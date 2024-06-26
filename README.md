# Spring Boot REST Application

This project is a simple Spring Boot application that provides a RESTful web service. It accepts HTTP GET requests at `/greeting` and responds with a JSON representation of a greeting. You can customize the greeting message with an optional `name` parameter in the query string. The application will start on http://localhost:8080.

## Features

- Responds to HTTP GET requests at `/greeting`
- Returns a greeting message in JSON format
- Customizable greeting message using a `name` query parameter

## Prerequisites

- Java 11 or higher
- Maven

## Project Structure

├── src
│ └── main
│ └── java
│ └── com
│ └── example
│ └── demo
│ ├── GreetingController.java
│ └── DemoApplication.java
├── src
│ └── main
│ └── resources
│ └── application.properties
└── pom.xml

## Installation

### Clone the repository:

git clone https://github.com/yourusername/spring-boot-rest.git
cd spring-boot-rest

### Build the project:

mvn clean install

### Run the application:

mvn spring-boot:run

## In the screenshot below, you can see the main interface of Spring Initializr:

<img width="1265" alt="Screenshot 2024-05-21 at 15 41 38" src="https://github.com/koraykarsan/Spring-Framework/assets/108725475/02da60f4-5da7-4cc6-af2b-bd24d6b0b280">
