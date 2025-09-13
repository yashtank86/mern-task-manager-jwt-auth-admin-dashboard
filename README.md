📝 Task Manager – MERN Stack Project

  A full-featured Task Management Web Application built with the MERN (MongoDB, Express, React, Node.js) stack. 
  This app allows users to manage daily tasks with authentication, deadlines, priorities, and statuses.


✨ Features

✅ User authentication (Login, Register, JWT)

📋 Create, edit, delete, and complete tasks

🏷️ Task priority & status tracking

📆 Due date reminders

🔍 Filter & sort tasks

💡 Responsive & user-friendly UI

🔐 Secure APIs with JWT

🌐 RESTful API architecture

🖼️ Demo

Live Demo: https://task-manager-demo.vercel.app

(Replace with your deployed link)


Dashboard showing active tasks, priority badges, and filter options.

⚙️ Tech Stack
Tech	Description
MongoDB	NoSQL database for storing tasks and user data
Express.js	Backend framework to handle API routes
React.js	Frontend UI library
Node.js	JavaScript runtime environment
JWT	Secure authentication system
Mongoose	MongoDB ODM for schema modeling
React Router	Frontend routing
TailwindCSS / Bootstrap	Styling the UI (choose one or customize)
📁 Project Structure
task-manager/
│
├── client/              # React Frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── services/
│       └── App.jsx
│
├── server/              # Node.js + Express Backend
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   └── routes/
│
└── README.md

🚀 Getting Started
1. Clone the repository
git clone https://github.com/yourusername/task-manager.git
cd task-manager

2. Setup Environment Variables

Create .env files in both /server and /client directories:

Example (server/.env)

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

3. Install Dependencies
# Backend
cd server
npm install

# Frontend
cd ../client
npm install

4. Run the App (Dev Mode)
# Start backend
cd server
npm run dev

# Start frontend
cd ../client
npm start

🔐 Authentication Flow

User registers or logs in

Server issues a JWT token

Frontend stores the token in localStorage

Protected routes check for token validity

🧪 API Endpoints
Method	Endpoint	Description
POST	/api/auth/register	Register a new user
POST	/api/auth/login	Login user
GET	/api/tasks/	Get all user tasks
POST	/api/tasks/	Create a task
PUT	/api/tasks/:id	Update a task
DELETE	/api/tasks/:id	Delete a task
📷 Screenshots
Dashboard	Task Form	Login

	
	
🛠️ Future Improvements

📱 Mobile-first design

📅 Calendar integration

📧 Email notifications

⏱️ Pomodoro timer

🧠 AI-based task prioritization (experimental)

🤝 Contributing

Contributions are welcome! Please open issues or submit a pull request for improvements.

Fork the project

Create your feature branch (git checkout -b feature/task-filter)

Commit your changes (git commit -m 'Add task filter')

Push to the branch (git push origin feature/task-filter)

Open a Pull Request

📄 License

This project is licensed under the MIT License - see the LICENSE
 file for details.

🙋‍♂️ Author

Your Name – @yashtank86

Feel free to reach out for collaboration or feedback!
