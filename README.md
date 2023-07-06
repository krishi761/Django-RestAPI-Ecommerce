# Django-RestAPI-Ecommerce

Before running the application, make sure you have the following installed on your machine:

    Python 3.9 or later
    pip package manager
    PostgreSQL (if using PostgreSQL as the database)

Setup

    Clone the Repository

    shell

git clone https://github.com/your-username/ecommerce-store.git
cd ecommerce-store

Create and Activate a Virtual Environment

shell

python3 -m venv env
source env/bin/activate

Install Dependencies

shell

pip install -r requirements.txt

Database Configuration

    If you are using SQLite as the database (default configuration):
        No further configuration is needed.
    If you are using PostgreSQL as the database:
        Create a PostgreSQL database.
        Update the database settings in myproject/settings.py file, including the database name, user, and password.

Apply Migrations

shell

python manage.py migrate

Create Superuser (Admin)

shell

python manage.py createsuperuser

Follow the prompts to provide a username and password for the admin user.

Run the Application

shell

    python manage.py runserver

    The application will be accessible at http://127.0.0.1:8000/.

    Access the Admin Interface

    To access the admin interface, go to http://127.0.0.1:8000/admin/ and log in using the superuser credentials created in step 6.

    API Documentation
        API documentation and available endpoints can be found at http://127.0.0.1:8000/api/docs/.
        Use Postman or a similar tool to interact with the API endpoints. Import the provided Postman collection for convenience.

Running Tests

To run the tests for the application, use the following command:

shell

python manage.py test

Deployment

The application can be deployed using various hosting providers and platforms. Make sure to update the necessary settings and configurations for your deployment environment.

