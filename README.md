# Contract Management Platform (Frontend)

A frontend-based **Contract Management Platform** built using **React, TypeScript, and Vite**.  
This project demonstrates product thinking, UI design, state management, and clean frontend architecture for managing contract blueprints and contracts.

---

## 🚀 Objective

The goal of this project is to build a **frontend-only contract management system** that allows users to:

- Create reusable contract **Blueprints**
- Configure and position fields inside a blueprint
- Generate **Contracts** from blueprints
- Fill contract fields and track contract status

This project was developed as part of a **Full Stack / Frontend Engineering Assignment**.

---

## 🛠 Tech Stack

- **React** – UI development
- **TypeScript** – Type safety and scalability
- **Vite** – Fast development and build tool
- **CSS** – Styling
- **ESLint** – Code quality and linting

---

## 📂 Project Structure

```
contract-management-frontend/
├── src/
│ ├── components/ # Reusable UI components
│ ├── pages/ # Application pages
│ ├── types/ # TypeScript interfaces & types
│ ├── utils/ # Helper functions
│ ├── App.tsx # Root component
│ └── main.tsx # Entry point
├── public/
├── index.html
├── package.json
├── tsconfig.json
├── vite.config.ts
└── README.md
```


---

## ✨ Features Implemented

### 1. Blueprint Management
- Create a blueprint (contract template)
- Add configurable fields
- Supported field types:
  - Text
  - Date
  - Signature
  - Checkbox
- Store field metadata:
  - Field type
  - Label
  - Position (basic placement)

### 2. Contract Creation
- Select an existing blueprint
- Generate a contract from the blueprint
- Render all fields dynamically based on blueprint definition

### 3. Contract Filling
- Fill in contract fields
- Track contract status:
  - Draft
  - Completed (basic status handling)

### 4. State Management
- Local state management using React hooks
- Mocked/local persistence (no backend dependency)

---

## 🧪 Assumptions & Limitations

- This is a **frontend-only** implementation
- Data persistence is mocked / stored locally
- No authentication or user roles implemented
- Field positioning is basic (drag & drop not implemented)
- No backend API integration

---

## ⚙️ Setup Instructions

### Prerequisites
- Node.js (v18 or above recommended)
- npm or yarn

### Installation

```bash
git clone https://github.com/Tanishka-K03/contract-management-frontend.git
cd contract-management-frontend
npm install
