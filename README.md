# Employee Data Management Project

A Full-stack Employee Data Management System built with Spring Boot + SQLite (backend) and React.js (frontend).  
The application allows managing employee records with basic CRUD operations.

---

##  Tech Stack

**Backend:**  
- Java 17+  
- Spring Boot  
- Spring Data JPA  
- SQLite Database  

**Frontend:**  
- React.js  
- Axios (for API calls)  
- HTML, CSS  

---

## Project Structure

### Backend (`employee-management/`)

<img width="561" height="776" alt="Screenshot 2025-10-02 004623" src="https://github.com/user-attachments/assets/336f8a86-5bc8-4b3e-8a33-9e9dc4bd8e35" />


---

### Frontend (`ems-frontend/`)

<img width="435" height="636" alt="image" src="https://github.com/user-attachments/assets/e92956bb-0170-476c-b505-bc3fab16840b" />


---

##  Setup & Run

### Backend (Spring Boot + SQLite)

1. Navigate to the backend folder:
   
   ```bash
   cd employee-management

2. Build and run the Spring Boot app:
   
   ./mvnw spring-boot:run

3. The server will start at: 
   
   http://localhost:8080

### Frontend (React.js)

1. Navigate to the frontend folder:
   
   cd ems-frontend

2. Install dependencies:
   
   npm install


3. Run the development server:
   
   npm start

   Open in browser:
   
   http://localhost:3000

### API Endpoints

  - GET /api/employees → Get all employees

  - GET /api/employees/{id} → Get employee by ID

  - POST /api/employees → Create new employee

  - PUT /api/employees/{id} → Update employee

  - DELETE /api/employees/{id} → Delete employee

### Screenshots
  
  # Employee Dashboard
   <img width="1579" height="622" alt="image" src="https://github.com/user-attachments/assets/1dec760d-6e09-43e7-a0ee-197e5a70cfd5" />

  # Add Employee
   <img width="1535" height="716" alt="image" src="https://github.com/user-attachments/assets/28392513-3f81-4da9-bec4-9aa401179817" />
    

 # Update Employee
   <img width="1643" height="753" alt="image" src="https://github.com/user-attachments/assets/bf32825c-fa75-424f-89cc-73c46dc4fa9e" />

 # Exception handling
   <img width="1567" height="820" alt="image" src="https://github.com/user-attachments/assets/66749785-af74-47df-a8b4-a0561e8c9bb1" />

# Delete Employee
   <img width="1492" height="492" alt="image" src="https://github.com/user-attachments/assets/c763dfa6-a9f9-4b99-b0cd-4c7eae41fa43" />

### Features

  - Add, update, delete, and view employees

  - React frontend with dynamic rendering

 -  RESTful API backend using Spring Boot

 - SQLite database for lightweight persistence

 - Global exception handling



