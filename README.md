🛒 E-Commerce Website (MERN Stack)
A full-featured, production-grade E-Commerce Web Application built with the MERN Stack, integrated with Stripe for payments, JWT authentication with cookies, Zustand for state management, Redis for access token control, and admin/customer dashboards with live chat support.



📸 Project Preview
🧑‍💻 Customer Interface
![Screenshot 2025-06-29 190833](https://github.com/user-attachments/assets/bc7a84f0-bcf6-48ca-9696-7ee924106e6b)
![Screenshot 2025-06-29 190847](https://github.com/user-attachments/assets/de69de98-ed85-405b-83b2-50f9ade46e86)
![Screenshot 2025-06-29 190859](https://github.com/user-attachments/assets/23028722-7262-4de1-ba9b-8864327a9c6e)
![Screenshot 2025-06-29 190913](https://github.com/user-attachments/assets/85f10ba1-807e-4b57-9d3a-7e73ecf5f0f4)
![Screenshot 2025-06-29 191037](https://github.com/user-attachments/assets/85fe3e9a-efd4-4449-a517-1b8949382578)
![Screenshot 2025-06-29 191050](https://github.com/user-attachments/assets/3e345560-3a43-4eb5-9a68-a7bc95dcc444)
![Screenshot 2025-06-29 191426](https://github.com/user-attachments/assets/f96a44b9-ecf5-4b83-87d2-fc94db0e4f7d)

🛍️ Product Page
![Screenshot 2025-06-29 190859](https://github.com/user-attachments/assets/ec805104-5c7a-4764-9ce2-88858b3f6aee)

💳 Stripe Checkout
![Screenshot 2025-06-29 191201](https://github.com/user-attachments/assets/33c9b754-f225-49fa-b4ad-a5db909ddba3)
![Screenshot 2025-06-29 191218](https://github.com/user-attachments/assets/c6a2408a-a33b-4ade-b42f-56c7649bde7f)
![Screenshot 2025-06-29 191303](https://github.com/user-attachments/assets/f455ca52-d117-4855-a359-d11da96c6b5e)

🛠️ Admin Dashboard
![Screenshot 2025-06-29 191341](https://github.com/user-attachments/assets/d8b8fc8f-6f9d-4d26-b153-48648e454df6)
![Screenshot 2025-06-29 191354](https://github.com/user-attachments/assets/082a0ae4-8b19-49b8-af1b-02276dd85027)
![Screenshot 2025-06-29 191407](https://github.com/user-attachments/assets/ed8e50b0-0a52-48aa-b76f-9bc21170252d)

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



🤝 Contributions
Pull requests are welcome! For major changes, please open an issue first.

📧 Contact
Built with ❤️ by VelagaSubhash
📩 Email: Velagasubhash03@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/velaga-subhash-39236b250/
