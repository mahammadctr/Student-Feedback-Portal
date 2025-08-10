````markdown
# 📚 Student Feedback Portal

A **full-stack web application** for managing and collecting feedback from students and teachers.  
Built with **React**, **Node.js**, **Express**, **MongoDB**, and **Material UI** for a responsive, modern, and user-friendly experience.

---

## 🚀 Features

- **Role-based Access**: Teacher and Student accounts.
- **JWT Authentication**: Secure login & signup.
- **Feedback Management**:
  - Create and submit feedback forms.
  - View all feedback.
  - Filter feedback by branch.
- **Profile Management**: Update and view teacher/student profiles.
- **Data Visualization**: Charts for feedback insights.
- **Responsive UI**: Works seamlessly on desktop and mobile.
- **Notifications**: Bootstrap Toasts and Material UI alerts.
- **Integration with Hugging Face API**: For NLP/ML processing of feedback.

---

## 📷 Screenshots

### Notifications
![Notifications](./screenshots/notifications.png)

### Signup Page
![Signup](./screenshots/signup.png)

### Login Page
![Login](./screenshots/login.png)

### Teacher Dashboard
![Teacher Dashboard](./screenshots/dashboard.png)

### Create Feedback
![Create Feedback](./screenshots/create-feedback.png)

### Student Profile
![Student Profile](./screenshots/student-profile.png)

### Teacher Profile
![Teacher Profile](./screenshots/teacher-profile.png)

---

## 🛠 Tech Stack

### **Frontend**
- **React 17** – UI framework.
- **Material UI (MUI)** – UI components.
- **Chart.js + react-chartjs-2** – Feedback visualization.
- **React Router DOM v6** – Routing & navigation.
- **Axios** – HTTP requests.
- **Yup** – Form validation.
- **Chroma.js** – Color manipulation.
- **React Table** – Data table rendering.

### **Backend**
- **Node.js** – JavaScript runtime.
- **Express.js** – Web server framework.
- **MongoDB** – NoSQL database.
- **Mongoose** – ODM for MongoDB.
- **dotenv** – Environment variable management.
- **cors** – Cross-origin request handling.
- **jsonwebtoken (JWT)** – Authentication.
- **morgan** – HTTP request logging.
- **node-fetch** – External API calls.
- **path** – File path utilities.

### **Development Tools**
- **nodemon** – Auto server restart.
- **ESLint & Prettier** – Code linting and formatting.

---

## 📦 Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/mahammadctr/Student-Feedback-Portal.git
cd Student-Feedback-Portal
````

### 2️⃣ Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file in the `backend` folder:

```env
MONGODB_URL="your-mongodb-connection-string"
HF_TOKEN="your-huggingface-token"
PORT=3005
```

Start the backend:

```bash
npm start
```

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm start
```

---

## 🔐 Environment Variables

| Variable     | Description                         |
| ------------ | ----------------------------------- |
| MONGODB\_URL | MongoDB connection string           |
| HF\_TOKEN    | Hugging Face API token              |
| PORT         | Backend server port (default: 3005) |

---

## 📬 API Endpoints (Examples)

| Method | Endpoint            | Description              |
| ------ | ------------------- | ------------------------ |
| POST   | `/auth/signup`      | Register a new user      |
| POST   | `/auth/login`       | User login               |
| GET    | `/feedback`         | Get all feedback         |
| POST   | `/feedback`         | Create new feedback      |
| GET    | `/feedback/:branch` | Get branch-wise feedback |

---

## 📊 Architecture Diagram

```plaintext
Frontend (React + MUI)
        ↓ Axios HTTP Requests
Backend (Node.js + Express)
        ↓ Mongoose Queries
Database (MongoDB)

External Integration:
Backend ↔ Hugging Face API
```

---

## 🧑‍💻 Contributing

1. **Fork** the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature-name
   ```
3. Commit and push changes:

   ```bash
   git push origin feature-name
   ```
4. Open a **Pull Request**.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🙌 Acknowledgements

* [Material UI](https://mui.com)
* [Chart.js](https://www.chartjs.org)
* [Bootstrap](https://getbootstrap.com)
* [Hugging Face](https://huggingface.co)
* [MongoDB](https://www.mongodb.com)

```
```
