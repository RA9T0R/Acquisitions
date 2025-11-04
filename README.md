# 🚀 Acquisitions API

A scalable and production-ready API built using **Node.js** and **Express.js**.

## ⚙️ Tech Stack

This project is built using a modern JavaScript backend stack:

| Component | Description |
| :--- | :--- |
| **Node.js** | JavaScript runtime environment for the server. |
| **Express.js** | Fast, minimalist web framework for building APIs. |
| **Jest** | Framework for unit and integration testing. |
| **Supertest** | Library for testing HTTP endpoints/APIs. |

## 🎓 Training & Acknowledgement

This repository serves primarily as a **training exercise** and **learning resource** based on the "Acquisitions API" tutorial from [JavaScript Mastery](https://youtu.be/H5FAxTBuNM8?si=RZG7smxyEekuN2o3).

The core code architecture and initial logic are derived from this educational project. This repository is used by me to practice and deepen my skills in **Node.js, Express.js, Jest, and API development**.

## 🤸 Quick Start

Follow these steps to set up and run the project locally.

### Prerequisites

Make sure you have the following installed:

* **[Git](https://git-scm.com/)**
* **[Node.js](https://nodejs.org/en)**
* **npm** (Node Package Manager)

### 1. Cloning the Repository

Open your terminal and run:

```bash
git clone [https://github.com/RA9T0R/Acquisitions.git](https://github.com/RA9T0R/Acquisitions.git)
cd Acquisitions
```

### 2. Installation

Install all the necessary dependencies:

```bash
npm install
```

### 3. Environment Variables

Create a file named .env in the root directory and add your configuration details:

```env
# Server Configuration
PORT=3000
NODE_ENV=development

# Database Configuration (Update this with your actual DB connection string)
DATABASE_URL=

# Arcjet Configuration
ARCJET_API_KEY=
```

### 4. Running the Project

To start the server in development mode:

```bash
npm run dev
```

The application will be running at http://localhost:3000.

### ✅ Running Tests

To execute the unit and integration tests using Jest and Supertest:

```bash
npm run test
```

___