# Cloud Development Final Project
Dockerized Todo Application on AWS
## Project Overview
This project is a simple cloud-based Todo Application designed to help users manage daily tasks efficiently.
Users can create, view, update, and delete tasks through a web interface.

The main goal of the project is to demonstrate the use of:

- Full-stack web development
- Docker containerization
- Database integration
- Cloud deployment concepts using AWS

The application is built using:

Frontend: React
Backend: Node.js + Express
Database: MySQL
Containerization: Docker & Docker Compose

## Project Objectives

The project was developed to:

- Build a functional CRUD web application
- Practice containerization using Docker
- Understand multi-container applications
- Prepare the application for cloud deployment on AWS
- Demonstrate basic cloud computing concepts such as scalability and service integration

## System Architecture

User Browser
     |
     
React Frontend
     |
     
Node.js / Express Backend API
     |
     
MySQL Database

Docker Compose is used to run all services together.

## Features
The application supports the following operations:

- Add new tasks
- View all tasks
- Update task status
- Delete tasks

Additional features:

- Persistent database storage
- Containerized environment
- Easy local setup
- Ready for AWS deployment

## Technologies Used

| Technology                     | Purpose                       |
| ------------------------------ | ----------------------------- |
| React                          | Frontend UI                   |
| Node.js                        | Backend runtime               |
| Express.js                     | REST API                      |
| MySQL                          | Database                      |
| Docker                         | Containerization              |
| Docker Compose                 | Multi-container orchestration |
| AWS EC2 *(planned deployment)* | Cloud hosting                 |

## Functional Requirements Coverage

| Requirement             | Status    |
| ----------------------- | --------- |
| User-facing interface   | Completed |
| Backend service         | Completed |
| Database integration    | Completed |
| CRUD operations         | Completed |
| Docker containerization | Completed |
| Multi-container setup   | Completed |
| Cloud-ready deployment  | Completed |

## Containerization

The project uses Docker to ensure the application runs consistently across environments.

Included files:

- Dockerfile
- compose.yaml

The containers include:

- Frontend/Backend application container
- MySQL database container

## AWS Services Used

| AWS Service     | Purpose                 |
| --------------- | ----------------------- |
| Amazon EC2      | Hosting the application |
| Security Groups | Allow public web access |

## Scalability & Reliability

The project follows basic cloud-native principles:

Scalability
- Docker containers make the application portable and scalable
- Services can be replicated in future deployments
Reliability
- Containerized services reduce environment-related issues
- Database persistence ensures task data is not lost
Maintainability
- Clean project structure
- Separated frontend and backend logic
- Dockerized setup simplifies deployment

## API Functionality

| Method | Function       |
| ------ | -------------- |
| GET    | Retrieve tasks |
| POST   | Create task    |
| PUT    | Update task    |
| DELETE | Remove task    |

## Project Structure

learn-docker-todo-app/
│

├── app/

│   ├── src/

│   └── package.json

│

├── mysql/

│

├── Dockerfile

├── compose.yaml

└── README.md

## Conclusion

This project demonstrates the fundamentals of cloud application development using Docker and AWS concepts.
It provides a simple but practical example of a full-stack containerized application with database integration and cloud deployment readiness.

*References

This repository is a sample application for users following the getting started guide at https://docs.docker.com/get-started/.

The application is based on the application from the getting started tutorial at https://github.com/docker/getting-started
