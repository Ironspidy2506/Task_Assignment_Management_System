Project: Task Assignment and Management System

About The Project
1. Task Allocation Algorithm: Implement a round-robin task assignment algorithm where each team member receives an equal share of tasks to be completed daily. Tasks should be distributed evenly among team members.
2. Leave Management: The system should handle both planned and unplanned leaves of team members. If a team member is on planned leave, tasks should be redistributed among the remaining team members. In the case of unplanned leave, tasks should be assigned to all team members.
3. Escalation Mechanism: If a task remains incomplete for two consecutive days, an automated email and call should be triggered to the responsible team member. If the issue persists, an alert should be sent to all team members for resolution.
4. User Interface: 
- Super-Admin: Capable of adding, modifying, and deleting tasks. Can assign tasks to team members.
- Team Lead: Can rearrange tasks among team members. Has access to view task statuses and team member assignments.
- Member: Can view assigned tasks and mark them as completed.
5. Security: Implement a secure user-based login system to ensure that only authorized users can access the system and perform relevant actions based on their roles.

How the System Works
The Task Management System users can be only created by admin and managers. The admin user or the project Managers will create a new project at first along with some important details and references of the users. When creating a project, the admin or project managers must list all the employees that will handle the project's tasks. After the creation of the project, the regular employees are limited only to adding their work progress for the task of the project that they are assigned. They are also allowed to edit the data of the progress that they only submitted. Then, as the employees regularly updating the system about the progress they have done the project managers will read or scan their activities so the project manager can check or decide if the certain task is done and need to update the task status in the system. For the printable report of the system, only the admin users and project managers has an access to this function or feature of the system.


How to Run:- 
Clone the repository using git clone.
Download or set up any local web server that runs PHP script.(Such as Apache)
Open the online localhost database and create a new database name it "task_db".(http://localhost/phpmyadmin)
Import the SQL file from the database folder of the source code.
Copy and paste the source code to the location where your local web server accessing your local projects. Example for XAMPP('C:\xampp\htdocs')
Open a web browser and browse the project. E.g [http://localhost/task_management_system]
Now to start the project just visit the website mentioned above by following the steps.


Now for the various user access,
Admin Access
Email: admin@admin.com
Password: admin123

Managers Access
Email: lead@lead.com
Password: lead123

Users Access
Email: user@user.com
Password: user123
