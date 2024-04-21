# Leave Management System

The Leave Management System is a web-based application designed to streamline and automate the process of managing employee leave requests within an organization. It provides an efficient way for employees to request leave, managers to approve or reject requests, and administrators to oversee the entire leave management process.

## Features

- 🔒 User Authentication: Secure login system for employees, managers, and administrators.
- 👥 Role-based Access Control: Different levels of access based on user roles, such as employee, manager, and administrator.
- 📝 Leave Request Management: Employees can submit leave requests, which are then routed to their respective managers for approval.
- 🔄 Manager Approval Workflow: Managers can view leave requests from their team members and approve or reject them.
- 📊 Administrator Dashboard: Administrators have access to a dashboard where they can view leave requests from all employees, generate reports, and manage user accounts.
- 📧 Email Notifications: Automated email notifications sent to employees and managers upon submission, approval, or rejection of leave requests.
- 📅 Calendar View: Visual representation of leave requests on a calendar for better scheduling and planning.

## Technologies Used

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, JavaScript
- **Database:** SQLite (for development), PostgreSQL (for production)
- **Authentication:** Django's built-in authentication system
- **Email:** SMTP for sending email notifications
- **Version Control:** Git, GitHub

## Installation

1. Install PostgreSQL
2. Clone the repository: `git clone (https://github.com/ASHIKinfohack/LEAVE-TRACK)`
3. Navigate to the project directory: `cd leave-management-system`
4. Install dependencies: `pip install -r requirements.txt`
5. Apply database migrations: `python manage.py migrate`
6. Run the development server: `python manage.py runserver`

## Usage

- Access the application through the browser: [http://localhost:8000](http://localhost:8000)
- Log in using your credentials:
  - For administrators: Use the superuser credentials created during installation.
  - For managers and employees: Use the credentials provided by the administrator.
