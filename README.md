#
This Project ProTasker is a task management app where users can register, log in, create projects, and manage tasks with statuses like "To Do", "In Progress", and "Done".

Setup: Clone the repo, install dependencies (npm install), add .env with MONGO_URI, JWT_SECRET, FRONTEND_URL, and start backend (npm run dev) and frontend (npm run dev).

API Endpoints:
POST /api/users/register → register a new user
POST /api/users/login → login user
GET /api/users → get all users (auth required)
GET /api/users/:id → get single user
GET /api/projects → get all projects
POST /api/projects → create project
PUT /api/projects/:id → update project
DELETE /api/projects/:id → delete project
GET /api/projects/:projectId/tasks → get tasks
POST /api/projects/:projectId/tasks → create task
PUT /api/projects/:projectId/tasks/:taskId → update task
DELETE /api/projects/:projectId/tasks/:taskId → delete task

Deployment: Frontend on Netlify, backend on Render.
https://finalproject-protasker-frontend.netlify.app/
https://finalproject-protasker-backend.onrender.com



## Dependencies

- Express
- MongoDB/Mongoose
- Dotenv
- Morgan
- Cors
- Helmet


## Dev Dependencies

- Nodemon