﻿# MU Student Management System

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

![Screenshot (159)](https://github.com/panna-talukdar/mu-student-management-system/assets/123767495/a9e401ae-c0e1-4c5b-b46c-44ff802f2f95)
![Screenshot (160)](https://github.com/panna-talukdar/mu-student-management-system/assets/123767495/ffc325c5-1bd1-4f1d-b613-9dacff1f02c6)
![Screenshot (163)](https://github.com/panna-talukdar/mu-student-management-system/assets/123767495/58de0d44-b70e-417a-9779-226e33f63638)
![Screenshot (164)](https://github.com/panna-talukdar/mu-student-management-system/assets/123767495/5fc4df7d-0cf4-40f2-9362-41aca7620327)
![Screenshot (165)](https://github.com/panna-talukdar/mu-student-management-system/assets/123767495/a00cfb71-fa33-4b93-a693-27395f07e8f8)
![Screenshot (166)](https://github.com/panna-talukdar/mu-student-management-system/assets/123767495/a6eb2db5-45e5-4c98-a697-7e4ba6fadeea)
![Screenshot (167)](https://github.com/panna-talukdar/mu-student-management-system/assets/123767495/df860f5a-97dd-4818-8ff8-4495624b9752)
![Screenshot (168)](https://github.com/panna-talukdar/mu-student-management-system/assets/123767495/d4d88c9c-0f3f-405f-8a0e-66bf1a1b641a)
![Screenshot (169)](https://github.com/panna-talukdar/mu-student-management-system/assets/123767495/706722fa-e391-4088-871b-d9d899e3dd89)











   

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
