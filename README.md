## 🎯 Problem Statement

Many eligible citizens miss government welfare schemes due to:

* Lack of awareness
* Unverified or outdated information
* No centralized platform for scheme discovery

**SmartGov** addresses this gap by providing a **verified, transparent, and user-friendly portal** to access government schemes based on eligibility.

---

## 👥 User Roles & Workflow

### 👤 User

* Register and login securely
* Maintain personal profile
* View **eligible government schemes**
* Access official scheme links

### 📝 Maker

* Government department employee (e.g., Bank / Office staff)
* Submits new government schemes
* Provides scheme details and reference links
* Cannot publish directly (approval required)

### ✅ Checker

* Senior official from the same department
* Independently verifies schemes submitted by makers
* Defines eligibility criteria (age, income, caste, etc.)
* Approves schemes for public access

### 🛡️ Admin

* Verifies and approves **Maker & Checker registrations**
* Maintains role authenticity
* Ensures platform security and trust

> 🔐 This **Maker–Checker model** ensures transparency and prevents misuse or false scheme information.

---

## 🚀 Key Features

* Role-Based Access Control (RBAC)
* JWT Authentication & Authorization
* Secure user profile management
* Scheme submission & verification workflow
* Eligibility-based scheme filtering
* Real-time backend integration
* Responsive and user-friendly UI

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Axios
* CSS (custom styling)

### Backend

* Node.js
* Express.js
* JWT Authentication

### Database

* MongoDB

---

## ▶️ How to Run the Project (Local Setup)

### 🔹 Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/SmartGov-Scheme-Finder.git
cd SmartGov-Scheme-Finder
```

---

### 🔹 Step 2: Install Dependencies

#### Backend

```bash
cd backend
npm install
```

#### Frontend

```bash
cd frontend
npm install
```

---

### 🔹 Step 3: Configure Environment Variables

Create a `.env` file in the backend with:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

### 🔹 Step 4: Start the Backend Server

```bash
npm start
```

Backend runs on:

```
http://localhost:5000
```

---

### 🔹 Step 5: Start the Frontend Server

```bash
npm start
```

Frontend runs on:

```
http://localhost:3000
```

---

## 🔐 Admin Login Credentials (Demo)

```text
Email: admin123@gmail.com
Password: guru123@@
```

> ⚠️ For demo/testing purposes only.

---
