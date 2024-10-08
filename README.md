# taskTicket

# Project Priority and Task Management Application

This is a full-stack web application built using the MERN stack (MongoDB, Express, React, Node.js). The application helps companies manage the priority of projects and tasks for users. It includes user authentication, dashboards for projects and tasks, search functionality, notifications, and profile management.

## Features

- **User Authentication**: Secure authentication with JWT tokens.
- **Dashboard**: Displays the user's projects and tasks, organized by priority.
- **Task Management**: Users can manage tasks with four priority levels.
- **Project Management**: Projects are assigned three priority levels.
- **Notifications**: Automatic notifications are sent when the priority of a project changes.
- **Search**: Users can search for other users, as well as their own projects and tasks.
- **Profile Management**: Users can view and edit their profiles.

## Technologies Used

### Front-End:
- **React.js**: For building the user interface.
- **Redux**: For state management.
- **React Router**: For handling navigation.
- **Axios**: For making HTTP requests to the API.

### Back-End:
- **Node.js**: For the server-side environment.
- **Express.js**: For building the RESTful API.
- **MongoDB**: For the database, using Mongoose as an ODM.
- **JWT (JSON Web Tokens)**: For user authentication and authorization.
  
## API Endpoints

### Authentication
- `POST /api/auth/register`: Register a new user.
- `POST /api/auth/login`: Login a user and get a JWT token.

### Projects
- `GET /api/projects`: Get all projects for the logged-in user.
- `POST /api/projects`: Create a new project.
- `PUT /api/projects/:id`: Update a project's priority.
- `DELETE /api/projects/:id`: Delete a project.

### Tasks
- `GET /api/tasks`: Get all tasks for the logged-in user.
- `POST /api/tasks`: Create a new task.
- `PUT /api/tasks/:id`: Update a task's priority or status.
- `DELETE /api/tasks/:id`: Delete a task.

### Users
- `GET /api/users`: Search for users.
- `GET /api/users/:id`: Get details for a specific user.
- `GET /api/profile`: Get the profile of the logged-in user.
- `PUT /api/profile`: Update the profile of the logged-in user.

### Notifications
- Notifications are sent via real-time updates when a project’s priority changes.

## How to Run the Project

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/priority-management-app.git
