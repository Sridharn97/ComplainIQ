# 🧭 ComplainIQ - Campus Lost & Found Platform

ComplainIQ is a centralized, mobile-responsive digital platform designed to help students easily report and track lost-and-found items within their college campus. The goal is to replace outdated and scattered methods like WhatsApp groups, notice boards, and word-of-mouth with a simple, structured, and real-time solution.

---

## 🚀 Features

- **Easy Reporting**  
  Submit lost or found item reports with a title, image, description, and optional location data.

- **Real-Time Tracking**  
  View the live status of each report and get notified on updates.

- **Community Engagement**  
  Users can upvote and comment on reports to help surface high-priority items and increase visibility.

- **Admin Dashboard**  
  Admins can manage and prioritize reports based on urgency and engagement.

---

## 🎯 Problem Statement

Students currently face challenges in reporting and recovering lost items due to:
- Lack of a centralized system
- Scattered communication via WhatsApp, notice boards, etc.
- No real-time updates
- Confusion and inefficiency in item recovery

### Example:  
> Rahul loses his calculator and asks around, checks notice boards, and posts in class groups—but never hears back. There's no way for him to know if someone found it.

---

## 💡 Our Solution

ComplainIQ provides a single, unified platform to:
- Instantly post and view lost-and-found reports
- Engage with other students for faster recovery
- Let admins manage reports effectively

### Example:  
> Rahul reports his lost calculator on ComplainIQ with a photo and location. A student who finds it comments, and Rahul retrieves it the same day.

---

## 📈 Projected Impact

- **Students:** Quick and easy access to lost-and-found system  
- **Colleges:** Organized and efficient complaint/report handling  
- **Society:** Promotes digital adoption and student responsibility

---

## 🛠 Tech Stack

- **Frontend:** React (Vite + Tailwind CSS)  
- **Backend:** Node.js + Express  
- **Database:** MongoDB  
- **Deployment:** Netlify / Vercel (frontend), Render / Railway (backend)

---

## 📂 Folder Structure

```bash
ComplainIQ/
├── server/
│   ├── config/
│   ├── middleware/
│   │   └── auth.js
│   ├── models/
│   │   ├── AdminPost.js
│   │   ├── Post.js
│   │   ├── User.js
│   └── server.js
├── src/
│   ├── assets/
│   │   └── react.svg
│   ├── pages/
│   │   ├── AdminDashboard.jsx
│   │   ├── AdminReply.jsx
│   │   ├── CompletedComplaints.jsx
│   │   ├── CreatePost.jsx
│   │   ├── Login.jsx
│   │   ├── Profile.jsx
│   │   ├── Register.jsx
│   │   └── UserDashboard.jsx
│   ├── services/
│   │   └── api.js
│   ├── utils/
│   │   └── auth.js
│   ├── App.css
│   ├── App.jsx
│   ├── index.css
│   ├── main.jsx
│   └── theme.css
├── README.md
└── package.json
