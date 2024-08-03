# LearningINC backend

### Content

- [Installation](#installation)

## Installation

### Prerequisites

Before you can run this project locally, ensure you have the following installed:

Python (version 3.x or higher)

pip (Python package installer)

### SetUp

### Create a Virtual Environment

First, create a virtual environment to manage your project’s dependencies. This helps to keep your project isolated from other Python projects on your machine.

`python -m venv venv`

### Activate the Virtual Environment

On Windows: `source venv/bin/activate`

On macOS and Linux: `source venv/bin/activate`

### Install Dependencies

With the virtual environment activated, install the necessary dependencies from the requirements.txt file:

`pip install -r requirements.txt`

### Run Migrations

Apply the initial migrations to set up the database:

```
   python manage.py makemigrations
   python manage.py migrate
```

### Start the Development Server

Run the development server to ensure everything is set up correctly:

`python manage.py runserver`

you should see output indicating the server is running, and you can access your project at http://127.0.0.1:8000/.
