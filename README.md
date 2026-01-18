# Project-Database-Management-System
This project is built using HTML, CSS, JavaScript for the frontend and Node.js with Express.js for the backend, connected to a MySQL database. It supports area-based service searching, user data insertion, and admin-controlled CRUD operations for emergency resources.


## Project Overview

This **Project - Database Management System** is a full-stack web application designed to provide instant, location-based access to essential emergency services in Chattogram, Bangladesh. Users can quickly find nearby ambulances, hospitals, blood banks, blood donors, police stations, fire services, and emergency shelters by selecting their area.

The platform includes:
- Public user interface for service discovery
- Registration forms for new ambulance services and blood donors
- Secure admin panel with full CRUD (Create, Read, Update, Delete) capabilities
- Real-time statistics dashboard for administrators

## ✨ Key Features

### User Features
- Area-based searching for all emergency services
- Detailed information display (contact, availability, type, hospital linkage, doctor specialty, etc.)
- Step-by-step filtering for police (District → City → Area) and fire services
- Easy registration for new ambulance services and blood donors

### Admin Features
- Secure username/password authentication
- Dashboard showing total counts of all services
- Full CRUD management for every service category
- Recent updates tracking
- Protected routes with session-based security

## 🛠️ Technology Stack

**Frontend**  
- HTML5 – Page structure and semantics  
- CSS3 – Custom responsive styling & layout  
- Vanilla JavaScript (ES6+) – Dynamic content, form handling & API calls  

**Backend**  
- Node.js – Server runtime  
- Express.js – RESTful API framework  

**Database**  
- MySQL – Relational database for structured emergency data  

**Tools & Libraries**  
- XAMPP – Local development environment (Apache + MySQL + phpMyAdmin)  
- CORS – Secure cross-origin API communication  
- JSON Middleware – Easy request/response handling  

## 📸 Screenshots

1. Homepage with area selection and service cards  
2. Ambulance listing with availability details  
3. Blood donor & blood bank results  
4. Admin dashboard overview  
5. Admin service management panel  
 

## 🚀 Quick Start (Local Setup)

### Prerequisites
- Node.js ≥ 16  
- MySQL / MariaDB (XAMPP recommended)  
- Git  

### Step-by-Step Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR-USERNAME/project-database-management-system.git
   cd project-database-management-system

Install dependenciesBashnpm install
Setup Database
Start XAMPP → Turn on Apache + MySQL
Create database: emergency_db
Import SQL dump: database/emergency_db.sql (or run provided SQL script)

Verify Database Connection (in server.js)JavaScriptconst db = mysql.createConnection({
  host: 'localhost',
  user: 'root',
  password: '',
  database: 'emergency_db'
});
Start the serverBashnpm startServer will run at: http://localhost:3000
Open in browser
Visit: http://localhost:3000/index.html
