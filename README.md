# Real-Time Chat Application

A real-time chat backend built with **Java**, **Spring Boot**, **WebSocket**, and **MongoDB**.

The project provides backend functionality for users, chat rooms, and real-time messaging, with Docker Compose for local MongoDB infrastructure.

## 🚀 Technologies

* Java
* Spring Boot
* Spring WebSocket
* Spring Data MongoDB
* MongoDB
* Maven
* Docker / Docker Compose
* RESTful APIs

## 📁 Project Structure

```text
src/
├── main/
│   ├── java/
│   └── resources/
│
├── docker-compose.yml
├── pom.xml
├── .env.example
└── README.md
```

The backend is organized around user, chat, chat-room, and configuration components.

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Zeyadtharwat66/realtime-chat-app.git
```

Navigate to the project:

```bash
cd realtime-chat-app
```

Install and run the project with Maven:

```bash
./mvnw spring-boot:run
```

On Windows:

```powershell
.mvnw.cmd spring-boot:run
```

## 🔐 Environment Variables

Create your environment configuration based on `.env.example`.

The project uses environment variables for MongoDB credentials and connection settings.

> **Note:** Do not commit real database credentials.

## ▶️ Running the Project

Start the MongoDB services with Docker Compose:

```bash
docker compose up -d
```

Then start the Spring Boot application.

The application uses port **8090** by default.

## 📌 Main Features

* User management
* Chat rooms
* Real-time messaging with WebSocket
* MongoDB persistence
* REST endpoints
* Dockerized MongoDB infrastructure

## 🛠️ Architecture

The application combines REST APIs for application operations with WebSocket communication for real-time messaging.

```text
Client
  ↓
Spring Boot
  ├── REST APIs
  └── WebSocket
        ↓
     MongoDB
```

## 🔮 Future Improvements

* User authentication and authorization
* Private messaging
* Message history pagination
* Online/offline user status
* Improved chat-room management
* Production deployment

## 👨‍💻 Author

**Zeyad Tharwat**

## 📄 License

This project is for learning and development purposes.
