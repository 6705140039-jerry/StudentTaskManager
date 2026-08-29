# Student Task Manager

> **Course:** 192-304 Agile Software Development\
> **Student:** Aung Myo Naing (6705140039)\
> **Project Type:** C# Student Task Manager

------------------------------------------------------------------------

## 📌 Project Overview

**Student Task Manager** is a simple C# console application designed to
help students organize and manage their academic tasks.

The application allows students to add, view, complete, and delete tasks
through a menu-driven console interface.

## 🌟 Core Features

1.  **Add Task:** Create a new task with task ID, student ID, title,
    description, due date, and completion status.
2.  **View Tasks:** Display the tasks currently stored in the
    application.
3.  **Complete Task:** Mark an existing task as completed using its Task
    ID.
4.  **Delete Task:** Remove an existing task using its Task ID.
5.  **Exit Application:** Close the application normally.

------------------------------------------------------------------------

## 📚 Project Documentation

All project documents are organized under the [`docs/`](./docs) folder:

  -------------------------------------------------------------------------------------------------------------------------
  Document              Description                                            Direct Link
  --------------------- --------------------- -----------------------------------------------------------------------------
  **Project Charter**   Project background,             [📄 `docs/Project-Charter.md`](./docs/Project-Charter.md)
                        objectives, scope,    
                        stakeholders,         
                        deliverables, risks,  
                        and timeline          

  **Requirements        Functional and                                             [📄
  Specification**       non-functional         `docs/Requirements-Specification.md`](./docs/Requirements-Specification.md)
                        requirements, OOP     
                        design requirements,  
                        user stories, and     
                        constraints           

  **Acceptance          Acceptance criteria         [📄 `docs/Acceptance-Criteria.md`](./docs/Acceptance-Criteria.md)
  Criteria**            and acceptance tests  
                        for the application's 
                        main features         

  **Database Design**   Proposed Student and            [📄 `docs/Database-Design.md`](./docs/Database-Design.md)
                        Task database         
                        entities,             
                        relationships,        
                        tables, and SQL       
                        structure             
  -------------------------------------------------------------------------------------------------------------------------

------------------------------------------------------------------------

## 🏗️ Tech Stack

-   **Language:** C#
-   **Framework:** .NET
-   **Application Type:** Console Application
-   **Development Environment:** Visual Studio / VS Code
-   **Version Control:** Git and GitHub
-   **Documentation:** Markdown

------------------------------------------------------------------------

## 📁 Project Structure

``` text
StudentTaskManager/
│
├── docs/
│   ├── Project-Charter.md
│   ├── Requirements-Specification.md
│   ├── Acceptance-Criteria.md
│   └── Database-Design.md
│
└── README.md
```

> `bin/` and `obj/` are generated build folders and normally should not
> be committed to GitHub.

------------------------------------------------------------------------

## ▶️ How to Run

Make sure a compatible .NET environment is installed.

From the project folder, run:

``` bash
dotnet run
```

The Student Task Manager menu should then be displayed.

------------------------------------------------------------------------

## 🎯 Project Goal

The goal of this project is to demonstrate basic C# programming and
Object-Oriented Programming concepts while creating a useful task
management application for students.

The project also includes Agile software development documentation and
is published on GitHub.
