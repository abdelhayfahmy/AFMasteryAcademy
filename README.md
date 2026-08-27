# 🏛️ AF Mastery Academy — Executive Learning Platform

[![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-blue?style=flat-square&logo=github)](https://abdelhayfahmy.github.io/)
[![Tailwind CSS](https://img.shields.io/badge/Styling-Tailwind%20CSS-38B2AC?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)
[![Google Apps Script](https://img.shields.io/badge/Backend-Google%20Apps%20Script-4285F4?style=flat-square&logo=google)](https://developers.google.com/apps-script)
[![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-gold?style=flat-square)](#)

An elite, high-performance web platform designed for executive professionals, corporate leaders, and commercial negotiators. Built with a luxury Obsidian & Gold design system, client-side access control, dynamic course management, and real-time Google Sheets telemetry.

---

## 🌟 Key Features

* **💎 Luxury Executive Aesthetic:** Crafted with Tailwind CSS, custom obsidian surfaces, gold gradient accents, and refined typography (*Cinzel*, *Cormorant Garamond*, *Plus Jakarta Sans*).
* **🔒 Course Gatekeeping & Access Control:** All masterclasses are locked until the student registers or logs in with their unique Credential ID.
* **⚡ Automatic Credential Issuance:** Upon registration with email and mobile/WhatsApp, a unique Cryptographic Credential (`AF-XXXXXX`) is generated and dispatched directly to the student's email.
* **📊 Google Sheets & Email Webhook:** Fully integrated with Google Apps Script (`doGet` pipeline) to synchronize registrations into Google Sheets and trigger automated notifications.
* **🖥️ Immersive Fullscreen Masterclass Player:** Distraction-free iframe player with reload and exit capabilities.
* **🛡️ Author / Instructor Studio:** Password-protected portal allowing the instructor to publish, manage, and delete courses dynamically stored in `localStorage`.
* **🔑 Credential Recovery System:** Integrated "Forgot Credential" service that automatically looks up the student's ID and dispatches it to their inbox.

---

## 🚀 Live Masterclass Modules

* **Platform URL:** [AF Mastery Academy](https://abdelhayfahmy.github.io/)
* **Integrated Masterclasses:**
  * **CLOSE Sales Mastery:** [Launch Module](https://abdelhayfahmy.github.io/CLOSE-SalesMastery/)
  * **Problem Solving Mastery:** [Launch Module](https://abdelhayfahmy.github.io/problem-solving-module/)

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, Tailwind CSS (CDN), Vanilla JavaScript (ES6+)
* **Typography:** Google Fonts (`Cinzel`, `Cormorant Garamond`, `Plus Jakarta Sans`)
* **Icons & Effects:** Font Awesome 6.4.0, Canvas Confetti
* **Backend & Telemetry:** Google Apps Script (Web App Endpoint), Google Sheets API, MailApp
* **Hosting:** GitHub Pages

---

## 📂 Project Structure

```text
├── index.html                  # Main academy portal & interactive logic
├── image_84ed9b.png            # Executive instructor portrait
└── README.md                   # Project documentation
