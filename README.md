# Task Manager Application

## Overview
The Task Manager application is a Spring Boot-based application that allows users to manage tasks efficiently. It provides functionalities to create, read, update, and delete tasks, along with tracking their execution details.

## Features
- Create, retrieve, update, and delete tasks.
- Manage task execution details.
- Simple RESTful API for task management.

## Technologies Used
- Java
- Spring Boot
- Maven
- JPA (Java Persistence API)
- Logback for logging

## Project Structure
```
task-manager
├── pom.xml
├── src
│   └── main
│       ├── java
│       │   └── com
│       │       └── example
│       │           └── taskmanager
│       │               ├── TaskManagerApplication.java
│       │               ├── controller
│       │               │   └── TaskController.java
│       │               ├── service
│       │               │   └── TaskService.java
│       │               ├── model
│       │               │   ├── Task.java
│       │               │   └── TaskExecution.java
│       │               └── repository
│       │                   └── TaskRepository.java
│       └── resources
│           ├── application.properties
│           └── logback.xml
└── README.md
```

## Setup Instructions
1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd task-manager
   ```
3. Build the project using Maven:
   ```
   mvn clean install
   ```
4. Run the application:
   ```
   mvn spring-boot:run
   ```

   
<img width="1206" height="342" alt="Screenshot 2025-10-20 011011" src="https://github.com/user-attachments/assets/596553d0-1ed0-4fcb-acea-ea19a86f84bd" />


-------------------------------------------------------------------------------------------------------------------------------------------------------------

<img width="1060" height="381" alt="Screenshot 2025-10-20 011058" src="https://github.com/user-attachments/assets/dac6e437-8a19-418a-b18a-84f1fb89757a" />



-------------------------------------------------------------------------------------------------------------------------------------------------------------


<img width="907" height="318" alt="Screenshot 2025-10-20 011309" src="https://github.com/user-attachments/assets/a4acccfd-8eb9-4f0f-b05b-658c701063f6" />


## Usage
- The application exposes a RESTful API for managing tasks.
- Use tools like Postman or curl to interact with the API endpoints.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License
This project is licensed under the MIT License.
