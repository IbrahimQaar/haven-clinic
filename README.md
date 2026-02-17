# 🏥 Haven Clinic

**Status:** Under Active Development

Haven Clinic is a full-stack healthcare web application that models patient-facing workflows commonly found in modern clinical systems. The platform provides structured access to medical services, provider directories, clinic locations, authentication, and patient resources through a clear, production-oriented interface. The system emphasizes accessibility, predictable navigation, and modular full-stack architecture aligned with real-world healthcare application standards.

---

## Screenshots

<img width="1509" height="857" alt="Screenshot 2026-02-17 at 1 50 16 AM" src="https://github.com/user-attachments/assets/9f6dda97-2d27-4ce7-94c8-c559f7e4c2d2" />
<img width="1510" height="860" alt="Screenshot 2026-02-17 at 1 50 02 AM" src="https://github.com/user-attachments/assets/d1c404a7-52d5-45ca-8538-5779019a1a10" />
<img width="1512" height="862" alt="Screenshot 2026-02-17 at 1 49 54 AM" src="https://github.com/user-attachments/assets/d327a555-a90d-4fc2-83c4-5787018ea505" />
<img width="1510" height="861" alt="Screenshot 2026-02-17 at 1 49 46 AM" src="https://github.com/user-attachments/assets/8a89c66e-46dc-408d-ba94-50a4a256ee7e" />
<img width="1511" height="860" alt="Screenshot 2026-02-17 at 1 47 54 AM" src="https://github.com/user-attachments/assets/dffea6bc-a11a-4d88-9bc6-fb872f2cdec1" />
<img width="1511" height="857" alt="Screenshot 2026-02-17 at 1 37 00 AM" src="https://github.com/user-attachments/assets/117616e5-4500-4716-a535-ce70540a0eb8" />

---

## ✨ Key Features

* **Service Discovery**
  Browse available healthcare services including primary care, urgent care, and virtual visits.

* **Provider Directory**
  View detailed provider profiles including specialty, clinic location, and contact information.

* **Clinic Locations**
  Access structured location data including addresses, phone numbers, and directions.

* **Patient Resources**
  Centralized educational materials, visit preparation guidance, billing information, and patient rights documentation.

* **Authentication System**
  Secure user registration and login flows with structured form validation.

* **Responsive Interface**
  Optimized layouts for desktop, tablet, and mobile devices.

---

## Application Structure

| Page              | Purpose                                                          |
| ----------------- | ---------------------------------------------------------------- |
| Home              | Overview of services, trust messaging, and insurance information |
| About             | Clinic mission, values, and patient-centered philosophy          |
| Services          | Browse healthcare services and provider details                  |
| Locations         | View clinic locations and contact information                    |
| Patient Resources | Educational and administrative patient support materials         |
| Login / Register  | Secure authentication and onboarding                             |

---

## Tech Stack

| Category | Technology                     | Responsibility                        |
| -------- | ------------------------------ | ------------------------------------- |
| Frontend | React, HTML5, CSS3, JavaScript | UI rendering and client-side behavior |
| Backend  | Java, Spring Boot              | REST API, routing, and business logic |
| Database | PostgreSQL                     | Relational data persistence           |
| Tooling  | Git & GitHub                   | Version control                       |

---

## Architecture

Haven Clinic follows a layered full-stack architecture:

* React frontend consuming RESTful APIs
* Spring Boot backend handling validation and business rules
* PostgreSQL for structured relational data storage
* Clear separation between presentation, service, and data layers

The application is designed for maintainability, modularity, and future scalability.

---

## Getting Started

### Prerequisites

* Node.js
* Java 17
* PostgreSQL

---

### Frontend

```bash
cd frontend
npm install
npm start
```

---

### Backend

```bash
cd backend
./mvnw spring-boot:run
```

Configure PostgreSQL credentials in `application.properties` before starting the backend.

---

## 👨‍💻 Author

**Ibrahim Qaar**
Full-Stack Java & React Developer
