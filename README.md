🛒 E-Commerce Website (MERN Stack)
A full-featured, production-grade E-Commerce Web Application built with the MERN Stack, integrated with Stripe for payments, JWT authentication with cookies, Zustand for state management, Redis for access token control, and admin/customer dashboards with live chat support.

Live Demo: [https://your-ecommerce-site.com](https://ecommerce-4ljp.onrender.com/)

📸 Project Preview
🧑‍💻 Customer Interface
![Screenshot 2025-06-29 190847](https://github.com/user-attachments/assets/4f0b70fb-4805-48dd-88ef-dc517a0396fd)
![Screenshot 2025-06-29 190833](https://github.com/user-attachments/assets/ba4c7847-bfe3-45ba-bbb5-6e38e98cd3c3)
![Screenshot 2025-06-29 190913](https://github.com/user-attachments/assets/18e0c01d-9721-40a1-ad35-dd24a92f0da4)
![Screenshot 2025-06-29 191037](https://github.com/user-attachments/assets/4a50996f-5b38-440e-8421-a17dcebaff43)
![Screenshot 2025-06-29 191050](https://github.com/user-attachments/assets/58cf3746-2e1f-4ce8-a921-0495a078bd62)
![Screenshot 2025-06-29 191426](https://github.com/user-attachments/assets/6e5185fc-4d78-4042-a6aa-1d5af6c507d3)

🛍️ Product Page
![Screenshot 2025-06-29 190859](https://github.com/user-attachments/assets/8a8e70da-1af3-44c3-8e06-9565847c87df)
💳 Stripe Checkout
![Screenshot 2025-06-29 191201](https://github.com/user-attachments/assets/8d217797-5ee8-4a70-96fa-3430dc216601)
![Screenshot 2025-06-29 191218](https://github.com/user-attachments/assets/f5d32726-afdb-4bae-b7d6-59a178440217)
![Screenshot 2025-06-29 191303](https://github.com/user-attachments/assets/ddd0e0f8-0636-4348-b30b-d77bbf5fb866)
🛠️ Admin Dashboard
![Screenshot 2025-06-29 191341](https://github.com/user-attachments/assets/eb416e0c-3ba8-4ab5-8e54-47d185fafdbf)
![Screenshot 2025-06-29 191354](https://github.com/user-attachments/assets/8a9d4f71-dff7-4b98-8ad3-e946c0b00ded)
![Screenshot 2025-06-29 191407](https://github.com/user-attachments/assets/58fb8d22-4fe9-4a06-bb29-21ba759ffd9f)
🚀 Features
👥 Authentication & User Management
Signup/Login with JWT & Cookies

Welcome emails with Nodemailer

Email confirmations on orders

🛒 E-Commerce Core
Add to cart with Toast notifications

Product listing, categories, filtering

Stripe payment gateway

Order summary & confirmation

🧾 Admin Panel
Add, edit, delete products

Mark products as featured

View total revenue, users, orders

Data visualizations for analytics

💬 Customer Support Chat
Real-time customer care chat

Admin and customer messaging

Persistent chat history

⚙️ Technologies Used
Tech	Description
MERN	MongoDB, Express, React, Node.js
JWT + Cookie-Parser	Auth with secure cookie tokens
Zustand	Lightweight state management
Redis	Manage access tokens & sessions
Stripe API	Secure payments
Nodemailer	Send emails on signup & orders
Cloudinary	Product image uploads
React-Toastify	User-friendly notifications

🛠️ Installation & Setup
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/mern-ecommerce.git
cd mern-ecommerce
2. Environment Variables
Create .env files in server/ and client/ folders:

Sample .env (server):

env
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
COOKIE_SECRET=your_cookie_secret
REDIS_URL=redis://localhost:6379
STRIPE_SECRET_KEY=your_stripe_key
EMAIL_USER=your_email
EMAIL_PASS=your_email_password
CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...
3. Run Server & Client
bash
Copy
Edit
# Server
cd server
npm install
npm run dev

# Client
cd ../client
npm install
npm start
🧪 Testing Features
Feature	Test Credentials
Admin Login	admin@example.com / Admin@123
User Login	user@example.com / User@123

🧠 Folder Structure
bash
Copy
Edit
.
├── client/                # React frontend (Zustand, Toasts, Chat UI)
├── server/                # Node.js backend (Express, Redis, JWT, Stripe)
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── utils/
├── assets/   
└── README.md
📊 Admin Dashboard Analytics
🔢 Total Orders

💰 Revenue

👥 Users

⭐ Top Selling Products

📈 Chart.js-based visual insights

🔐 Security Highlights
Secure JWT tokens with Redis session tracking

HTTPS cookie authentication

Rate-limiting & data validation

Cloudinary for secure image uploads

🌐 Deployment
Frontend: Vercel / Netlify

Backend: Render / Railway / VPS

Database: MongoDB Atlas

Redis: Upstash / Render

Cloudinary: Image hosting

✅ Live Site: https://your-ecommerce-site.com](https://ecommerce-4ljp.onrender.com/
🔧 Admin Panel: https://your-ecommerce-site.com](https://ecommerce-4ljp.onrender.com/admin

🤝 Contributions
Pull requests are welcome! For major changes, please open an issue first.

📧 Contact
Built with ❤️ by VelagaSubhash
📩 Email: Velagasubhash03@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/velaga-subhash-39236b250/
