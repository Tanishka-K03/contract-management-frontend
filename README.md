# Contract Management Platform (Frontend)

## Objective
Build a frontend-based Contract Management Platform from scratch to demonstrate
product thinking, UI design, state management, and clean code architecture.

No backend or UI designs were provided. The complete UI, data flow, and logic have
been designed and implemented independently.

---

## Tech Stack
- React
- TypeScript
- Vite
- CSS
- Local Storage (mocked persistence)

---

## Functional Requirements

### 1. Blueprint Creation
A Blueprint represents a reusable contract template.

Features:
- Create a blueprint with configurable fields
- Supported field types:
  - Text
  - Date
  - Checkbox
  - Signature
- Basic field positioning on a page
- Field metadata stored:
  - Type
  - Label
  - Position

Blueprint data is stored locally using mocked persistence.

---

### 2. Contract Creation from Blueprint
- Select an existing blueprint
- Generate a contract from the blueprint
- Contract inherits all blueprint fields
- Users can fill values for each field
- Blueprint structure remains immutable

---

### 3. Contract Lifecycle Management
Each contract follows a controlled lifecycle:


## Project Structure

contract-management-frontend/
│
├── public/
│ └── vite.svg
│
├── src/
│ ├── pages/
│ │ ├── BlueprintPage.tsx
│ │ ├── CreateContractPage.tsx
│ │ ├── ContractViewPage.tsx
│ │ └── DashboardPage.tsx
│ │
│ ├── services/
│ │ └── storage.ts
│ │
│ ├── types/
│ │ ├── blueprint.ts
│ │ └── contract.ts
│ │
│ ├── utils/
│ │ └── lifecycle.ts
│ │
│ ├── App.tsx
│ └── main.tsx
│
├── index.html
├── package.json
├── vite.config.ts
└── README.md


