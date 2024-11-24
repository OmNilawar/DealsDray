# DealsDray - Employee Management System

*DealsDray* is an employee management system built using **React.js**, **Node.js**, **Express**, and **MongoDB**. The system provides a simple, efficient way to manage employee data, with features like viewing, editing, deleting, and sorting employee details.

## Features

- *Employee Management*: Add, view, edit, and delete employee records.
- *Sorting*: Sort employees by name, email, ID, or date.
- *Responsive Design*: Fully responsive user interface for use on both desktop and mobile devices.
- *Authentication*: Secure login system with role-based access (Admin).
- *Editable Fields*: Admin users can edit employee details, including Name, Email, Mobile, Designation, Gender, and Course.
- *Role Management*: Admin can manage employee roles.

## Technologies Used

- *Frontend*:
  - React.js
  - React Router
  - Tailwind CSS
  - Axios for API requests

- *Backend*:
  - Node.js
  - Express.js
  - MongoDB
  - Mongoose for database interaction

- *Authentication*:
  - JWT (JSON Web Tokens)

## Prerequisites

Before you begin, ensure you have met the following requirements:

- *Node.js* and *npm* installed. [Download Node.js](https://nodejs.org/)
- Git for version control.

## Installation

### Clone the repository

```bash
git clone https://github.com/OmNilawar/DealsDray.git
cd DealsDray
```

### Backend Setup

```bash
cd backend
npm install
```

### Start Backend Server

```bash
npm run dev
```

### Frontend Setup

```bash
cd frontend
npm install
```

### Start Frontend 

```bash
npm run dev
```


## API Endpoints

### Authentication
- `POST /api/auth/login` - Authenticates the admin and generates a JWT token.

### Admin Login Credentials

Use the following credentials to log in as an admin:

- **Email**: dummyadmin@gmail.com
- **Password**: admin@123

### Employee Operations
- `GET /api/employee/fetch` - Fetch all employee records.
- `POST /api/employee/add` - Add a new employee.
- `PUT /api/employee/edit/:id` - Edit an existing employee by ID.
- `DELETE /api/employee/delete/:id` - Delete an employee by ID.

## Screenshots

Here are some screenshots of the app in action:

- [LoginPage](https://ibb.co/p4LKNDd)
- [AdminPage](https://ibb.co/3CkWGqL)

## Contact

For any questions or issues, please reach out to me at:

- Email: omkarnilawar9@gmail.com
