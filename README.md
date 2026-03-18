# SkilledBoys - Connecting Customers with Trusted Local Experts

![SkilledBoys](frontend/images/logoskilled.png)

> **"काम कोई भी हो, सिर्फ़ एक क्लिक, और हर काम आसान।"**  
> *No matter what the job, just one click and every job becomes easy.*

---

## 📋 Project Overview

**SkilledBoys** is a modern marketplace platform that connects customers with trusted local skilled workers. The platform enables customers to find and hire professional workers (plumbers, electricians, carpenters, etc.) without any intermediary costs, while workers can register and receive job opportunities in their area.

### Key Statistics
- 🎯 **15,000+** Happy Customers
- 💼 **50,000+** Jobs Completed
- ⭐ **4.8★** Average Rating
- 🏙️ **25+** Cities Covered

---

## ✨ Features

### For Customers
- 🔍 **Search & Filter** workers by category and location
- 📱 **Easy Booking** interface
- ⭐ **Ratings & Reviews** system
- 🔒 **Secure Transactions**
- 📞 **Direct Contact** with workers
- 💬 **Customer Support**

### For Workers
- 📝 **Easy Registration** process
- 📍 **Location-based** job listings
- 💰 **Instant Earnings**
- 📊 **Profile Management**
- 🏆 **Build Reputation** through ratings
- 📱 **Dedicated Dashboard** for job management

---

## 🛠️ Technology Stack

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Styling & responsive design
- **JavaScript (ES6+)** - Interactivity
- **Tailwind CSS** - Utility-first CSS framework
- **Typed.js** - Text animation library
- **Font Awesome** - Icon library

### Backend
- **Node.js** - JavaScript runtime
- **Express.js** - Web framework
- **MongoDB** - NoSQL database
- **Mongoose** - Object modeling
- **JWT** - Authentication & authorization
- **bcryptjs** - Password hashing
- **CORS** - Cross-origin resource sharing

### Deployment
- **GitHub** - Version control & repository hosting

---

## 🚀 Getting Started

### Prerequisites
- **Node.js** (v14 or higher)
- **npm** or **yarn**
- **MongoDB** (local or cloud like MongoDB Atlas)

---

## 🔐 Authentication

- **Customer Registration**: Email & password with bcryptjs hashing
- **Worker Registration**: Email, phone, skills, location
- **JWT Tokens**: Secure token-based authentication
- **Password Reset**: (To be implemented)

---

## 🗄️ Database Schema (Overview)

### Users Collection
- Email, Password (hashed), Name, Phone, Address, Role (Customer/Worker)

### Workers Collection
- User ID, Category, Skills, Rating, Reviews, Service Area, Contact Info

### Jobs/Bookings Collection
- Customer ID, Worker ID, Category, Status, Rating, Payment Info

---

## 🌐 API Endpoints (To be documented)

```
POST   /api/auth/register       - User/Worker registration
POST   /api/auth/login          - User login
GET    /api/workers             - List all workers
GET    /api/workers/:id         - Get worker details
GET    /api/workers/search      - Search workers
POST   /api/bookings            - Create booking
GET    /api/bookings/:id        - Get booking details
POST   /api/reviews             - Submit review/rating
```

---

## 📄 License

This project is licensed under the **ISC License** - see the LICENSE file for details.

---

## ✉️ Contact & Support

- **Email**: support@skilledboys.com
- **Website**: https://www.skilledboys.com
- **GitHub**: [manishverma0507/SkilledBoys](https://github.com/manishverma0507/SkilledBoys)

---

## 🙏 Acknowledgments

- **Tailwind CSS** - For utility-first CSS framework
- **Typed.js** - For text animation
- **Font Awesome** - For icons
- **Express.js** - For backend framework
- **MongoDB** - For database

---

## 📊 Project Status

🚀 **Active Development** - Version 1.0.0

### Upcoming Features
- [ ] Real-time chat between customers and workers
- [ ] Payment gateway integration (Razorpay/Stripe)
- [ ] Advanced search filters
- [ ] Mobile app (React Native/Flutter)
- [ ] Admin dashboard
- [ ] Email notifications

---

## 👨‍💻 Author

**Manish Verma**  
GitHub: [@manishverma0507](https://github.com/manishverma0507)

---

**Last Updated**: March 18, 2026
