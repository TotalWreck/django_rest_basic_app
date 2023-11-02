# Django REST API Basic App Readme

This is a basic Django REST API application. Follow the instructions below to install and run this app from a Git repository.

## Installation

### Prerequisites

Before you begin, ensure you have the following software installed on your system:

- Python (3.6 or higher)
- pip (Python package manager)
- git (Version control system)

### Clone the Repository

1. Open your terminal or command prompt.
2. Change to the directory where you want to store the project.
3. Clone the Git repository using the following command:

   ```
   git clone https://github.com/TotalWreck/django_rest_basic_app.git
   ```

### Create a Virtual Environment (Optional but recommended)

It's a good practice to create a virtual environment to isolate project dependencies. Follow these steps to create and activate a virtual environment:

1. Navigate to the project directory:

   ```
   cd django_rest_basic_app
   ```

2. Create a virtual environment:

   ```
   python -m virtualenv venv
   ```

3. Activate the virtual environment:

   - On macOS and Linux:

     ```
     source venv/bin/activate
     ```

   - On Windows (Command Prompt):

     ```
     venv\Scripts\activate
     ```

   - On Windows (PowerShell):

     ```
     .\venv\Scripts\Activate.ps1
     ```

### Install Dependencies

Install the required Python packages using pip:

```
pip install -r requirements.txt
```

## Usage

1. Navigate to the project directory if you haven't already:

   ```
   cd django_rest_basic_app
   ```

2. Migrate the database to create the necessary tables:

   ```
   python manage.py migrate
   ```

3. Create a superuser (admin account) for the Django admin interface:

   ```
   python manage.py createsuperuser
   ```

   Follow the prompts to create an admin account with a username, email, and password.

4. Run the development server:

   ```
   python manage.py runserver
   ```

   The server will start, and you can access the app at `http://127.0.0.1:8000/` or `http://127.0.0.1:8000/admin` in your web browser.

Happy coding!