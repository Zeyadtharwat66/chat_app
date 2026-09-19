# Real-Time Chat Application

A Spring Boot real-time chat backend with WebSocket messaging, MongoDB persistence, and a browser-based client.

## Features
- User management
- Chat rooms
- Real-time messaging over WebSocket
- MongoDB persistence
- REST endpoints for application operations
- Docker Compose setup for MongoDB and Mongo Express

## Tech Stack
- Java
- Spring Boot
- Spring WebSocket
- Spring Data MongoDB
- Maven
- Docker / Docker Compose
- MongoDB

## Configuration
Credentials are supplied through environment variables rather than being committed to the repository.

Copy the example environment file and provide local values before starting Docker services.

## Run
```bash
docker compose up -d
./mvnw spring-boot:run
```

On Windows:
```powershell
docker compose up -d
.mvnw.cmd spring-boot:run
```

The application uses port 8090 by default.

## Architecture
The backend is organized around user, chat, chat-room, and configuration components, with WebSocket support for real-time communication.

## Status
Portfolio project demonstrating Spring Boot, WebSocket, MongoDB, and containerized local infrastructure.
