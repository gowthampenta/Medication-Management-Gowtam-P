# 💊 Medication Management System

A full-stack web application designed for patients and caretakers to track and manage medications effectively. The system supports role-based dashboards, medication tracking, and authentication with persistent data storage using SQLite.

---

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Folder Structure](#folder-structure)
- [Testing](#testing)
- [Contributing](#contributing)
- [Author](#author)

---

## 📖 Project Overview

This project was developed as part of a technical assignment. It provides an intuitive interface for patients and caretakers to manage medication schedules, mark doses as taken, and track adherence.

### 👥 Target Users

- **Patients**: Track their medications, schedules, and adherence.
- **Caretakers**: Manage multiple patients and their medication progress.

---

## ✅ Features

### 🔐 Authentication

- Signup/Login using SQLite
- Role-based access for patients and caretakers

### 💊 Medication Management

- Add medications with name, dosage, and frequency
- Mark medication as taken
- View all medications
- Display adherence percentage

### 📊 Dashboards

- Dynamic dashboard for either **Patient** or **Caretaker**
- Real-time display of medication info connected to the backend

### 🧪 Form Validation & UX

- Validations for all forms (login, signup, add medication)
- Loading and error states during API interactions

---

## 🛠 Technology Stack

### Frontend

- React (Vite + JSX)
- React Query
- Tailwind CSS
- ShadCN UI

### Backend

- Node.js
- Express.js
- SQLite (using `sqlite3` package)

### Testing

- Vitest (unit/component testing)

---

## 🚀 Getting Started

### Prerequisites

- Node.js & npm (Install using [nvm](https://github.com/nvm-sh/nvm#installing-and-updating))

### Setup Instructions

#### 1. Clone the Repository

```bash
git clone <YOUR_GIT_URL>
cd medication-management-system
