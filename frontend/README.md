

## Project setup
A simple and customizable Todo List application built with Node.js and Vue.js. This project provides a full-stack solution with both backend and frontend components, making it easy to manage and extend.

Project Structure:

The repository follows a simple structure:

```
.
├── Readme.md
├── backend
├── docker-compose.yml
└── frontend
```

backend: Contains the Node.js backend for the Todo List.
frontend: Contains the Vue.js frontend for the Todo List.
docker-compose.yml: Orchestrates the deployment of containers for the entire application.


## Getting Started

Prerequisites
Make sure you have the following software installed on your machine:

Docker
Git


### Installation
Clone the code repository
```
$ git clone git@github.com:Arziva/Todo_list.git
```
Navigate to the root directory.

```
$ cd NodeJs-Todo-List

```

## Usage

Starting the Application
To start the application, run the following command:

```
$ docker-compose up -d 
```

This command will launch the frontend, backend, and db containers in detached mode.

Accessing the App
Open your web browser and go to http://localhost:8080 to interact with the Todo List application.


## License

This project is licensed under the MIT License.

