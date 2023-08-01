# Simple CardView Django App

This project is a very simple project as part of my assignment in SWE Project and Django Course in Phitron

## Prerequisites

Before running the project, ensure you have the following installed:

- Python (version 3.7 or higher)
- Django (version 3.0 or higher)
- Virtualenv (optional)

## Getting Started

Follow these steps to run the Django project locally:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/mojnomiya/Simple-CardView-App-Using-Django.git
   ```

2. Navigate to the project directory:

   ```bash
   cd assignment_1
   ```

3. Create a virtual environment (optional but recommended):

   ```bash
   # Windows
   python -m venv venv
   
   # macOS / Linux
   python3 -m venv venv
   ```

4. Activate the virtual environment:

   ```bash
   # Windows
   venv\\Scripts\\activate
   
   # macOS / Linux
   source venv/bin/activate
   ```

5. Install project dependencies:

   ```bash
   pip install -r requirements.txt
   ```

6. Apply database migrations:

   ```bash
   python manage.py migrate
   ```

7. Create a superuser (optional, if you want access to the Django admin interface):

   ```bash
   python manage.py createsuperuser
   ```

8. Start the development server:

   ```bash
   python manage.py runserver
   ```

9. Open your web browser and go to `http://127.0.0.1:8000/` to view the Django project.

