
College Enterprise Resource Planner
This is a College Enterprise Resource Planner Developed by me and my project partners for my college. We use Python/Django Framwork for building an fully functional web application. (If facing problem!! : put discussion)

Deployed at SIGCE SIGCE v1.1.0
For viewing the home page of student you must have required credentials given below

-> E-Mail : student@student.com -> Password : student@erp

Features of this Project
A. Admin Users Can
See Overall Summary Charts of Students Performances, Staff Performances, Courses, Subjects, Leave, etc.
Manage Staff (Add, Update and Delete)
Manage Students (Add, Update and Delete)
Manage Course (Add, Update and Delete)
Manage Subjects (Add, Update and Delete)
Manage Sessions (Add, Update and Delete)
View Student Attendance
Review and Reply Student/Staff Feedback
Review (Approve/Reject) Student/Staff Leave
B. Staff/Teachers Can
See the Overall Summary Charts related to their students, their subjects, leave status, etc.
Take/Update Students Attendance
Add/Update Result
Apply for Leave
Send Feedback to HOD
C. Students Can
See the Overall Summary Charts related to their attendance, their subjects, leave status, etc.
View Attendance
View Result
Apply for Leave
Send Feedback to HOD
Support Developer
Add a Star 🌟 to this 👆 Repository
Follow on Github & LinkedIn
How to Install and Run this project?
Pre-Requisites:
Install Git Version Control [ https://git-scm.com/ ]

Install Python Latest Version [ https://www.python.org/downloads/ ]

Install Pip (Package Manager) [ https://pip.pypa.io/en/stable/installing/ ]

Alternative to Pip is Homebrew

Installation
1. Create a Folder where you want to save the project

2. Create a Virtual Environment and Activate

Install Virtual Environment First

$  pip install virtualenv
Create Virtual Environment

For Windows

$  python -m venv venv
For Mac

$  python3 -m venv venv
For Linux

$  virtualenv .
Activate Virtual Environment

For Windows

$  source venv/scripts/activate
For Mac

$  source venv/bin/activate
For Linux

$  source bin/activate
3. Clone this project

$  git clone https://github.com/Ansarimajid/College-ERP.git
Then, Enter the project

$  cd College-ERP
4. Install Requirements from 'requirements.txt'

$  pip3 install -r requirements.txt
5. Add the hosts

Got to settings.py file
Then, On allowed hosts, Use [] as your host.
ALLOWED_HOSTS = []
Do not use the fault allowed settings in this repo. It has security risk!

6. Now Run Server

Command for PC:

$ python manage.py runserver
Command for Mac:

$ python3 manage.py runserver
Command for Linux:

$ python3 manage.py runserver
7. Login Credentials

Create Super User (HOD) Command for PC:

$  python manage.py createsuperuser
Command for Mac:

$  python3 manage.py createsuperuser
Command for Linux:

$  python3 manage.py createsuperuser
Project's Journey
| Admin/Staff/Student Login | | Add and Edit Course |

 Add and Edit Staff
 Add and Edit Student
 Add and Edit Subject
 Upload Staff's Picture
 Upload Student's Picture
 Sidebar Active Status
 Named URLs
 Model Forms for adding student
 Model Forms for all
 Views Permission (MiddleWareMixin)
 Attendance and Update Attendance
 Password Reset Via Email
 Apply For Leave
 Students Can Check Attendance
 Check Email Availability
 Reply to Leave Applications
 Reply to Feedback
 Admin View Attendance
 Password Change for Admin, Staff and Students using set_password()
 Admin Profile Edit
 Staff Profile Edit
 Student Profile Edit
 Student Dashboard Fixed
 Passing Page Title From View - Improved
 Staff Dashboard Fixed
 Admin Dashboard Fixed
 Staff Add Student's Result
 Staff Edit Result Using CBVs (Class Based Views)
 Google CAPTCHA
 Student View Result
 Change all links to be dynamic
 Code Restructure - Very Important
