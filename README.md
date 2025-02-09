Task Management Application

     

Overview

The Task Management Application is a comprehensive solution built using Java Spring Boot to streamline task management. It offers secure authentication, session management, CRUD operations, and automated email notifications, all backed by scalable technologies.

Features

🔐 User Authentication with JWT

Secure token-based authentication using JWT.

Login and logout functionalities.


🚀 Session Management with Redis

Uses Redis for efficient and scalable session storage.

Ensures token validation and expiry.


👮 Role-Based Access Control

Admin-only user creation for better security.

Restricts access to sensitive endpoints.


📝 RESTful API for Task Management

CRUD operations (Create, Read, Update, Delete) for tasks.

JWT token security for all API endpoints.


💾 MongoDB for Data Storage

Uses MongoDB Atlas (NoSQL) for scalable and flexible data storage.

Ensures high availability and performance.


📩 Automated Email Notifications

Uses JavaMailSender for automated email notifications.

Scheduled cron jobs send reminders for task due dates.

Emails are sent to users with assigned tasks and pending tasks.


🛠 Technologies Used

Java 17+

Spring Boot (Spring Security, Spring Data, Spring Mail)

JWT (JSON Web Token)

Redis (Session Management)

MongoDB Atlas

Gradle


📌 Prerequisites

Ensure you have the following installed before running the project:

Java 17 or higher

Gradle

MongoDB Atlas (or a local MongoDB instance)

Redis

Any IDE (IntelliJ, VS Code, Eclipse)


📜 License

This project is licensed under the MIT License.
