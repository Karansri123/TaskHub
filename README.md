📌 TaskHub

TaskHub is a powerful and scalable multi-tenant project management system built with Node.js, MongoDB, and React.
Designed for real-world B2B SaaS needs, it provides everything from authentication to role-based permissions, workspace management, project tracking, and task collaboration.

🌟 Key Features

🔐 Authentication – Google Sign-In, Email & Password

🏢 Workspaces – Create & Manage Multiple Workspaces

📊 Projects & Epics – Organize work efficiently

✅ Tasks – CRUD operations with status, priority & assignee

👥 Roles & Permissions – Owner, Admin, Member

✉️ Invitations – Invite members to workspaces

🔍 Filters & Search – By status, priority, assigned user

📈 Analytics Dashboard – Insights & reports

📅 Pagination & Load More – Handle large datasets

🔒 Session Management – Cookie-based sessions

🚪 Logout – Secure session termination

🌱 Database Seeding – Test data setup

💾 Mongoose Transactions – Ensure data integrity

🚀 Tech Stack

Backend: Node.js, Express.js, TypeScript

Frontend: React, Vite.js, TypeScript

Database: MongoDB with Mongoose

Auth: Google OAuth, JWT, Cookie Sessions

UI/UX: TailwindCSS, Shadcn UI

Other: REST APIs, Transactions, Analytics

🛠️ Installation & Setup

Clone the repo

git clone https://github.com/your-username/taskhub.git
cd taskhub


Backend Setup

cd backend
npm install
npm run dev


Frontend Setup

cd frontend
npm install
npm run dev


Environment Variables
Create .env files in both backend and frontend with:

MONGO_URI=your_mongo_url
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_secret
SESSION_SECRET=your_session_secret


📅 Roadmap

✅ Multi-tenant Workspaces

✅ Role-based Access Control

⏳ File Uploads & Attachments

⏳ Real-time Notifications (Socket.io)

⏳ Kanban Board & Gantt Charts

🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.
