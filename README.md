# 🚗 ASU Smart Parking (Driver App)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white)

A mobile-first, Single Page Application (SPA) designed to help Angelo State University (ASU) drivers find, reserve, and pay for parking spots in real-time. This project serves as a full-stack MVP (Minimum Viable Product) utilizing Vanilla JavaScript for the frontend and Google Firebase for backend authentication.

## 🔗 Live Demo
> **[Play with the Live App Here!]** USER mode (https://starjay88.github.io/ASU-Smart-Parking/user.html)  ADMIN mode (https://starjay88.github.io/ASU-Smart-Parking/)

## ✨ Key Features

* **🔐 Secure Authentication:** Real-time user registration and login powered by Google Firebase Auth.
* **📍 Interactive Floor Map:** A dynamic UI grid where users can view available spots and reserve them instantly.
* **⏱️ Dynamic Fee Calculation:** A live JavaScript timer that calculates parking fees in real-time ($0.01 per 10 seconds) upon reservation.
* **⚡ Single Page Application (SPA):** Seamless transitions between Map, Pay, and Profile views without page reloads.
* **💾 Persistent State Management:** Utilizes browser `LocalStorage` to maintain user sessions and active parking reservations even after refreshing the page.
* **⚠️ Smart Alerts:** Custom toast notifications and an auto-expiring reservation system (5-minute limit) to prevent spot hoarding.

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6 Modules)
* **Backend:** Google Firebase (Authentication)
* **Hosting/Deployment:** GitHub Pages
* **Design/UI:** Custom CSS (Mobile-first approach), Google Fonts (Plus Jakarta Sans)

## 🚀 How to Run Locally

1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/starjay88/ASU-Smart-Parking.git](https://github.com/starjay88/ASU-Smart-Parking.git)
