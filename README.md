# Wanderlust 🏡✈️

## "Find your perfect stay, anytime, anywhere!." 

Wanderlust is a **full-stack Airbnb-style web application** built using the **MERN stack** (MongoDB, Express.js, React, Node.js) or (with EJS templating).  
It allows users to **browse, book, and manage property listings**, providing a seamless, interactive, and responsive experience, similar to Airbnb.  

---

## 🌟 Features

### **User Management & Authentication**
- **User Registration:** Secure sign-up process for new users.  
- **Login & Logout:** Authentication using **Passport.js** or **JWT**.  
- **User Profiles:** Users can manage their personal accounts and listings.  
- **Password Security:** Implements **bcrypt** for secure password hashing.  

### **Listing Management (CRUD Operations)**
- **View Listings:** Browse all properties with images, pricing, and details.  
- **Add Listings:** Hosts can add their properties with location, description, price, and images (stored on **Cloudinary**).  
- **Edit Listings:** Hosts can update property details.  
- **Delete Listings:** Hosts can remove their listings.  

### **Booking & Review System**
- **Booking Management:** Users can select check-in/out dates and book properties.  
- **Review System:** Users can leave ratings and reviews for properties.  
- **Review Management:** Authors can delete their own reviews.  

### **Interface & User Experience**
- **Responsive Design:** Works flawlessly on mobile, tablet, and desktop.  
- **Interactive Maps:** Displays property locations using **Mapbox API**.  
- **Flash Messages:** Real-time feedback to users (e.g., success/error messages).  
- **Clean UI:** Modern and user-friendly design inspired by Airbnb.  

---

## 🛠️ Technologies Used

| Layer | Technology | Purpose |
|-------|-----------|---------|
| Frontend | HTML, CSS, JavaScript | Core web development |
| Frontend | Bootstrap / Tailwind CSS | Styling & responsiveness |
| Frontend | React.js / EJS templating | Dynamic, interactive UI |
| Backend | Node.js | Server-side runtime |
| Backend | Express.js | API routes & server logic |
| Database | MongoDB | Store users, listings, reviews |
| Database | Mongoose | Object Data Modeling (ODM) |
| Cloud Services | Cloudinary | Store and manage property images |
| Cloud Services | Mapbox API | Interactive property maps |
| Deployment | Render.com | Hosting for full-stack application |
| Authentication | Passport.js / JWT | Secure login/signup & authorization |
| Security | Bcrypt | Password hashing |
| Data Validation | Joi | Ensure data integrity |
| Version Control | Git & GitHub | Track code & collaboration |

---

## 🚀 Getting Started

### **1. Clone the repository**
```bash
git clone https://github.com/shravani27-07/WanderLust.git
cd WanderLust
