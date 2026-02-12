🎙 Podcast Management System

The Podcast Management System is a software application designed to manage podcasts, episodes, and related information efficiently.
It allows users or administrators to organize content, maintain records, and perform operations such as adding, updating, searching, and deleting podcast data.

This project was developed as part of my Computer Engineering studies to practice programming, object-oriented design, and data management.

🎯 Project Objectives

The main goals of this system are:

Provide a structured way to manage podcasts and episodes

Apply Object-Oriented Programming (OOP) principles

Manipulate and store data efficiently

Build a clean and maintainable software architecture

⚙️ System Overview

The application maintains information about podcasts such as titles, hosts, categories, and episodes.

Typical workflow:

User or admin adds a podcast.

Episodes can be created and linked to a podcast.

Information can be viewed, updated, searched, or removed.

The system ensures organized and consistent data handling.

🚀 Features

➕ Add new podcasts

➕ Add and manage episodes

✏ Update podcast or episode information

❌ Delete records

🔎 Search and display data

📋 Structured storage and retrieval

🛠 Technologies Used

(edit depending on what you used)

Programming Language: Java

Concepts: OOP, data structures, modular design

Tools: Git, GitHub, VS Code / IntelliJ / Eclipse

🧩 System Design

The project follows a modular folder structure, separating logic from data models:

src/
 ├── app/      → program flow and user interface
 │    ├── Main.java
 │    └── PodcastManager.java
 └── model/    → data models and entities
      ├── Podcast.java
      └── Episode.java

data/          → stores persistent data (JSON, CSV, etc.)
images/        → screenshots of program
docs/          → extra documentation


app/ contains the main program and managers handling user interactions

model/ contains the data entities like Podcast and Episode

Optional folders like data/, images/, and docs/ improve organization and professionalism

This separation improves readability, maintainability, and scalability.

▶ How to Run

Clone the repository

Open the project in your IDE

Compile and run the Main.java program

Use the menu/interface to manage podcasts

📈 Learning Outcomes

Through this project, I strengthened my understanding of:

Object-oriented programming

Designing structured and modular applications

Managing relationships between entities

Writing maintainable and reusable code

Organizing a professional project structure

👩‍💻 Author

Majdoline
Computer Engineering Student
