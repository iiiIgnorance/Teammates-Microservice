# Teammates-Microservice

## RESTful APIs
- /students
  - GET: list all student ids in the database
- /students/{sid}
  - GET: get the detailed information of a student
  - POST: modify the student's profile
  - DELETE: remove the student from the database
- /students/{sid}/courses
  - GET: list all courses the student is enrolled
  - POST: modify/add a course in the student's schedule
  - DELETE: remove a course from the student's schedule
- /students/{sid}/projects
  - GET: list all projects the student is working on
  - POST: modify/add a project in the student's todo list
  - DELETE: remove a project from the student's todo list
