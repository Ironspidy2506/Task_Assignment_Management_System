# 📝 Task Assignment and Management System

## 📖 About the Project

The Task Assignment and Management System is designed to automate **task allocation**, **leave management**, and **task escalation** within teams. It distributes tasks evenly, manages both planned and unplanned leaves, and has an escalation mechanism to handle incomplete tasks.

---

## 🌟 Key Features

1. **Task Allocation Algorithm** 🎯
   - Implements a round-robin task assignment, ensuring each team member receives an equal share of tasks daily for balanced workload distribution.

2. **Leave Management** 🏖️
   - Supports both **planned** and **unplanned leaves**:
     - **Planned Leave**: Redistributes tasks among the remaining team members.
     - **Unplanned Leave**: Automatically assigns tasks to all available team members.

3. **Escalation Mechanism** 🚨
   - Automatically escalates tasks if they remain incomplete for two consecutive days:
     - Sends an email and triggers a call to the responsible team member.
     - Alerts all team members if the task remains incomplete.

4. **User Interface** 🎛️
   - **Super-Admin**: Can add, modify, and delete tasks, and assign tasks to team members.
   - **Team Lead**: Can rearrange tasks among team members and view task statuses.
   - **Member**: Can view assigned tasks and mark them as completed.

5. **Security** 🔒
   - Secure, role-based login system to ensure that only authorized users can access the system and perform actions based on their roles.

---

## 🛠️ How the System Works

- Only Admins and Managers can create new users and assign them to projects.
- Admins or Managers can create new projects, adding relevant details and assigning employees to handle tasks.
- Team members update the system with their task progress, while Project Managers review these updates.
- Only Admins and Managers have access to generate a report for the project.

---

## 🚀 Getting Started

### Prerequisites
- Local web server for PHP (e.g., XAMPP, WAMP)
- MySQL Database

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/task_management_system.git

2. **Set Up Database**
- Open your local server database interface (e.g., http://localhost/phpmyadmin).
- Create a new database named task_db.
- Import the task_db.sql file from the database folder in this repository.

2. **Configure Local Server**
- Copy the project files into your server’s root directory.
- Example for XAMPP: C:\xampp\htdocs\task_management_system.

4. **Run the Project**
- Open a browser and go to http://localhost/task_management_system to access the application.

--

## 👥 User Roles and Access
### Admin Access
- Email: `admin@admin.com`
- Password: `admin123`

### Manager Access
- Email: `lead@lead.com`
- Password: `lead123`

### User Access
- Email: `user@user.com`
- Password: `user123`

--

Thank you for using the Task Assignment and Management System! 🛠️ Happy tasking!
