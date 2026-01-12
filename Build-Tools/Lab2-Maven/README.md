# Lab 2: Building and Packaging Java Applications with Maven

## Objective
Build, test, and package a Java application using Maven, then run the generated JAR file to verify the application is working correctly.

## Prerequisites
- Java JDK 17
- Maven
- Git

## Lab Steps

1. Clone the project:
```bash
git clone https://github.com/Ibrahim-Adel15/build2.git
cd build2

2. Run Unit tests:
mvn test

3. Build the application:
mvn package

4. Run the application:
java -jar target/hello-ivolve-1.0-SNAPSHOT.jar

5. Verify the application is working
Hello Ivolve Trainee
