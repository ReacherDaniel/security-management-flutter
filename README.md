# Security Management App – Flutter & Firebase

This project is a **cross-platform mobile application** developed using **Flutter** and **Firebase**, designed for **security personnel management** with **role-based access control (RBAC)** and **real-time incident reporting**.

The application manages a hierarchical security structure while providing emergency alert features for residents or tenants.

---

## Project Overview

The system allows organizations or residential communities to manage security staff and residents through a secure mobile application.

It supports a **hierarchical role structure**:

- **Admin** – Full system access and configuration
- **Sheriff** – Supervisory and management permissions
- **Guard** – Operational security access
- **Resident / Tenant** – Incident reporting and communication

Each role has specific permissions enforced by the system to guarantee secure and controlled operations.

---

## Core Features

- Role-Based Access Control (RBAC)
- Hierarchical user management
- Full CRUD operations for security personnel
- Authentication and authorization
- Secure data storage with Firebase rules
- Cross-platform support (Android & iOS)

---

## Emergency & Community Features

The application includes **real-time safety and communication tools** designed for emergency situations:

- **Emergency alert by device motion**
  - Residents can trigger an alert by **shaking the mobile device**
- **Real-time location sharing**
  - The user's **GPS location is sent automatically** to the assigned guard
- **Incident reporting**
  - Reports for assaults, suspicious activity, or emergencies
- **Complaints and requests**
  - Residents can submit complaints or non-emergency reports
- **Community notifications**
  - Guards can send **announcements and alerts** to all residents in the community

These features enable rapid response and improved communication between residents and security staff.

---

## 🏗️ Architecture Overview

```text
Flutter Mobile App
        ↓
Firebase Authentication
        ↓
Firebase Firestore
        ↓
Firebase Cloud Functions (optional)

🧩 Application Modules

User authentication and role validation

Role-based UI rendering

Security personnel management (CRUD)

Emergency alert system (shake detection)

GPS location tracking and sharing

Incident and complaint reporting

Community announcements and notifications

🚀 Technologies Used
Frontend

Flutter

Dart

Material UI

Device sensors (accelerometer)

GPS / Location services

Backend & Services

Firebase Authentication

Firebase Firestore

Firebase Security Rules

Firebase Cloud Messaging (notifications)

🔐 Security Model

The application implements RBAC (Role-Based Access Control) to ensure that:

Users can only perform actions permitted by their role

Sensitive operations are restricted to authorized roles

Emergency alerts and location data are securely handled

Data access is validated both at UI and backend levels

🎯 Purpose of the Project

Practice secure mobile application development

Implement real-time emergency systems

Apply RBAC and hierarchical authorization

Develop scalable and maintainable Flutter applications

Strengthen skills in Firebase-based architectures
