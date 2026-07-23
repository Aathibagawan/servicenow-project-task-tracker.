# ServiceNow Project Task Tracker

A ServiceNow-based project task tracking application designed to help teams create, assign, monitor, and manage project-related tasks efficiently. The application provides a centralized workspace for tracking task progress, priorities, deadlines, assignees, and project status.

## Overview

The **ServiceNow Project Task Tracker** helps users organize work items within projects and maintain clear visibility of task ownership and progress.

It is built to demonstrate practical ServiceNow development concepts such as custom tables, forms, workflows, roles, business rules, notifications, reports, and automation.

## Features

* Create and manage project tasks
* Assign tasks to users or team members
* Track task status, priority, and due dates
* Monitor project progress through task records
* Maintain task descriptions and work updates
* Filter and search tasks easily
* Support role-based access for users and administrators
* Automate task-related actions using ServiceNow workflows or business rules
* Generate reports for task status, priority, and completion progress

## Modules

### Project Management

Create and maintain project records with details such as project name, description, start date, end date, project manager, and current status.

### Task Management

Users can create tasks under a project and manage important information including:

* Task number
* Task name
* Project reference
* Assigned user
* Priority
* Status
* Due date
* Description
* Work notes
* Completion details

### Task Status Tracking

Tasks can be tracked using statuses such as:

* New
* In Progress
* On Hold
* Completed
* Closed
* Cancelled

### Priority Management

Tasks can be categorized based on urgency:

* Critical
* High
* Medium
* Low

### Notifications and Automation

The application can notify assigned users when:

* A new task is assigned
* A task priority is updated
* A due date is approaching
* A task is completed or closed
* Task details are modified

## Technology Stack

* **Platform:** ServiceNow
* **Development Type:** ServiceNow Scoped Application / Custom Application
* **Scripting:** JavaScript
* **Database:** ServiceNow Tables
* **Automation:** Business Rules, Flow Designer, Workflows, Notifications
* **Reporting:** ServiceNow Reports and Dashboards
* **Version Control:** Git and GitHub

## Application Workflow

```text
Project Creation
      ↓
Task Creation
      ↓
Task Assignment
      ↓
Work Progress Updates
      ↓
Status Monitoring
      ↓
Task Completion
      ↓
Project Progress Reporting
```

## Installation and Setup

1. Log in to your ServiceNow instance with administrator access.

2. Import the project files or update set into your ServiceNow Personal Developer Instance or target ServiceNow instance.

3. Navigate to the application module from the ServiceNow application navigator.

4. Configure users, roles, task categories, and project details as required.

5. Create project records and begin adding tasks.

6. Assign tasks to users and track their progress through the task tracker interface.

## Configuration

Before using the application, configure the following items based on your ServiceNow instance requirements:

* User roles and permissions
* Task statuses
* Priority levels
* Notification templates
* Workflow or Flow Designer rules
* Custom tables and fields
* Reports and dashboards

## Suggested Custom Tables

| Table Name   | Purpose                                          |
| ------------ | ------------------------------------------------ |
| Project      | Stores project-level information                 |
| Project Task | Stores individual tasks under a project          |
| Task Update  | Stores work notes, comments, or activity updates |
| Team Member  | Maintains user or team assignment information    |

## User Roles

### Administrator

Administrators can manage application configurations, users, task records, workflows, reports, and permissions.

### Project Manager

Project managers can create projects, create tasks, assign team members, monitor progress, and review task completion.

### Team Member

Team members can view assigned tasks, update task status, add work notes, and complete assigned work.

## Screenshots

Add screenshots of the following pages here for a stronger project presentation:

* Project creation form
* Task creation form
* Task list view
* Assigned task dashboard
* Project progress report
* Notification or workflow example

```text
/screenshots
  ├── project-form.png
  ├── task-list.png
  ├── task-form.png
  └── dashboard.png
```

## Future Enhancements

* Add Kanban board view for task tracking
* Add email and mobile notifications
* Include task comments and attachments
* Add task dependency management
* Add project milestone tracking
* Create advanced dashboards with charts
* Integrate with external tools such as GitHub, Jira, or Microsoft Teams
* Add SLA tracking for high-priority tasks
* Implement approval workflows for task closure

## Learning Outcomes

This project demonstrates knowledge of:

* ServiceNow application development
* Custom table creation
* Form and list configuration
* User roles and access control
* Business rules and client scripts
* Flow Designer and workflow automation
* Notifications
* Reporting and dashboards
* GitHub version control

## Repository Structure

```text
servicenow-project-task-tracker/
│
├── update-set/
│   └── ServiceNow project update set files
│
├── documentation/
│   └── Project documentation and setup guides
│
├── screenshots/
│   └── Application screenshots
│
├── scripts/
│   └── ServiceNow scripts and configurations
│
└── README.md
```

## Author

**Aathibagawan M.**

Computer Science and Engineering Graduate
ServiceNow Learner | Python Full Stack Developer | Software Developer

## License

This project is created for learning, academic, and portfolio purposes.

Feel free to fork, explore, and improve the project.
# servicenow-project-task-tracker.
