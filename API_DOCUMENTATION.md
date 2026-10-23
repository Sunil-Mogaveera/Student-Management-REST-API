

\# Student Management REST API



\## Project Description

A REST API built using Python, Django REST Framework, and SQLite to manage student records.



\## Base URL

http://127.0.0.1:8000/api/



\## Student Model

\- id: Automatically generated student ID

\- name: Student name

\- email: Valid and unique email

\- course: Student course



\## API Endpoints



| Method | Endpoint | Description |

|--------|----------|-------------|

| GET | /students/ | Get all students |

| POST | /students/ | Create a student |

| GET | /students/1/ | Get a student by ID |

| PUT | /students/1/ | Update a student |

| PATCH | /students/1/ | Partially update a student |

| DELETE | /students/1/ | Delete a student |



\## Sample POST Request



{

&#x20; "name": "Rahul Kumar",

&#x20; "email": "rahul@example.com",

&#x20; "course": "BCA"

}



\## Successful Responses

\- 200 OK: Data retrieved or updated

\- 201 Created: Student created

\- 204 No Content: Student deleted



\## Error Responses

\- 400 Bad Request: Invalid input

\- 404 Not Found: Student does not exist



\## Database

SQLite is used to store student records.



