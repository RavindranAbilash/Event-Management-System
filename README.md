# Event Management System Service

This repository contains a RESTful API built with Node.js, Express, and MongoDB for managing events. It supports CRUD operations to create, retrieve, update, and delete events. The application is Dockerized for easy deployment and includes a `docker-compose.yml` file to manage the application and MongoDB services.

## Features
- **Create**: Add new events to the database.
- **Retrieve**: Fetch details of all events or a specific event by ID.
- **Update**: Modify the details of an existing event.
- **Delete**: Remove an event from the database.

## How to Run
1. Clone the repository:
    ```sh
    git clone [https://github.com/your-username/event_management_system.git](https://github.com/RavindranAbilash/Event-Management-System.git)
    cd event_management_system
    ```
2. Build and run the Docker containers:
    ```sh
    docker-compose up --build
    ```
3. Access the API at `http://localhost:8080`.

## API Endpoints
- **GET /events**: Retrieve all events.
- **GET /events/:id**: Retrieve a specific event by ID.
- **POST /events**: Create a new event.
- **PUT /events/:id**: Update an existing event by ID.
- **DELETE /events/:id**: Delete an event by ID.

## Testing
You can test the API using Postman or curl commands to ensure all endpoints are functioning correctly.
