# Smart House Project

A comprehensive Smart Home management system built with a Spring Boot backend and an Angular frontend, containerized with Docker.

## 🚀 Technologies

- **Backend**: Spring Boot (Java 17)
- **Frontend**: Angular
- **Database**: PostgreSQL
- **Containerization**: Docker & Docker Compose

## 🏗 Architecture

The project is composed of the following services:

- **postgres**: PostgreSQL database service.
- **backend**: Spring Boot application acting as the REST API.
- **frontend**: Angular application serving the user interface.

## 🛠 Prerequisites

- [Docker](https://www.docker.com/get-started) installed on your machine.

## 🏃‍♂️ Getting Started
![alt text](image.png)
![alt text](image-1.png)
![alt text](image-2.png)

1. **Clone the repository** (if not already done).

2. **Start the application** using Docker Compose:

   ```bash
   docker-compose up --build
   ```

3. **Access the application**:
   - Frontend: [http://localhost:80](http://localhost:80)
   - Backend API: [http://localhost:8085](http://localhost:8085)

## 📦 Features

- **Appareil Management**: Manage smart home devices.
- **Category Management**: Categorize devices for better organization.

## 🔧 Database

The project uses PostgreSQL. The database schema is automatically verified/updated by Hibernate on startup.

- **URL**: `jdbc:postgresql://localhost:5432/smart-house` (External) / `jdbc:postgresql://postgres:5432/smart-house` (Internal)
- **Username**: `postgres`
- **Password**: `root`
