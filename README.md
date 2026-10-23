

\# Student Management REST API



\## About

This project is a REST API developed using Python, Django REST Framework, and SQLite. It manages student records through CRUD operations.



\## Features

\- Create student records

\- View all students

\- View a student by ID

\- Update student details

\- Delete student records

\- Validate student names and email addresses

\- Handle errors for missing student records



\## Technologies Used

\- Python 3.9

\- Django 4.2

\- Django REST Framework

\- SQLite

\- GitHub



\## Installation and Setup



1\. Install Python 3.9 or later compatible with Django 4.2.

2\. Install Django:



&#x20;  py -m pip install "Django<5.0"



3\. Install Django REST Framework:



&#x20;  py -m pip install djangorestframework



4\. Open the project folder in Command Prompt.

5\. Run database migrations:



&#x20;  py manage.py migrate



6\. Start the server:



&#x20;  py manage.py runserver



7\. Open this URL in your browser:



&#x20;  http://127.0.0.1:8000/api/students/



\## API Endpoints



| Method | Endpoint | Description |

|--------|----------|-------------|

| GET | /api/students/ | List students |

| POST | /api/students/ | Create student |

| GET | /api/students/1/ | Retrieve student |

| PUT | /api/students/1/ | Update student |

| PATCH | /api/students/1/ | Partially update student |

| DELETE | /api/students/1/ | Delete student |



\## Database Model



Each student has:

\- id

\- name

\- email

\- course



\## Validation and Error Handling

\- Blank names are rejected.

\- Invalid email addresses are rejected.

\- Missing student IDs return HTTP 404.



\## Documentation

See API\_DOCUMENTATION.md for API details and sample responses.



