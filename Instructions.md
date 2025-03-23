# Popcorn Palace Movie Ticket Booking System
This document provides the instructions necessary to build, run and test the Popcorn Palace assignment.

## SETUP
1. Clone the repository to your local machine
2. DataBase setup: This assignment is configured by default to connect to a PostgreSQL database.
    Thus, you rather use yourlLocal PostgreSQL.


## PREREQUISITES
1. JDK
2. Apache Maven
3. PostgreSQL Database

## STRUCTURE
The project is organized as follows:
popcorn-palace/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── att/
│   │   │           └── tdp/
│   │   │               └── popcorn_palace/     # Application source code (controllers, models, repos, etc.)
│   │   └── resources/                          # Main configuration files (application.yaml, static files, etc.)
│   └── test/
│       ├── java/
│       │   └── com/
│       │       └── att/
│       │           └── tdp/
│       │               └── popcorn_palace/     # Unit and integration test classes
│       └── resources/                          # Test-specific resources (e.g., application-test.yaml)
├── docker-compose.yml                          # Docker configuration (if using PostgreSQL via Docker)
├── pom.xml                                      # Maven build configuration
└── Instructions.md                              # Setup and usage guide for the project


## BUILD
To build the project, go to the project root directory and run the following command:
* mvn clean install

## RUN
start the application using the following command:
* mvn spring-boot:run

## TEST
To run all tests simply use:
* mvn test
