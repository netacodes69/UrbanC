# 🛠️ SkillTrade

**SkillTrade** is a full-stack service marketplace platform that connects users with skilled professionals such as electricians, plumbers, painters, and other service providers. The platform simplifies discovering, booking, and managing local services through a clean, modern, and role-based web application.

🔗 **Live Demo:** https://skill-trade-next-15.vercel.app/  
📦 **GitHub Repository:** https://github.com/netacodes69/Skill_Trade  

SkillTrade aims to bridge the gap between customers and trusted service providers by offering an intuitive interface, secure authentication, and scalable backend architecture.

---

## 🚀 Features

- Browse and discover skilled professionals easily  
- Role-based access for Users and Service Providers  
- Secure authentication using JWT  
- Modern, responsive UI built with Next.js  
- Service listing and booking workflow  
- AI-powered **SkillBot** for assistance and guidance  

---

## 🧱 Tech Stack

- **Frontend:** Next.js  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication / ORM:** JWT, Mongoose  

---

## ⚙️ Setup & Installation

1️⃣ Clone the Repository
git clone https://github.com/netacodes69/Skill_Trade.git
cd Skill_Trade

2️⃣ Frontend Setup
npm install
npm run dev

Create a .env.local file:
NEXT_PUBLIC_BASE_URL=http://localhost:8000
NEXT_PUBLIC_HERE_API_KEY=your_here_maps_api_key

Frontend runs at:
http://localhost:3000

3️⃣ Backend Setup
cd server
npm install
npx nodemon server

Create a .env file:
DB_CONNECT=your_mongodb_uri
PORT=8000
SECRET=your_jwt_secret
email_id=
pass_key=

Backend runs at:
http://localhost:8000


🧑‍💻 Usage
Start both frontend and backend servers
Open http://localhost:3000
Register or log in as a user or service provider
Browse, list, or book services seamlessly

🧩 Future Enhancements
Online payments and wallet integration
Rating & review system
Real-time booking notifications
Admin dashboard and analytics
Location-based service recommendations

