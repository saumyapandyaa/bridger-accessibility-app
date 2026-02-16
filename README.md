# Bridger

Accessibility-focused navigation and social networking platform designed to empower individuals with disabilities.

Bridger combines venue accessibility data, geolocation services, and community networking into a unified platform built with accessibility-first design principles.

---

##  Problem Statement

Mainstream navigation and venue platforms rarely prioritize accessibility data. Individuals with mobility or visual impairments often lack reliable information about accessible locations.

Bridger addresses this gap by providing:

- Accessibility-aware venue discovery
- User-submitted accessibility ratings
- Community networking
- Incentive-based engagement system
- AODA-compliant UI design

---

##  System Architecture

Three-tier architecture:

Frontend (React) → Backend (Node.js + Express REST API) → MySQL Database (via Sequelize ORM)

The system cleanly separates presentation, business logic, and persistence layers.

---

##  Tech Stack

Frontend:
- React
- Accessible UI design (high contrast, clear layout)

Backend:
- Node.js
- Express.js
- Sequelize ORM
- bcrypt (secure password hashing)
- JWT authentication

Database:
- MySQL

External Integration:
- IP Geolocation API (ip-api.com)

---

##  Core Features

### Authentication & Security
- Secure password hashing (bcrypt)
- JWT-based session authentication
- Role-based admin capabilities

### Accessibility-Aware Venue Discovery
- Search and rate venues based on accessibility
- Submit new venue entries
- Admin moderation and approval system

### Social Networking
- Friend requests
- Location sharing
- Community-driven discovery

### Rewards System
- Points earned for contributions
- Incentivized accessibility feedback

---

##  Security Considerations

- Passwords hashed using bcrypt
- JWT tokens used for stateless authentication
- Protected API routes with middleware validation
- Input validation and ORM-level query abstraction

---

##  Running Locally

Clone repository:
```
git clone https://github.com/Yaraqm/Bridger.git  
cd Bridger  
```
Backend setup:
```
cd server  
npm install  
npm start  
```
Frontend setup:
```
cd client  
npm install  
npm start  
```
Application runs at: http://localhost:3000

---

##  What This Project Demonstrates

- Full-stack application development
- Three-tier system design
- Secure authentication patterns
- Database modeling with relational schema
- REST API design
- Accessibility-first UI principles
- Community-driven platform logic

---

##  Future Enhancements

- Mobile-native application
- Real-time GPS navigation
- Voice accessibility (speech-to-text / text-to-speech)
- Advanced analytics dashboard
- Cloud deployment with containerization
- Role-based access refinement
