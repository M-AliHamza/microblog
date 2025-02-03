
# Microblog

A simple microblogging application built with Flask.

## Features

- User authentication: Register and log in to your account.
- Post creation: Share your thoughts with others.
- Post management: Edit or delete your posts.
- User profiles: View your profile and others' profiles.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/M-AliHamza/microblog.git
   cd microblog
   ```

2. **Create a virtual environment:**

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install the dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set up the environment variables:**

   Create a `.flaskenv` file in the root directory with the following content:

   ```bash
   FLASK_APP=microblog.py
   FLASK_ENV=development
   ```

5. **Initialize the database:**

   ```bash
   flask db init
   flask db migrate -m "Initial migration."
   flask db upgrade
   ```

6. **Run the application:**

   ```bash
   flask run
   ```

   The application will be accessible at `http://127.0.0.1:5000/`.

## Testing

To run the test suite:

```bash
python tests.py
```

