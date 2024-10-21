
# FormCustomersApp

This repository contains both the frontend and backend modules for a Customer Management (CRUD) Application. The application allows users to manage customer data using Angular for the frontend and Spring Boot for the backend, all orchestrated with Docker Compose.

## Cloning the Repository

To start working on this project, clone the repository using:

`git clone https://github.com/anderson-154/FormCustomersApp.git`

Once the repository is cloned, make sure both the frontend and backend modules are placed in the same root directory.

#### If they are not in the root directory you can fill them in the following way

`git clone https://github.com/anderson-154/backend-spring.git`

`git clone https://github.com/anderson-154/Frontend-Angular`

## Running the Project with Docker Compose
Once both the backend and frontend modules are in the same directory, you can use Docker Compose to run the entire project, including the MySQL database, backend, and frontend.

#### To build and run everything, use the following command:

`docker-compose up --build -d`
This will start:

* MySQL Database: Running at localhost:3306
* Spring Boot Backend: Running at http://localhost:8080/
* Angular Frontend: Running at http://localhost:4200/

## Stopping the Services
To stop all running services, use:

`docker-compose down`

This will stop and remove the running containers for the database, backend, and frontend.


> [!WARNING]
> If there is an error in the connection between the db and the backend, you can try to do it again:

`docker-compose up`
