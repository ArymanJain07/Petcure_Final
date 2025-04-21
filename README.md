
# PetCure – Full Stack Web Application (Frontend & Backend)

## Overview
PetCure is a full-stack web application designed to connect pet owners with veterinarians for appointment booking and pet care services. It allows users to search for nearby veterinarians, book appointments, and access pet care resources. The app includes an admin panel for veterinarians to manage their schedules and appointments.

## Features
### User Features:
- User authentication (login, registration)
- Search and book appointments with veterinarians
- Access pet care resources
- Manage appointments

### Veterinarian Features:
- Admin panel to manage appointments and schedules
- Update pet care resources

## Technologies Used:
- **Frontend**: React.js, Bootstrap, Axios
- **Backend**: Spring Boot, Hibernate, Spring Security
- **Database**: MySQL
- **Authentication**: JWT

## Setup Instructions:
### Clone the repository:
```bash
git clone https://github.com/ArymanJain07/Petcure_Final.git
```

### Backend Setup:
1. **Navigate to the backend directory**:
   ```bash
   cd backend
   ```
2. **Install dependencies** using Maven:
   ```bash
   mvn install
   ```
3. **Set up the MySQL database**:
   - Create a MySQL database and configure the connection details in `src/main/resources/application.properties`.
   - Example SQL for database creation:
     ```sql
     CREATE DATABASE petcure_db;
     ```
   - Ensure that the `application.properties` file is updated with correct MySQL database credentials.
   
4. **Run the Spring Boot application**:
   ```bash
   mvn spring-boot:run
   ```

### Frontend Setup:
1. **Navigate to the frontend directory**:
   ```bash
   cd frontend
   ```
2. **Install dependencies**:
   ```bash
   npm install
   ```
3. **Run the React application**:
   ```bash
   npm start
   ```

### Database Configuration:
- Make sure MySQL is installed and running. The application connects to `petcure_db`. Update the database credentials in `src/main/resources/application.properties`.

## How to Contribute:
1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Feature added"
   ```
4. Push to your fork:
   ```bash
   git push origin feature-name
   ```


