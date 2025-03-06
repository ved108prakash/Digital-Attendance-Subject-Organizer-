# Digital-Attendance-Subject-Organizer-


# Overview:-
Class360 is a Django-based web application designed to streamline student attendance tracking and subject organization. It provides role-based access for students and teachers, ensuring a smooth and efficient management system.

# Key Features:-

        --> User Roles: Separate modules for Students and Teachers with role-based access.
        --> Attendance Management: Teachers can mark and view student attendance records.
        --> Leave Requests: Teachers can apply for leave, and Admin can approve the leave requests.
        --> Authentication & Security: Secure login/logout system with role-based authentication.
        --> Responsive UI: Frontend built with HTML, CSS, and JavaScript for an intuitive user experience.
        --> Database: Uses MySQL for efficient data storage and retrieval.


# Installation Guide:-
        1. Clone the repository:
                 git clone <GitHub-Link>
        2. Create a virtual environment and activate it:
                 python -m venv venv
                 source venv/bin/activate  # On macOS/Linux
                 venv\Scripts\activate  # On Windows
        3. Install dependencies:
                 pip install -r requirements.txt
        4. Configure the database settings in settings.py.
        5. Apply migrations:
                 python manage.py migrate
        6. Create a superuser (optional):
                 python manage.py createsuperuser

        7. Run the development server:
                 python manage.py runserver

# Usage:-
     -->Teachers can log in, mark attendance, and request leave.

     -->Admins can manage users and approve leave requests.

     -->Students can view their attendance records.

# Technologies Used:-
             -->Backend: Django (Python)

             -->Frontend: HTML, CSS, JavaScript

             -->Database: MySQL
