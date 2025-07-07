# Project Manager

A full-stack project management application built with the MERN stack (MongoDB, Express, React, Node.js) and GraphQL. Easily manage clients and projects with real-time status tracking and a modern, responsive interface.

## Features

- Manage individual and team projects
- Add, update, and delete clients and projects (full CRUD)
- Real-time project status tracking (Not Started, In Progress, Completed)
- Flexible GraphQL API for efficient data retrieval
- Responsive React frontend with Apollo Client for state management and caching
- Secure handling of sensitive data using environment variables

## Tech Stack

- **Frontend:** React, Apollo Client, Bootstrap
- **Backend:** Node.js, Express, GraphQL
- **Database:** MongoDB, Mongoose

## Getting Started

### Prerequisites

- Node.js and npm installed
- MongoDB installed and running

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/NayanBITMesra/ProjectManagerFinal.git
   cd ProjectManagerFinal
   ```

2. **Install server dependencies:**
   ```sh
   cd server
   npm install
   ```

3. **Install client dependencies:**
   ```sh
   cd ../client
   npm install
   ```

4. **Set up environment variables:**
   - Create a `.env` file in the `server` directory with your MongoDB URI and any other secrets.

5. **Start the backend server:**
   ```sh
   cd ../server
   npm start
   ```

6. **Start the frontend:**
   ```sh
   cd ../client
   npm start
   ```

7. **Open your browser and go to:**  
   `http://localhost:3000`

## Folder Structure

```
project-root/
│
├── client/      # React frontend
├── server/      # Node.js/Express/GraphQL backend
├── .gitignore
├── package.json
└── README.md
```



---
