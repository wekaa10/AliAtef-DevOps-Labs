# Lab 3: Run Java Spring Boot App in a Docker Container

## Objective
Run a Java Spring Boot application inside a Docker container.

## Prerequisites
- Docker installed and running
- Java JDK 17
- Maven
- Git

## Lab Steps

### 1. Clone the Spring Boot Application
git clone https://github.com/Ibrahim-Adel15/Docker-1.git .

### 2. Write Dockerfile

### 3. Build Docker Image
docker build -t app1 .

### 4. Run Container from the Image
docker run -d -p 8080:8080 --name container1 app1

### 5. Test the Application
```bash
curl http://localhost:8080
 
