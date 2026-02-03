# Smart Water Quality Monitoring & Disease Risk Prediction System

A premium, multilingual, IoT-ready web dashboard designed to monitor water quality, evaluate safety levels, and provide intelligent health risk insights through a clean and user-friendly interface. This project demonstrates how modern web technologies, analytics, and intuitive design can be combined to build a scalable smart water monitoring solution for public and smart-city environments.

---

## 🌊 Overview
The Smart Water Quality Monitoring & Disease Risk Prediction System helps users track essential water parameters in real time, visualize trends, and understand potential risks based on sensor indicators. The interface is designed for non-technical users while maintaining a professional, government-grade visual experience.

---

## ✨ Features

### User Roles
- **Smart User**
  - Connect IoT/Bluetooth devices (supported browsers)
  - View personal sensor data
  - Access district water data

- **Standard User**
  - Read-only access to district water quality
  - View analytics and map data

---

### Water Quality Monitoring
- pH Level  
- Temperature (°C)  
- Turbidity (NTU)  
- TDS (ppm)

---

### Risk & Disease Insight
- Safety Status Levels: **Safe / Low Risk / High Risk / Critical**
- Rule-based intelligent prediction
- Recommended precautionary actions
- No unnecessary alerts when water is safe

---

### Interactive Map
- Displays nearby water tanks and district water bodies
- Custom water-tank markers
- Mini water reports on click

---

### Analytics Dashboard
- Historical parameter charts
- Risk trend visualization
- Clear indication of data source (IoT / Manual)

---

### Multilingual Support
- English
- Tamil
- Hindi
- Instant language switching without page reload
- JSON-based i18n system

---

### UI / UX Highlights
- Aqua water-themed background
- Smooth animations and transitions
- Clean card-based layout
- Responsive design
- Large readable typography
- Designed for accessibility and clarity

---

## 🛠️ Tech Stack
- **Frontend:** React / Next.js  
- **Language:** TypeScript  
- **Styling:** Tailwind CSS  
- **Animations:** Framer Motion  
- **Charts:** Recharts / Chart.js  
- **Maps:** Leaflet / Google Maps  
- **Internationalization:** i18n JSON  
- **IoT Ready:** WebSocket / MQTT architecture ready

---

---

## 🚀 Purpose
This project showcases a scalable approach to smart water monitoring suitable for hackathons, research prototypes, municipalities, and educational demonstrations.

---

<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/drive/1BtO3p1vBEseZuFkG7GG9uh1G8W1jj4P9

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`
