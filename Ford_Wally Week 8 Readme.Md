# Employee Management System (MERN Stack)

## Overview

This is a full-stack Employee Management application built using the MERN stack:

* **MongoDB** – Database
* **Express.js** – Backend framework
* **React** – Frontend library
* **Node.js** – JavaScript runtime

The application supports full CRUD functionality, allowing users to create, read, update, and delete employee records.

## Prerequisites

Before running the project, make sure you have the following installed:

* Node.js
* npm
* MongoDB (local installation or MongoDB Atlas)

## Install Dependencies

### Backend

Open a terminal and navigate to the backend folder:

```bash
cd backend
npm install
```

### Frontend

Open another terminal and navigate to the frontend folder:

```bash
cd frontend
npm install
```

## Configure Environment Variables

Inside the **backend** folder, create a `.env` file containing:

```env
MONGO_URI=mongodb://127.0.0.1:27017/employeesDB
PORT=5000
```

Update the `MONGO_URI` if you are using MongoDB Atlas.

## Run the Application

### Start the Backend Server

```bash
cd backend
npm run dev
```

The backend API will run at:

```
http://localhost:5000
```

### Start the Frontend Server

Open a new terminal and run:

```bash
cd frontend
npm run dev
```

The React application will be available at:

```
http://localhost:5173
```

## Features

* Add new employees
* View all employees
* View employee details
* Edit employee information
* Delete employee records
* RESTful API using Express.js and MongoDB
* React frontend connected with Axios
