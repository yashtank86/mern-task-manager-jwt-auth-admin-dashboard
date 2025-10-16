
# 🧠 Task Manager — MERN Stack Project

![Task Manager Banner](./assets/banner.png)
_A powerful task management web app built with the MERN stack featuring authentication, dashboards, task analytics, and admin-user collaboration._

---

### 🌐 **Live Demo**
🔗 [View Deployed App on Render](https://your-app-url.onrender.com)  
💻 [View Source Code on GitHub](https://github.com/yourusername/task-manager)

---

## 📸 **Screenshots**

### 🔐 Authentication (Login / Register)
![Login Page](./screenshots/login.png)
![Register Page](./screenshots/register.png)

### 🧑‍💼 Admin Dashboard
![Admin Dashboard](./screenshots/admin-dashboard.png)

### 👤 User Dashboard
![User Dashboard](./screenshots/user-dashboard.png)

### 📋 Task Creation (Admin)
![Create Task](./screenshots/create-task.png)

### 📊 Reports & Analytics
![Reports](./screenshots/reports.png)

---

## 🚀 **Features**

### 🔑 **Authentication & Authorization**
- JWT-based secure authentication.
- Role-based access control (Admin / User).
- Separate dashboards for Admin and Users.

---

### 📊 **Dashboard Analytics**
#### 🧑 User Dashboard:
- Displays task statistics using **Pie Chart** (Pending, In Progress, Completed).
- **Bar Chart** showing Task Priority distribution (Low, Medium, High).
- Recently added tasks section.
- Task counters at the top:  
  `Total Tasks | Pending | In Progress | Completed`

#### 🧑‍💼 Admin Dashboard:
- Overview of all system tasks and users.
- Same analytics charts for quick insights.
- Recently created tasks summary.
- Team performance overview.

---

### 📝 **Task Management (Admin)**
- Create tasks with:
  - `Title`, `Description`, `Priority (Low, Medium, High)`, and `Due Date`.
  - Assign multiple members (users).
  - Add To-do checklist (subtasks).
  - Add attachments (URL format).
- Tasks are visible to assigned members only.
- Real-time task status and progress updates based on checklist completion.

---

### 📦 **Reports & Exports (Admin)**
- Download **Task Reports** in Excel:
  - Includes: Task ID, Title, Description, Priority, Status, Assigned Members.
- Download **User Reports** in Excel:
  - Includes: Username, Email, Total Assigned Tasks, Pending, In Progress, and Completed counts.

---

### 👥 **User Features**
- View only assigned tasks.
- Update subtasks (To-do checklist).
- Watch automatic task progress and status updates.
- Filter tasks by:
  - `All | Pending | In Progress | Completed`
- View task details including:
  - Priority, Progress %, Due Date, Attachments, and Assigned Members.

---

### 💻 **Responsive Design**
- Fully responsive for all devices (Desktop, Tablet, Mobile).
- Smooth UI/UX with modern animations and charts.

---

## 🧰 **Tech Stack**

| Layer | Technology |
|-------|-------------|
| **Frontend** | React.js, React Router, Axios, Chart.js, Tailwind CSS |
| **Backend** | Node.js, Express.js, Cors|
| **Database** | MongoDB (Mongoose ORM) |
| **Authentication** | JSON Web Tokens (JWT), bcrypt |
| **Deployment** | Render (Backend + Frontend), GitHub |
| **Reports** | XLSX (Excel Export) |

---

## ⚙️ **Installation & Setup**

### 🧾 Prerequisites
Make sure you have installed:
- Node.js (v16+)
- MongoDB
- npm or yarn

---

### 🪜 Steps

```bash
# 1️⃣ Clone the Repository
git clone https://github.com/yourusername/task-manager.git

# 2️⃣ Navigate into Project
cd task-manager

# 3️⃣ Install Dependencies
cd server && npm install
cd ../client && npm install

# 4️⃣ Add Environment Variables
Create `.env` file in `server` folder and add:
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_secret_key
PORT=5000

# 5️⃣ Run Backend
cd server
npm start

# 6️⃣ Run Frontend
cd client
npm start
```

Then open 👉 `http://localhost:3000`

---

## 📦 **Folder Structure**

```
Task-Manager/
│
├── client/                # React Frontend
│   ├── src/
│   │   ├── components/    # UI Components
│   │   ├── pages/         # Page Components
│   │   ├── context/       # Context API
│   │   ├── utils/         # Helper functions
│   │   └── App.js
│   └── package.json
│
├── server/                # Node + Express Backend
│   ├── config/            # Database & JWT config
│   ├── controllers/       # Business Logic
│   ├── models/            # Mongoose Models
│   ├── routes/            # API Routes
│   ├── middleware/        # Auth Middleware
│   └── server.js
│
└── README.md
```

---

## 📈 **Future Enhancements**
- Task comments section 💬  
- File upload for attachments 📎  
- Email notifications for task updates 📧  
- Dark/Light mode toggle 🌗  

---

## 🧑‍💻 **Author**
**Yash T.**  
💼 Junior Software Engineer  
🌍 [LinkedIn](https://linkedin.com/in/your-link)  
📧 [Email Me](mailto:work.tankyash@gmail.com)

---

## ⭐ **Support**
If you like this project, don’t forget to ⭐ **star** the repository and share it!

---

## 🖼️ **Sample Preview**

| Admin Dashboard | User Dashboard |
|-----------------|----------------|
| ![Admin Dashboard](./screenshots/admin-dashboard.png) | ![User Dashboard](./screenshots/user-dashboard.png) |
