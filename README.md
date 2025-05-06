# 💹 Zerodha Clone – Full-Stack Stock Trading Platform

A full-stack clone of [Zerodha](https://zerodha.com), India's largest stock brokerage platform. This project simulates core features of a stock trading dashboard, including user authentication, stock listings, portfolio management, and responsive UI – built using the **MERN stack**.

![Zerodha Clone Demo]("https://drive.google.com/file/d/1kgbvCc59JeydgGaonl7Ru8ntTmzrR20x/view?usp=drive_link") <!-- Replace with actual image or demo GIF -->

---

## 🚀 Features

✅ User Sign Up / Login with JWT Authentication  
✅ Dashboard showing live/mock stock data  
✅ Responsive UI inspired by Zerodha  
✅ Portfolio & order summary  
✅ Secure APIs with validation  
✅ Error handling and clean UX  
✅ Modular backend with MVC architecture  

---

## 🛠️ Tech Stack

**Frontend**  
- React.js  
- React Router  
- Axios  
- Tailwind CSS / Bootstrap  

**Backend**  
- Node.js  
- Express.js  
- MongoDB + Mongoose  
- JWT for Auth  
- Bcrypt for Password Hashing  

**Others**  
- Postman (for API testing)  
- Git & GitHub  
- Vercel / Render (for deployment)  

---

## 📦 Folder Structure
student-apnacollege/
│
├── backend/ # Node.js + Express server
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── .env # Environment variables
│ └── server.js
│
├── dashboard/ # Data visualizations using Chart.js
│ ├── chart-data.js
│ └── graphs.js
│
├── frontend/ # React frontend
│ ├── public/
│ └── src/
│ ├── components/
│ ├── pages/
│ └── App.js
│
├── .gitignore
├── README.md
└── package.json

---

## 🚀 Features

- ✅ JWT Authentication (Signup & Login)
- ✅ Interactive Dashboard with Chart.js
- ✅ Stock data visualization
- ✅ Secure RESTful API
- ✅ Responsive design for mobile/tablet
- ✅ Folder-wise code separation (MVC structure)

---

## 🛠 Tech Stack

| Frontend    | Backend       | Tools         |
|-------------|----------------|---------------|
| React.js    | Node.js        | Git & GitHub  |
| TailwindCSS | Express.js     | Postman       |
| Chart.js    | MongoDB        | Render/Vercel |
| Axios       | JWT, Bcrypt    | dotenv        |

---

## 🧪 Setup Instructions

### Clone the Repository:
```bash
git clone https://github.com/Kishansingh890kiit/Zerodha-clone
cd student-apnacollege
Backend Setup:
bash
Copy
Edit
cd backend
npm install
touch .env
# Add MONGO_URI and JWT_SECRET
npm start
✨ Future Enhancements
💼 Add Buy/Sell stock simulation

🔄 Real-time stock updates via WebSockets or APIs

👨‍💼 Admin dashboard for managing stocks and users

📈 Use TradingView for advanced charting

