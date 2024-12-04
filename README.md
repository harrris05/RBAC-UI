# RBAC-UI

Role-Based Access Control (RBAC) UI
Project Overview
This project is a frontend implementation of a Role-Based Access Control (RBAC) system, designed to provide an intuitive and secure user interface (UI) for managing users, roles, and permissions in an admin dashboard. The goal is to create a UI where administrators can easily assign roles, modify permissions, and manage users in a secure and user-friendly environment.

The project is built using React and Bootstrap for styling, with a focus on responsiveness and ease of use. The app simulates a real-world RBAC system that includes CRUD operations for users and roles, role-based permissions, and dynamic permissions assignment.

Core Features
User Management

View and manage users (add, edit, delete).
Assign roles to users and manage their statuses (Active/Inactive).
Role Management

Define and edit roles with permissions (e.g., Read, Write, Delete).
Easily assign and modify permissions for each role.
Dynamic Permissions

Clear UI for managing permissions for each role.
Display of permissions in an intuitive format for easy modification.
Custom API Simulation

Mock API calls for CRUD operations on users and roles.
Simulated server responses to validate functionality.
Live Project
Frontend (UI): Role-Based Access Control (RBAC) UI - Live
Backend (API): Backend API - Live
Technologies Used
React for the frontend framework.
Bootstrap for responsive UI design.
Vite for development build and bundling.
Mock APIs for simulating server requests (optional).
Installation Instructions
Clone the repository:

git clone <repository-url>
Navigate to the project folder:

cd rbac-ui
Install the dependencies:

npm install
Run the development server:

npm run dev
Open your browser and visit http://localhost:5173/ to view the app.

Project Structure
rbac-ui/
│
├── src/
│   ├── components/          # UI components (Navbar, UserList, RoleList, etc.)
│   ├── pages/               # Different pages of the application (Dashboard, Login, etc.)
│   ├── services/            # Simulated API calls and data management
│   ├── App.js               # Main app component
│   ├── index.js             # Entry point
│   └── styles.css           # Custom styles
│
├── public/                  # Static assets (index.html, images, etc.)
│   ├── images/              # Images like logos, icons, etc.
│   └── favicon.ico          # Favicon for the app
│
├── package.json             # Project dependencies and scripts
├── vite.config.js           # Vite configuration
└── README.md                # Project documentation
Features
User Management
Add, edit, and delete users.
Assign roles and manage user status (Active/Inactive).
Role Management
Create, edit, and delete roles.
Roles can have permissions such as Read, Write, Delete, or custom permissions.
Dynamic Permission Assignment
Assign permissions to roles dynamically.
Modify permissions easily from the UI with a simple toggle.
Responsive Design
The app is fully responsive and adapts to various screen sizes, from mobile to desktop.
Security
Basic input validation is implemented to prevent invalid data.
Error handling in API calls to manage failed operations gracefully.
Bonus Features
Sorting, filtering, and searching capabilities for users and roles.
Customizable permissions for each role, ensuring flexibility in the RBAC model.
Usage
Managing Users:

Admins can add new users, edit existing users, and assign them specific roles (e.g., Admin, User, Guest).
Admins can also toggle user status between Active and Inactive.
Managing Roles:

Admins can create new roles and assign permissions (Read, Write, Delete).
Admins can edit roles and modify permissions based on the needs of their team.
Managing Permissions:



