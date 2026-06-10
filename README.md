# 🚀 Alford Portfolio Website

A modern personal portfolio website designed to introduce myself, showcase my interests and skills, and provide interactive features such as real-time messaging (Menfess).

## 🌟 Overview

This website includes:

* Personal profile
* Detailed biography
* Skills and interests showcase
* Contact information
* Interactive greeting feature
* Real-time Menfess system
* Google Authentication
* Futuristic video background
* Modern Glassmorphism design

---

## ✨ Key Features

### 👤 Personal Profile

Displays information about the website owner, background, ambitions, and interests in technology.

### 📊 Skills Showcase

Animated progress bars to visually represent skills and areas of expertise.

### 📞 Interactive Contact Section

Direct access to:

* Instagram
* GitHub
* Email
* Google Maps

### 👋 Interactive Greeting

Visitors can reveal a personalized welcome message with a single click.

### 💌 Real-Time Menfess System

Users can:

* Sign in with Google
* Send messages
* View messages in real time
* Display sender profile photos
* View message timestamps

### 🎨 Modern UI/UX

Built with:

* Glassmorphism effects
* Gradient color schemes
* Smooth animations
* Responsive layouts
* Full-screen video backgrounds

---

## 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript (ES6)

### Backend & Database

* Firebase Authentication
* Firebase Firestore Database

### Hosting

* Firebase Hosting
* GitHub Pages (optional)

---

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/USERNAME/REPOSITORY-NAME.git
```

### 2. Navigate to the Project Folder

```bash
cd REPOSITORY-NAME
```

### 3. Run the Website

Open:

```text
index.html
```

Alternatively, use VS Code with the **Live Server** extension:

```text
Right Click → Open With Live Server
```

---

## 🔥 Firebase Setup

Since this project uses Firebase services, you need to create your own Firebase project.

### Enable Authentication

```text
Firebase Authentication
↓
Google Provider
↓
Enable
```

### Create Firestore Database

Create a collection named:

```text
pesan
```

Required fields:

```text
nama
foto
isi
uid
timestamp
```

### Configure Firebase

Open:

```javascript
script.js
```

Replace the Firebase configuration with your own:

```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "XXXXXX",
  appId: "XXXXXX"
};
```

---

## 🚀 Deployment

### Firebase Hosting

Install Firebase CLI:

```bash
npm install -g firebase-tools
```

Login:

```bash
firebase login
```

Initialize Firebase:

```bash
firebase init
```

Deploy:

```bash
firebase deploy
```

---

## 📱 Responsive Design

This website is optimized for:

* Desktop
* Laptop
* Tablet
* Smartphone

---

## 🎯 Project Goals

This project was created for:

* Personal branding
* Online portfolio development
* Learning modern web development
* Exploring Firebase Authentication
* Implementing real-time databases
* Enhancing UI/UX design skills

---

## 👨‍💻 Developer

### Alford G. C. Bantong

A high school student from Sorong, Southwest Papua, Indonesia.

Areas of interest:

* Web Development
* UI/UX Design
* Technology
* Gaming & Esports

---

## 📬 Contact

**Instagram**
@justman07

**GitHub**
https://github.com/AlfordPages

**Email**
[alfordbantong@gmail.com](mailto:alfordbantong@gmail.com)

---

## ⭐ Support

If you find this project useful:

⭐ Give this repository a Star.

Feel free to Fork, improve, and customize it for your own projects.

---

© 2026 Alford Portfolio Website

Built with ❤️ using HTML, CSS, JavaScript, and Firebase.
