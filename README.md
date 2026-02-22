# 📚 StudyNotion – Full-Stack Ed-Tech Platform

**StudyNotion** is a fully functional ed-tech platform that enables users to create, consume, and rate educational content.  
Built using the **MERN stack**, the platform focuses on accessibility, interactive learning, and smooth user experience for both students and instructors.

---

## ✨ Features

### 👩‍🎓 For Students
- Browse and view all available courses  
- Course wishlist  
- Full course playback pages  
- Checkout & secure payment flow (Razorpay)  
- User profile management  

### 🧑‍🏫 For Instructors
- Dashboard with insights  
- Course creation & content management  
- Edit profile & view analytics  

### 🛠️ Admin (Future Scope)
- Platform overview dashboard  
- Instructor management  
- User and course insights  

---

## 🏗️ System Architecture

StudyNotion follows a **client–server architecture** with:

- **Frontend:** React.js + Tailwind CSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Cloud Services:** Cloudinary for media, Razorpay for payments  

---

## 🎨 Front-End Overview

Built using:
- **React.js**
- **Tailwind CSS**
- **Redux** for state management  
- **REST APIs** for all data communication  
- Designed using **Figma** (UI/UX planning)  

Frontend pages include:
- Homepage  
- Course List  
- Course Details  
- Wishlist  
- Checkout  
- Course Playback  
- User Details & Edit Profile  
- Instructor Dashboard & Course Management  

---

## 🔧 Back-End Overview

Backend built using:
- **Node.js**
- **Express.js**
- **MongoDB + Mongoose**
- **JWT Authentication**
- **Bcrypt for password hashing**

Key Backend Features:
- User Authentication (Login, Signup, OTP Verification)
- Course CRUD (Create, Read, Update, Delete)
- Rating & Review System
- Payment Integration (Razorpay)
- Cloud-based media management (Cloudinary)

---

## 🛣️ API Endpoints (Examples)

- `POST /api/auth/signup` – Create new user  
- `POST /api/auth/login` – Login & JWT generation  
- `GET /api/courses` – Get all courses  
- `POST /api/courses` – Create new course  
- `PUT /api/courses/:id` – Update a course  
- `DELETE /api/courses/:id` – Delete course  

---

## 🚀 Deployment

StudyNotion uses:

- **Vercel** → Frontend deployment  
- **Render / Railway** → Backend hosting  
- **MongoDB Atlas** → Cloud database  
- **Cloudinary** → Media storage  

---

## 🔮 Future Enhancements

- Personalized learning paths  
- Gamification (badges, progress XP)  
- Social learning features  
- Mobile App (Android + iOS)  
- ML-based course recommendations  
- VR/AR learning modules  

---

## 👩‍💻 Author

**Bhavya Paliwal**  
B.Tech AI & DS | Aspiring Software Engineer  

🔗 GitHub: https://github.com/Bhavya-Paliwal22  
🔗 LinkedIn: https://www.linkedin.com/in/bhavya-paliwal-13a897354/
