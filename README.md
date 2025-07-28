# 🌴 Balilore | Full Stack Web Application

A responsive and scalable full-stack web application developed for BaliLore — built with **React.js**, **Tailwind CSS**, **Node.js**, **Express.js**, and **MongoDB**.

> 🛠️ This repository combines both the frontend and backend in a single monorepo.

---

## 📁 Folder Structure

Balilore-task/
│
├── Balilore/ # Backend (Node.js + Express + MongoDB)
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── utils/
│ ├── .env # Environment variables (not committed)
│ └── server.js # Entry point
│
├── Bailore-front/ # Frontend (React + Tailwind CSS)
│ ├── public/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── App.jsx
│ │ └── main.jsx
│ └── vite.config.js
│
└── README.md

yaml
Copy
Edit

---

## 🚀 Tech Stack

**Frontend:**
- React.js (with Vite)
- Tailwind CSS
- Axios
- React Router DOM

**Backend:**
- Node.js
- Express.js
- MongoDB + Mongoose
- Stripe API
- JWT Authentication
- Dotenv

---

## ⚙️ Environment Variables

Create a `.env` file inside the `Balilore/` (backend) directory:

```bash
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_key
If contributing or sharing: create a .env.example for reference.

🧑‍💻 How to Run Locally
1. Clone the Repo
bash
Copy
Edit
git clone https://github.com/tabish-27/Balilore-task.git
cd Balilore-task
2. Setup Backend
bash
Copy
Edit
cd Balilore
npm install
npm run dev
3. Setup Frontend
bash
Copy
Edit
cd ../Bailore-front
npm install
npm run dev
Then open: http://localhost:5173

✅ Features
💳 Stripe Payment Integration

🔐 JWT-Based Authentication

📦 Modular Backend Architecture

📱 Responsive Frontend UI

🔄 API Integration with Axios

🌐 Fully functional end-to-end stack

📸 Screenshots (Optional)
Add UI screenshots here if needed!

👨‍💻 Developer
Made with 💻 by Tabish Javed
🔗 LinkedIn | 🧠 GitHub

📄 License
This project is licensed under the MIT License.

yaml
Copy
Edit

---

### ✅ Next Steps You Can Do

1. Paste this content inside your `README.md`
2. Add a `.env.example` file (let me know if you want that)
3. Optional: Add screenshots (`/screenshots/home.png`, etc.)

Let me know if you'd like a lighter version or if I should include deployment instructions too.
