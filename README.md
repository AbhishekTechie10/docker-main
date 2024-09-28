# To-Do List React App

## Overview
This is a simple To-Do List application built using React and containerized using Docker. The app allows users to add, remove, and manage their tasks efficiently.

## Features
- Add new tasks
- Remove completed tasks
- Mark tasks as completed
- User-friendly interface

## Technologies Used
- React
- Docker
- JavaScript
- CSS (with Bootstrap for styling)

## Getting Started

### Docker architecture
![image](https://github.com/user-attachments/assets/5aceef3a-4b79-4450-920e-2a293872fd40)
Docker Architecture
Docker Client: Interface for users to manage containers and images.
Docker Daemon: Manages containers and communicates with the client.
Docker Registry: Stores Docker images (e.g., Docker Hub).
Docker Images: Read-only templates used to create containers.
Docker Containers: Lightweight, isolated instances of images.
Docker Volumes: Persistent storage for container data.
Docker Networks: Enable communication between containers.
Docker Compose: Manages multi-container applications using a YAML file.


### Prerequisites
Make sure you have the following installed on your machine:
- [Docker](https://www.docker.com/get-started) 
- [Node.js](https://nodejs.org/) (for local development, if needed)

### Steps to Run the Application

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/todo-list-app.git
   cd todo-list-app
   
2. **Build the Docker Image Ensure you are in the project directory and run:**
docker build -t todo-list-app .

3. **Run the Docker Container**
   docker run -p 3000:3000 todo-list-app

#### Screenshots
![Screenshot (826)](https://github.com/user-attachments/assets/d132963f-f89c-4569-8a86-1632215a7b00)



