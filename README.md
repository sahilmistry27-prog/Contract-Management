# 📄 Contract Management Platform (Frontend Only)

A frontend-based **Contract Management Platform** built from scratch to demonstrate product thinking, UI design, controlled state management, and clean code architecture.

This project does **not** include a backend and uses mocked/local data as per assignment requirements.

---

## 🎯 Objective

To design and implement a frontend application that allows:
- Creating reusable contract blueprints
- Generating contracts from blueprints
- Managing contracts through a strict lifecycle
- Displaying contracts clearly using a dashboard

---

## ✨ Features

### 1️⃣ Blueprint Creation
- Create reusable contract templates (Blueprints)
- Supported field types:
  - Text
  - Date
  - Signature
  - Checkbox
- Basic field positioning on a visual canvas
- Field metadata stored:
  - Type
  - Label
  - Position
- Data stored locally (mock persistence)

---

### 2️⃣ Contract Creation from Blueprint
- Select an existing blueprint
- Generate a new contract from it
- Automatically inherit all blueprint fields
- Allow users to fill field values
- Initial status: **Created**

---

### 3️⃣ Contract Lifecycle Management

Each contract follows a **strict lifecycle**:

