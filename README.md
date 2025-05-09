# restaurant-order-manager
# 🍽️ Restaurant Order Management System

A full-featured Restaurant Order Management System built using the **MEAN** stack (MongoDB, Express.js, Angular, Node.js). This system allows customers to browse and order food items, and provides an admin panel to manage and monitor orders in real-time.

---

## 🚀 Features

### 👨‍🍳 User Features
- Browse menu items by category (Appetizers, Main Course, Beverages, etc.)
- Add items to cart
- Place orders with order summary and payment info
- View past orders and order status updates

### 🛠️ Admin Features
- Secure admin login
- Dashboard to view real-time orders
- Update order status (Pending, Preparing, Delivered)
- Add/edit/delete menu items
- Manage categories and prices

---

## 🧰 Tech Stack

- **Frontend:** Angular
- **Backend:** Node.js with Express.js
- **Database:** MongoDB
- **Authentication:** JWT-based authentication for Admin
- **Deployment:** Can be deployed on platforms like Heroku, Vercel, or AWS

---

## 🏗️ Project Structure

```
restaurant-order-system/
├── frontend/               # Angular frontend
│   ├── src/
│   └── ...
├── backend/               # Express.js backend
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── ...
├── README.md
└── package.json
```

---

## 📦 Installation

### 1. Clone the repository
```bash
git clone https://github.com/Venkata-sai-koushik-M/restaurant-order-manager.git
cd restaurant-order-manager
```

### 2. Install backend dependencies
```bash
cd backend
npm install
```

### 3. Install frontend dependencies
```bash
cd frontend
npm install
```

### 4. Configure environment variables

Create a `.env` file inside the `backend/` directory with the following:
```env
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_secret_key
```

### 5. Start the development servers

#### Backend
```bash
cd backend
npm run dev
```

#### Frontend
```bash
cd frontend
ng serve
```

---

## 🧪 Sample Admin Login (for testing)
```bash
Username: admin@example.com
Password: admin123
```

> You can change this by editing the `seed` file or creating an admin account through API.

---

## 🔒 Security
- JWT authentication for admin access
- Input validation and error handling
- CORS and Helmet for basic protection

---

## 📝 Future Improvements
- Payment gateway integration (e.g., Stripe)
- Mobile responsive UI
- Email notifications for orders
- Real-time order updates with WebSockets

---

## 🙌 Contributing

Contributions are welcome! Please open an issue or submit a pull request for suggestions or improvements.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Developed by
**Venkata sai koushik M**  
[GitHub](https://github.com/Venkata-sai-koushik-M) 

Watch Youtube video for set up, run, and demo

https://www.youtube.com/watch?v=Yf8zB4dXp7I

Give a star if you like it!
