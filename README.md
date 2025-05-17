# Taskify


## Overview

Taskify is a modern task management application designed to help individuals and teams organize, track, and complete their tasks efficiently. Built with React for the frontend and Node.js for the backend, Taskify provides a seamless user experience with intuitive interfaces and real-time updates.

## Features

- **User Authentication**: Secure login and registration system
- **Task Management**: Create, edit, delete, and prioritize tasks
- **Task Categories**: Organize tasks into custom categories
- **Due Dates & Reminders**: Set deadlines and receive timely notifications
- **Progress Tracking**: Monitor completion status with visual indicators
- **Team Collaboration**: Share tasks and collaborate with team members
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Dark/Light Mode**: Choose your preferred theme for comfortable viewing

## Technologies Used

### Frontend
- React.js
- Redux for state management
- Material UI components
- Axios for API communication
- React Router for navigation

### Backend
- Node.js
- Express.js framework
- MongoDB database
- JWT for authentication
- Socket.io for real-time updates

## Installation

### Prerequisites
- Node.js (v14.0.0 or higher)
- npm (v6.0.0 or higher)
- MongoDB (v4.0 or higher)

### Clone the Repository
```bash
git clone https://github.com/saurabh12nxf/taskify.git
cd taskify
```

### Backend Setup
```bash
cd backend
npm install
cp .env.example .env  # Create and configure your environment variables
npm run dev  # Start the development server
```

### Frontend Setup
```bash
cd frontend
npm install
cp .env.example .env  # Create and configure your environment variables
npm start  # Start the React development server
```

## Configuration

Create `.env` files in both the frontend and backend directories based on the provided examples:

### Backend `.env` Example
```
PORT=5000
MONGODB_URI=mongodb://localhost:27017/taskify
JWT_SECRET=your_jwt_secret_key
NODE_ENV=development
```

### Frontend `.env` Example
```
REACT_APP_API_URL=http://localhost:5000/api
REACT_APP_SOCKET_URL=http://localhost:5000
```

## API Documentation

The API documentation is available at `/api/docs` when running the backend server. It provides detailed information about all available endpoints, required parameters, and response formats.

### Key Endpoints

- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Authenticate a user
- `GET /api/tasks` - Get all tasks for the authenticated user
- `POST /api/tasks` - Create a new task
- `PUT /api/tasks/:id` - Update an existing task
- `DELETE /api/tasks/:id` - Delete a task

## Project Structure

```
taskify/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── app.js
│   └── server.js
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── contexts/
│   │   ├── hooks/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── store/
│   │   ├── utils/
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
└── README.md
```

## Contributing

We welcome contributions to Taskify! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

Please make sure to update tests as appropriate and adhere to the existing coding style.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Saurabh - [@saurabh12nxf](https://github.com/saurabh12nxf)

Project Link: [https://github.com/saurabh12nxf/taskify](https://github.com/saurabh12nxf/taskify)

## Acknowledgments

- [React Documentation](https://reactjs.org/docs/getting-started.html)
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- All our contributors and supporters
