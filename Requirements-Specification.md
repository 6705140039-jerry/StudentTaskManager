Requirements Specification

1. Introduction

1.1 Project Name

Student Task Manager

1.2 Purpose

This document defines the functional and non-functional requirements for the Student Task Manager application.

1.3 System Description

The Student Task Manager is a C# console application that allows students to manage academic tasks through a simple menu-driven interface.

⸻

2. User

The primary user of the system is a student.

The student can:

* Add a task
* View tasks
* Complete a task
* Delete a task
* Exit the application

⸻

3. Functional Requirements

FR-01: Student Information

The system shall store basic student information:

* Student ID
* Student name
* Student email

FR-02: Add Task

The system shall allow the user to create a new task.

A task shall contain:

* Task ID
* Student ID
* Title
* Description
* Due date
* Completion status

FR-03: View Tasks

The system shall display all tasks stored during the current application session.

The displayed information shall include:

* Task ID
* Task title
* Due date
* Completion status

FR-04: Complete Task

The system shall allow the user to mark a task as completed by entering its Task ID.

FR-05: Delete Task

The system shall allow the user to delete a task by entering its Task ID.

FR-06: Invalid Task ID

If the user enters a Task ID that does not exist, the system shall display an appropriate error message.

FR-07: Menu

The system shall provide a menu containing:

1. Add Task
2. View Tasks
3. Complete Task
4. Delete Task
5. Exit

FR-08: Exit

The system shall terminate when the user selects the Exit option.

⸻

4. Non-Functional Requirements

NFR-01: Usability

The application should provide a simple and understandable console interface.

NFR-02: Performance

The application should respond to normal user actions without noticeable delay.

NFR-03: Reliability

The application should handle normal user operations without crashing.

NFR-04: Maintainability

The source code should be organized into separate classes.

NFR-05: Portability

The application should run on a computer with a compatible .NET environment.

⸻

5. Object-Oriented Design Requirements

The application shall use Object-Oriented Programming concepts.

Student Class

Responsible for storing student information.

TaskItem Class

Responsible for storing task information and task status.

TaskManager Class

Responsible for managing the collection of tasks.

Program Class

Responsible for the main user interface and application flow.

⸻

6. User Stories

User Story 1

As a student, I want to add a task so that I can keep track of my assignments.

User Story 2

As a student, I want to view my tasks so that I know what work I need to complete.

User Story 3

As a student, I want to mark a task as completed so that I can identify finished work.

User Story 4

As a student, I want to delete a task so that I can remove tasks that I no longer need.

⸻

7. Constraints

* The first version is a console application.
* Tasks are stored in memory.
* Data is lost when the application closes.
* The application does not require an internet connection.
* The application does not require XAMPP.

⸻

8. Future Improvements

Future versions could include:

* SQLite or SQL Server database
* User login
* Task editing
* Task priorities
* Task categories
* Search and filtering
* Graphical user interface
* Web or mobile version

⸻

9. Requirements Summary

The system must provide the basic functionality required to create and manage student tasks while demonstrating good C# programming and OOP practices.