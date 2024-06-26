# MU Student Management System

This is a Student Management System created by Maisha Ibnat (221-115-054), Panna Begum (221-115-077) & Kazi Tanzina Akter Hridika (221-115-051) for Project-300 course.

## Features of this Project

### A. Admin Users Can

1. See Overall Summary Charts of Stuudents Performance, Staffs Perfomrances, Courses, Subjects, Leave, etc.
2. Manage Staffs (Add, Update and Delete)
3. Manage Students (Add, Update and Delete)
4. Manage Course (Add, Update and Delete)
5. Manage Subjects (Add, Update and Delete)
6. Manage Sessions (Add, Update and Delete)
7. View Student Attendance
8. Review (Approve/Reject) Student/Staff Leave

### B. Staff/Teachers Can

1. See the Overall Summary Charts related to their students, their subjects, leave status, etc.
2. Take/Update Students Attendance
3. Add/Update Result
4. Apply for Leave

### C. Students Can

1. See the Overall Summary Charts related to their attendance, their subjects, leave status, etc.
2. View Attendance
3. View Result
4. Apply for Leave

## How to Install and Run this project?

### Pre-Requisites:

1. Install Git Version Control
   [ https://git-scm.com/ ]

2. Install Python Latest Version
   [ https://www.python.org/downloads/ ]

3. Install Pip (Package Manager)
   [ https://pip.pypa.io/en/stable/installing/ ]

### Installation

**1. Create a Folder where you want to save the project**

**2. Create a Virtual Environment and Activate**

Install Virtual Environment First

```
$  pip install virtualenv
```

Create Virtual Environment

For Windows

```
$  python -m venv venv
```

For Mac

```
$  python3 -m venv venv
```

Activate Virtual Environment

For Windows

```
$  source venv/scripts/activate
```

For Mac

```
$  source venv/bin/activate
```

**3. Clone this project**

```
$  git clone https://github.com/vijaythapa333/django-student-management-system.git
```

Then, Enter the project

```
$  cd django-student-management-system
```

**4. Install Requirements from 'requirements.txt'**

```python
$  pip install -r requirements.txt
```

**5. Add the hosts**

-   Got to settings.py file
-   Then, On allowed hosts, Add [‘*’].

```python
ALLOWED_HOSTS = ['*']
```

_No need to change on Mac._

**6. Now Run Server**

Command for PC:

```python
$ python manage.py runserver
```

Command for Mac:

```python
$ python3 manage.py runserver
```

**7. Login Credentials**

Create Super User (Admin)

```
$  python manage.py createsuperuser
```

Then Add Email, Username and Password

**or Use Default Credentials**

_Default Admin Credential_
Email: admin@gmail.com
Password: admin

_Default Staff Credential_
Email: staff@gmail.com
Password: staff

_Default Student Credential_
Email: student@gmail.com
Password: student
