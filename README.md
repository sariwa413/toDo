
# ToDo List - Fullstack Project              
https://todolist-kga5.onrender.com/
## Overview

The **ToDo List** project is a Fullstack application designed to manage tasks efficiently. It features a backend built with **.NET 8 Minimal API**, a frontend powered by **React.js**, and uses a **MySQL** database for data storage, enabling smooth task CRUD operations while prioritizing both simplicity and performance.

## Key Features

- **Task Management**: Add, view, modify, and delete tasks.
- **Database Integration**: Utilizes MySQL with Entity Framework Core for reliable data storage.
- **Minimal API**: A streamlined backend offering straightforward route management.
- **Client-Server Interaction**: React frontend communicates with the API through Axios.
- **API Documentation**: Swagger interface for API testing.
- **CORS Support**: Allows secure cross-origin requests.
- **Error Handling**: Efficient error logging with Axios interceptors.

## Technology Stack

### Backend
- **.NET 8 Minimal API**
- **Entity Framework Core** (with Pomelo for MySQL)
- **Swagger (Swashbuckle)**

### Frontend
- **React.js**
- **Axios**

### Database
- **MySQL** (Managed via MySQL Workbench)

## API Routes

- **GET** `/tasks` - Fetch all tasks
- **POST** `/tasks` - Create a new task
- **PUT** `/tasks/{id}` - Update an existing task
- **DELETE** `/tasks/{id}` - Remove a task

## Setup and Running the Project

### Prerequisites

- **MySQL** must be installed and running
- **Node.js** and **npm** must be installed
- **.NET 8 SDK** must be installed

### Backend Setup

1. Navigate to the `TodoApi` folder.
2. Update the `appsettings.json` file with your MySQL connection string.
3. Launch the backend:
   ```bash
   dotnet watch run

### Frontend Setup

1. Go to the `Client` directory.

2. Install required dependencies:
   npm install
3. Start the frontend:
   npm start

## Acknowledgments

A big thank you to the tools and libraries that made this project possible:

- **Microsoft .NET**
- **React.js**
- **Axios**
- **MySQL Workbench**
