📝 Journal Management Application

A backend Journal Management Application built using Java, Spring Boot, and MongoDB that allows users to create, view, update, and delete personal journal entries through RESTful APIs.

This project was developed as a learning-focused backend application, following best practices in Spring Boot while emphasizing clean architecture, API design, and database integration.

🚀 Features

User-based journal management

Create, read, update, and delete (CRUD) journal entries

RESTful API design using Spring Boot

MongoDB for data persistence

Controller–Service–Repository layered architecture

Basic error handling and clean request/response flow

🛠️ Tech Stack

Language: Java

Framework: Spring Boot

Database: MongoDB

API Style: REST

Build Tool: Maven

Version Control: Git & GitHub

📂 Project Structure
journalApp
│
├── controller     → Handles API requests
├── service        → Business logic layer
├── repository     → MongoDB database interactions
├── entity         → Data models
└── application    → Main Spring Boot application

📌 API Endpoints (Sample)
Method	Endpoint	Description
GET	/journal/{username}	Get all journal entries of a user
POST	/journal/{username}	Add a new journal entry
PUT	/journal/id/{id}	Update an existing journal
DELETE	/journal/id/{id}	Delete a journal entry
⚙️ How to Run the Project
Prerequisites

Java 17+

Maven

MongoDB (running locally or via MongoDB Atlas)

Steps

Clone the repository

git clone https://github.com/your-username/journal-app.git


Navigate to the project folder

cd journal-app


Configure MongoDB connection in application.yml / application.properties

Run the application

mvn spring-boot:run

Access APIs via Postman or browser


📖 Learning Outcomes

Hands-on experience with Spring Boot backend development

Understanding of REST APIs and HTTP methods

Working with MongoDB and Spring Data

Applying layered architecture and clean code principles

Improved debugging and problem-solving skills

🙌 Acknowledgment

This project was built by following a structured learning resource and enhanced through hands-on implementation to strengthen backend development skills.
