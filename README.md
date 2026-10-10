# FlowBoard — CodeAlpha Task 3 (Project Management Tool)

## Features
- Project board with To do, In progress and Done columns
- Create projects and tasks
- Assign a task owner and due date
- Change task status
- Task details and comments
- Delete tasks
- Demo registration/login
- JSON-file persistence; responsive UI

## Requirements
- Node.js 18 or later

## Run on Windows
1. Install Node.js from the official Node.js website.
2. Extract this folder, for example `C:\CodeAlpha\ProjectManagementTool`.
3. Open it in VS Code.
4. Open Terminal > New Terminal.
5. Run `npm install`
6. Run `npm start`
7. Open `http://localhost:3002`

## Important
This is a learning/demo project. Passwords are stored in plain text in a local JSON file, so use only fake demo credentials. Before production use, add password hashing, sessions/JWT, role-based access, CSRF protection, stronger validation and a proper database.
