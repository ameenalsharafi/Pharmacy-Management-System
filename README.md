# Pharmacy Management System (MEAN Stack)

## 📝 Overview
The **Pharmacy Management System** is a full-stack web application built using the **MEAN stack** (MongoDB, Express.js, Angular, and Node.js).  
It provides an all-in-one solution for managing pharmacy operations such as inventory control, supplier management, sales tracking, and order processing.

---

## 🚀 Features
- **User Authentication** – Sign up, log in, and manage access with JWT-based authentication.
- **Point of Sales (POS)** – Sell products directly and process payments efficiently.
- **Inventory Management** – Track drug stock, expiry dates, and restocking needs.
- **Supplier Management** – Add, view, and contact suppliers directly from the system.
- **Sales Analytics** – Generate and visualize sales charts.
- **Automated Alerts** – Notifications for low stock and near-expiry products.
- **Doctor Orders** – Verify and manage prescription orders.
- **Settings** – Configure pharmacy preferences and user settings.

---

## 📸 Screenshots
| Login Page | Sign Up Page |
|------------|--------------|
| ![Login](./screenshots/login.png) | ![Signup](./screenshots/signup.png) |

| Dashboard | Point of Sales |
|-----------|---------------|
| ![Dashboard](./screenshots/dashboard.png) | ![POS](./screenshots/Point%20Of%20Sales.png) |

| Doctor Orders | Sales Charts |
|---------------|--------------|
| ![Doctor Orders](./screenshots/doctor%20orders.png) | ![Sales Charts](./screenshots/Sales%20Charts%20generated.png) |

| Expired Products | Low Stock Alerts |
|------------------|------------------|
| ![Expired](./screenshots/Expired%20&%20about%20to%20expire%20table.png) | ![Low Stock](./screenshots/Out%20of%20Stock%20&%20About%20to%20get%20out%20of%20stock.png) |

| Preferences | Checkout |
|-------------|----------|
| ![Preferences](./screenshots/Preferences%20or%20Settings.png) | ![Checkout](./screenshots/Checking%20out%20drugs%20from%20Point%20Of%20Sales.png) |

---

## 🛠️ Installation & Setup
**Prerequisites:**
- Node.js (>= 12.x)
- Angular CLI
- MongoDB database (local or cloud via MongoDB Atlas)

**Steps:**
1. **Clone the repository**  
   ```bash
   git clone https://github.com/YOUR_USERNAME/Pharmacy-Management-System.git
   cd Pharmacy-Management-System
   ```

2. **Install dependencies for backend**  
   ```bash
   cd backend
   npm install
   ```

3. **Install dependencies for frontend**  
   ```bash
   cd ../
   npm install
   ```

4. **Configure environment variables**  
   Create a `.env` file in the backend folder and add:  
   ```
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

5. **Run backend server**  
   ```bash
   npm run start:server
   ```

6. **Run frontend**  
   ```bash
   ng serve
   ```

7. **Access the app**  
   Open [http://localhost:4200](http://localhost:4200) in your browser.

---

## 🏗️ Tech Stack
- **Frontend:** Angular 8
- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **Authentication:** JWT
- **Email Service:** Nodemailer

---

## 📜 License
This project is licensed under the [MIT License](LICENSE).

---

📌 *Note:* This is a showcase project. For production, ensure proper security configurations, environment variable management, and database backups.
