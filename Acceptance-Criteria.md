Acceptance Criteria

1. Purpose

This document defines the conditions that must be satisfied for the Student Task Manager project to be accepted as complete.

⸻

2. Acceptance Criteria

AC-01: Application Starts

Given the application has been built successfully,

When the user runs the application,

Then the Student Task Manager menu should be displayed.

⸻

AC-02: Add Task

Given the application is running,

When the user selects “Add Task” and enters valid task information,

Then a new task should be created successfully.

The task must contain:

* Task ID
* Student ID
* Title
* Description
* Due date
* Completion status

⸻

AC-03: View Tasks

Given at least one task exists,

When the user selects “View Tasks”,

Then the system should display the saved tasks.

The display should include:

* Task ID
* Title
* Due date
* Completion status

⸻

AC-04: Complete Task

Given a task exists,

When the user enters a valid Task ID to complete the task,

Then the task status should change to completed.

⸻

AC-05: Delete Task

Given a task exists,

When the user enters a valid Task ID to delete it,

Then the task should be removed from the task list.

⸻

AC-06: Invalid Task ID

Given the user enters a Task ID that does not exist,

When the system searches for the task,

Then the system should display “Task not found.”

⸻

AC-07: Empty Task List

Given no tasks have been added,

When the user selects “View Tasks”,

Then the system should display a message indicating that no tasks are available.

⸻

AC-08: Exit Application

Given the application is running,

When the user selects “Exit”,

Then the application should terminate normally.

⸻

3. Acceptance Test Table

ID	Feature	Expected Result	Status
AC-01	Start application	Menu is displayed	Pending
AC-02	Add task	Task is added	Pending
AC-03	View tasks	Tasks are displayed	Pending
AC-04	Complete task	Task becomes completed	Pending
AC-05	Delete task	Task is removed	Pending
AC-06	Invalid ID	Error message displayed	Pending
AC-07	Empty list	No-task message displayed	Pending
AC-08	Exit	Application closes	Pending

⸻

4. Definition of Done

The project is considered complete when:

* All required features work correctly.
* The application can be run successfully.
* The acceptance tests pass.
* The source code is organized.
* The four project documents are complete.
* The project has been uploaded to GitHub.