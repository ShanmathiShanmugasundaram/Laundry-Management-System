# Laundry Management System

The **Laundry Management System** is a full-stack web application designed to simplify laundry service operations by enabling customers to place orders online and allowing admins to manage services, pricing, and order status efficiently. The system supports real-time order tracking, automatic cost calculation, and secure payments.

---

## Features

### User Features
- User registration and login
- Browse laundry services (Wash, Iron, Wash & Fold, Dry Clean)
- Select garment types (T-shirt, Pant, Saree, Chudidar, Bedsheet, etc.)
- Automatic price calculation based on service and quantity
- Online payment and order confirmation
- Real-time order tracking

### Admin Features
- Admin login and dashboard
- View and manage all orders
- Update order status (Pending, Washing, Ironing, Delivered)
- Modify service and garment pricing
- Monitor payments and completed orders

---

## Technology Stack

- **Frontend:** React.js (Vite)
- **Backend:** Node.js, Express.js
- **Database:** MongoDB Atlas
- **Authentication:** Login & Signup
- **Payment Integration:** Online payment module
- **Version Control:** Git & GitHub

---

## Database Design

- **Users** – Stores customer and admin details  
- **Services** – Laundry services and pricing  
- **Orders** – Order details, garment types, quantities, and status  
- **Payments** – Transaction and payment status  
- **Notifications** – Real-time order updates  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/laundry-management-system.git
cd laundry-management-system
