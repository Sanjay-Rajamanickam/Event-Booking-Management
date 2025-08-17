Event Management System
📌 Overview

The Event Management System is a full-stack web application designed to simplify the creation, management, and registration of events. The backend is powered by Spring Boot with a MySQL database, while the frontend is built using ReactJS .

This project provides a user-friendly interface for users to create/manage events and for attendees to register seamlessly.

✨ Features

🔑 User Authentication – Secure login and signup functionality

📝 Event Creation & Management – Organizers can create, edit, and delete events

👥 Attendee Registration – Users can register for available events

📋 Event Listing – View all upcoming events in one place

📱 Responsive UI – Works on both desktop and mobile devices

🛠️ Technologies Used

Backend

Java Spring Boot

MySQL

Hibernate

Frontend

ReactJS

HTML / CSS

Development Tools

IntelliJ IDEA (Backend)

Visual Studio Code (Frontend)

⚙️ Setup Instructions
✅ Prerequisites

Java 8 or higher

Node.js & npm

MySQL

IntelliJ IDEA or Eclipse

Visual Studio Code

🚀 Backend Setup

Clone the repository

git clone https://github.com/mehreen019/event_management_system.git
cd event_management_system


Create a MySQL database:

CREATE DATABASE event_management;


Update database credentials in src/main/resources/application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/event_management
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update


Run the backend:

Open project in IntelliJ IDEA

RunEventManagementSystemApplication.java

🎨 Frontend Setup

Navigate to frontend directory:

cd frontend


Install dependencies:

npm install


Start the frontend:

npm start

🎯 Usage

Open in browser: http://localhost:5173

Register and log in as a user.

Create and manage events via dashboard

Browse and register for events

📚 What I Learned

Building a full-stack web application with Spring Boot + ReactJS

Implementing Spring Security for authentication

Handling frontend-backend integration smoothly with REST APIs

Gained experience in managing cross-language applications

# 📌 Author
# Sanjay Rajamanickam 
📧 Contact: [pmraja75@gmail.com]  
🔗 GitHub: [https://github.com/Sanjay-Rajamanickam](https://github.com/Sanjay-Rajamanickam)
