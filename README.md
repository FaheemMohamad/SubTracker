


# 📬 SubTracker

A robust and modular backend API for managing user subscriptions with automated email reminders and advanced security features.

---

## ⚙️ Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose

---

## 🔋 Features

- **🔐 Authentication with JWT**  
  Secure user registration and login using JSON Web Tokens.

- **📦 Subscription Management**  
  Users can create and track their subscriptions with renewal dates and categories.

- **📧 Automated Email Reminders**  
  Sends reminders before subscription renewal using Upstash workflows.

- **🧠 Smart Data Modeling**  
  Well-structured MongoDB schemas with validations and relationships.

- **🛡️ Bot & Abuse Protection**  
  Arcjet integration for real-time bot detection and rate limiting.

- **💥 Centralized Error Handling**  
  Global error middleware to manage validation and server errors uniformly.

- **📝 Logging & Monitoring**  
  Console logs and structured responses for easier debugging.

- **🔁 Scalable Code Architecture**  
  Modular controller, routes, and middleware layers for easy extension.

---

## 🤸 Quick Start

Follow these steps to set up the project locally on your machine.

### ✅ Prerequisites

- Git
- Node.js
- npm

---

### 📦 Cloning the Repository

```bash
git clone https://github.com/FaheemMohamad/SubTracker.git
cd SubTracker
````

---

### 🛠️ Installation

```bash
npm install
```

---

### ⚙️ Set Up Environment Variables

Create a file named `.env.local` in the root directory and add:

```env
PORT=5500
SERVER_URL="http://localhost:5500"
NODE_ENV=development
DB_URI=
JWT_SECRET=
JWT_EXPIRES_IN="1d"
ARCJET_KEY=
ARCJET_ENV="development"
QSTASH_URL=http://127.0.0.1:8080
QSTASH_TOKEN=
EMAIL_PASSWORD=
```

---

### 🚀 Running the Project

```bash
npm run dev
```

Visit: [http://localhost:5500](http://localhost:5500)

---

### 📁 Project Structure

```
.
├── config/
├── controllers/
├── middlewares/
├── models/
├── routes/
├── utils/
├── workflows/
└── app.js
```

---


