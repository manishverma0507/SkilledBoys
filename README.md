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

## 📁 Project Structure

```
Skilledboys/
├── frontend/
│   ├── index.html              # Landing/home page
│   ├── landing.html            # Customer landing page
│   ├── login.html              # Customer login
│   ├── register.html           # Customer registration
│   ├── worker-login.html       # Worker login
│   ├── worker-register.html    # Worker registration
│   ├── worker-dashboard.html   # Worker dashboard
│   ├── category.html           # Browse workers by category
│   ├── area.html               # Browse workers by location
│   ├── result.html             # Search results
│   ├── results.html            # Alternative results page
│   ├── about.html              # About us
│   ├── contact.html            # Contact/support
│   ├── css/
│   │   └── style.css           # Custom styles
│   ├── js/
│   │   └── script.js           # Main JavaScript
│   └── images/                 # Image assets
├── backend/
│   ├── server.js               # Main server file
│   ├── package.json            # Dependencies & scripts
│   ├── add-sample-data.js      # Sample data insertion
│   ├── check-db.js             # Database verification
│   ├── list-all-workers.js     # Worker listing utility
│   └── test-search.js          # Search functionality test
├── .gitignore                  # Git ignore rules
└── README.md                   # This file
```

---

## 🚀 Getting Started

### Prerequisites
- **Node.js** (v14 or higher)
- **npm** or **yarn**
- **MongoDB** (local or cloud like MongoDB Atlas)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/manishverma0507/SkilledBoys.git
   cd SkilledBoys
   ```

2. **Install Backend Dependencies:**
   ```bash
   cd backend
   npm install
   ```

3. **Configure Environment Variables:**
   Create a `.env` file in the `backend/` directory:
   ```
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/skilledboys
   JWT_SECRET=your_jwt_secret_key
   NODE_ENV=development
   ```

4. **Start MongoDB:**
   ```bash
   mongod
   ```

5. **Run the Backend Server:**
   ```bash
   npm start
   ```
   Server will run on `http://localhost:5000`

6. **Open Frontend:**
   - Navigate to `frontend/index.html` in your browser
   - Or use a local server: `python -m http.server 8000` (then visit `http://localhost:8000/frontend/`)

---

## 📝 Available Scripts

### Backend Scripts

```bash
# Start the server
npm start

# Run tests (configure as needed)
npm test
```

### Utility Scripts

```bash
# Add sample data to database
node add-sample-data.js

# Check database connection
node check-db.js

# List all workers
node list-all-workers.js

# Test search functionality
node test-search.js
```

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

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

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
