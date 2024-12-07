# Admin Dashboard Project

This project is an **Admin Dashboard** built with **React**, **Recharts**, and **json-server** for backend data.

---

## **Technologies Used**
- **React**: Component-based UI development.
- **Recharts**: Interactive chart visualizations.
- **json-server**: Mock REST API for backend data.

---

## Screenshots

![Screenshot 1](public/s1.jpeg)
![Screenshot 2](public/s2.jpeg)
![Screenshot 2](public/s3.png)


## **Getting Started**

### **Prerequisites**
- Node.js (version 14 or higher) installed on your system.
- A package manager like npm or Yarn.

### **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/admin-dashboard.git
   ```
2. Navigate to the project directory:
   ```bash
   cd admin-dashboard
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

### **Run the Application**
1. Start the mock server with `json-server`:
   ```bash
   npx json-server --watch db.json --port 3001
   ```
2. Start the React application:
   ```bash
   npm start
   ```
3. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

---

## **API Endpoints**

### Endpoints Used:

#### User Endpoints
- `GET /users`: Fetch all users.
- `POST /users`: Add a new user.
- `PUT /users/:id`: Edit a user by ID.
- `DELETE /users/:id`: Delete a user by ID.

#### Role Endpoints
- `GET /roles`: Fetch all roles.
- `POST /roles`: Add a new role.
- `PUT /roles/:id`: Edit a role by ID.
- `DELETE /roles/:id`: Delete a role by ID.

---

## **Troubleshooting**

- Make sure you have the correct Node.js version installed.
- Check if the `json-server` is running on the correct port.
- Verify that the React application is running on the correct port.

---
