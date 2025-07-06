# Learning Management System (LMS)

A comprehensive web-based Learning Management System designed for universities, providing administration capabilities for staff, students, and study programs while serving as the university's official website.

## 🎯 Project Overview

This LMS application enables management of university personnel, students, and academic programs through a web interface that supports high concurrent user loads. The system serves multiple user types including students, teachers, administrative staff, administrators, and unregistered visitors.

## 🏗️ Architecture

- **Frontend**: Angular (TypeScript)
- **Backend**: Java Spring Boot
- **Architecture**: Web-based application with RESTful APIs

## 👥 User Roles & Capabilities

### Unregistered Users

- Browse university information (contact, location, rector details)
- View faculty pages and study programs
- Access course syllabi and materials
- User registration

### Students

- View current courses and announcements
- Access study history and grades
- Register for exams
- Track ECTS credits and GPA

### Teachers

- Manage course syllabi and schedules
- Create evaluation instruments (projects, tests, quizzes)
- Manage course announcements
- View student lists and search functionality
- Grade student exams (within 15-day window)

### Administrative Staff

- Student enrollment management
- Document and certificate issuance
- Schedule management for classes and exams
- Library management
- Inventory management

### Administrators

- User administration
- Study program management
- System configuration
- Staff management

## 🔧 Technical Features

- **Data Export**: XML and PDF export capabilities for student/teacher data
- **Bulk Import**: XML-based evaluation results import with validation
- **RDF Integration**: One entity stored as RDF triples with full CRUD operations
- **Search Functionality**: Advanced student search capabilities
- **Document Management**: PDF export for evaluation results

## 🚀 Getting Started

### Prerequisites

- Node.js (for Angular frontend)
- Java JDK 11+ (for Spring Boot backend)
- Maven (for dependency management)

### Frontend Setup (Angular)

```bash
cd frontend/lms-t7
npm install
ng serve
```

Access at: `http://localhost:4200`

### Backend Setup (Spring Boot)

```bash
cd backend/lms-t7
mvn clean install
mvn spring-boot:run
```

API available at: `http://localhost:8080`

## 📁 Project Structure

```
learning-management-system-tim7/
├── frontend/lms-t7/          # Angular application
│   ├── src/app/              # Angular components and services
│   └── package.json          # Frontend dependencies
└── backend/lms-t7/           # Spring Boot application
    ├── src/main/java/        # Java source code
    └── pom.xml               # Backend dependencies
```

## 🎓 Academic Requirements

This project fulfills university coursework requirements including:

- Multi-tier web application architecture
- Role-based access control
- Data persistence and management
- Document processing (XML/PDF)
- RDF/Semantic web integration
- Concurrent user support

## 📝 Development Status

🚧 **Currently in development** - This is an active university project implementing a full-featured Learning Management System.

---

_This project is part of academic coursework and implements industry-standard practices for educational technology systems._
