# Lab 1: Building and Packaging Java Applications with Gradle

## Objective
Build, test, and package a Java application using Gradle, then run the generated JAR file to verify the application is working correctly.

## Prerequisites
- Java JDK 17
- Gradle 8.5
- Git

## Lab Steps
### 1. Clone the project:
   git clone https://github.com/Ibrahim-Adel15/build1.git
   cd build1

### 2. Run Unit Tests
   gradle test

### 3. Build the Application
   gradle build

### 4. Run the Application
   java -jar build/libs/ivolve-app.jar

### 6. Verify the Application is Working
   ```bash
   Hello Ivolve Trainee
