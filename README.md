# Absentia Project

## Overview
**Absentia** is a web-based application that integrates a **MySQL database** with backend and frontend services. Follow the steps below to set up and run the project on your local machine.

---

## Prerequisites
Ensure the following tools are installed on your system:
- **Node.js** (with npm)
- **MySQL Server**
- **Git**
- **Web Browser** (e.g., Google Chrome, Mozilla Firefox)

---

## Installation Steps

### 1. Clone the Repository
Clone this repository to your local machine using:
```bash
git clone <YOUR_REPOSITORY_URL>
```

### 2. Import database
create a new database with "absentia_db" name then import the database with backup database file (absentia_db.sql)

### 3. Install Dependency
Install dependency for both frontend and backend project directory by open command line on each directory and type command:
```bash
npm install
```

### 4. Install Nodemon (Backend)
Install Nodemon for dev dependency:
```bash
npm install --save-dev nodemon
```

### 5. Run Both Project
Frontend:
```bash
npm run start
```
Backend:
```bash
nodemon index.js
```

### 6. Open the website
make sure the frontend run correctly. open your browser (highly recommend: chrome) and type this URL: http://localhost:4200.


---

**Note:** the Face Attendance only work on Mobile resolution (estricted to mobile).
