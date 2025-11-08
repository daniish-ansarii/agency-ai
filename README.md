# 🌐 Agency.ai

> **A modern, animated digital agency website built using React, Tailwind CSS, and Framer Motion.**  
> Showcasing services, projects, and team members with beautiful animations and smooth interactivity.

---

## 🧭 Overview

**Agency.ai** is a sleek, responsive, and feature-rich **digital agency website** designed to represent a creative or tech-based brand.  
It integrates **scroll animations**, **dark/light theme support**, and a **working contact form** via **Web3Forms API**, providing both functionality and an engaging user experience.

---

## ✨ Features

✅ **Responsive Design** – Fully optimized for all screen sizes.  
✅ **Dark & Light Mode** – Toggle between themes; preference saved to `localStorage`.  
✅ **Custom Animated Cursor** – Adds an interactive visual experience.  
✅ **Framer Motion Animations** – Smooth transitions and scroll-based effects.  
✅ **Functional Contact Form** – Submits data securely using **Web3Forms API**.  
✅ **React Hot Toast** – For success/error notifications.  
✅ **Reusable Components** – Modular design for easy scalability and maintenance.  
✅ **Modern UI/UX** – Clean typography, gradients, and smooth section spacing.

---

## 🧩 Tech Stack

| Category | Technologies Used |
|-----------|-------------------|
| ⚛️ **Frontend** | React (Vite) |
| 🎨 **Styling** | Tailwind CSS |
| 🧠 **Animation** | Framer Motion (`motion/react`) |
| 📬 **Form Handling** | Web3Forms API |
| 🔔 **Notifications** | React Hot Toast |
| 🌗 **Theme Management** | React Hooks + LocalStorage |
| 🖋️ **Fonts** | [Manrope](https://fonts.google.com/specimen/Manrope) (Google Fonts) |

---

## 🧠 How It Works

### 1️⃣ Navbar  
- Sticky, responsive navbar with theme toggle and smooth transitions.

### 2️⃣ Hero Section  
- Displays tagline, background visuals, and subtle motion effects.

### 3️⃣ TrustedBy Section  
- Showcases brand logos dynamically to build trust.

### 4️⃣ Services Section  
- Hover-sensitive service cards with gradient lighting effects.

### 5️⃣ Our Work  
- Grid layout portfolio showcasing recent projects with animations.

### 6️⃣ Team Section  
- Lists team members with staggered fade-in effects.

### 7️⃣ Contact Form  
- Users can submit queries directly to **Web3Forms API**.  
- Instant feedback shown via `react-hot-toast`.

### 8️⃣ Footer  
- Newsletter subscription, quick links, and social media icons.

### 9️⃣ Custom Cursor  
- Dual-layer animated cursor ring and dot that follow user movement.

---

## ⚙️ Installation & Setup

1️⃣ **Clone the Repository** 
git clone https://github.com/daniish-ansarii/agency.ai.git
cd agency.ai

2️⃣ Install Dependencies 

npm install

3️⃣ Start the Development Server

npm run dev

4️⃣ Build for Production

npm run build


🌗 Theme System

The project detects your OS theme automatically.
You can toggle between Dark and Light mode manually via the top-right button.
Theme preferences persist across sessions using LocalStorage.

📬 Contact Form Integration

The ContactUs component uses Web3Forms for backend-free form handling.
It securely sends form data using an access_key and displays a success/error toast message.

🧑‍💻 Folder Structure

agency.ai/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── Navbar.jsx
│   │   ├── Hero.jsx
│   │   ├── TrustedBy.jsx
│   │   ├── Services.jsx
│   │   ├── OurWork.jsx
│   │   ├── Teams.jsx
│   │   ├── ContactUs.jsx
│   │   ├── Footer.jsx
│   │   └── Title.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
└── package.json

🎨 Design Highlights

Gradient-based color scheme (--color-primary: #5044E5)
Smooth shadows and rounded corners
Minimal layout with ample white space
Beautiful Manrope typography
Custom animations using Framer Motion

🚀 Live Demo
You can deploy this project easily on:
Vercel : https://agency-ai-2que.vercel.app

👨‍💻 Author
MD Danish
Mernstack Developer | React Enthusiast
