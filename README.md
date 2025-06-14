# Flahti — Microservices Platform for Smart Agriculture

**Projet de Fin d’Année 2025 — 4th Year Computer Engineering PFA at EHEI Oujda**

---

## Overview

Flahti is an innovative, modular platform designed to address major challenges faced by Moroccan farmers in managing their agricultural operations intelligently using modern technologies.

Built with a **microservices architecture**, Flahti integrates multiple services focused on:

- Geolocated farm and land management
- Soil moisture monitoring with connected sensors
- Intelligent agricultural advice generation based on weather data, AI models, and plant needs
- Automated irrigation controlled by Arduino modules
- Integrated e-commerce for agricultural equipment with secure payments via Stripe

This project was developed by our team — Zakariae Bouanane, Oussama Elamrani, Mohamed Ayman Dziri, and Anass Aouissi — under the supervision of Mr. Mani Mohammed Adil, as part of our 4th-year PFA.

---

## Architecture & Technologies

### Microservices & Backend
- **.NET 8 (ASP.NET Core)** and **Symfony 7** for scalable service development
- **Entity Framework Core** and **Doctrine ORM** for data access
- **JWT with RSA encryption** for secure authentication
- Databases: **SQL Server**, **MariaDB**

### Frontend & Mobile
- **Angular 18** for web interface
- **Ionic Framework** for cross-platform mobile apps
- Languages & Styling: **TypeScript**, **SCSS**, **Bootstrap**

### APIs & External Services
- Weather and environment: **OpenMeteo**
- AI & Translation: **OpenAI**, **DeepL**
- Communication: **Twilio (SMS, voice)**, **Telegram Bot**
- Text-to-Speech: **Speechify**

### DevOps & Tooling
- Containerization: **Docker**, **Docker Compose**
- Version Control: **Git**, **GitHub**
- API testing: **Postman**
- Project Management & Modeling: **JIRA (SCRUM)**, **StarUML**

---

## Repository Structure

This main repository manages the overall project and includes each microservice as a **Git submodule**:

/Dashboard_service-Flahti
/Public_page_service-Flahti
/Advice_service-Flahti
/Users_Backend-Flahti
/Lands_service-Flahti
/Notification_service-Flahti
/Mobile-service_Flahti

Each microservice is versioned and developed independently to ensure modularity and scalability.

---

## Future Directions

Flahti aims to transform Moroccan agriculture by integrating:

- Image recognition for plant identification
- Disease detection from photos using AI
- Additional smart farming automation features

Our goal is to provide farmers with an **intelligent, scalable, and accessible platform** for sustainable, high-performance, and connected agriculture.

---

## Acknowledgments

Special thanks to our supervisors and mentors for their invaluable guidance.

---

*Feel free to explore each microservice folder for detailed documentation and source code.*

---

© 2025 — Flahti Team
