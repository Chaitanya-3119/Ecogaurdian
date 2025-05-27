# Ecogaurdian
A centralized and user-friendly web platform that empowers citizens to actively participate in environmental protection through real-time reporting, air quality monitoring, community engagement, and incentivized contributions, ultimately fostering a cleaner and more sustainable urban environment .


# EcoGuardian 🌿

**Empowering Community-Driven Environmental Action**

EcoGuardian is a real-time environmental action web platform that enables citizens to report pollution issues, track air quality, participate in clean-up events, and earn eco rewards — all in one centralized, user-friendly interface.

---

## 🌍 Problem Statement

Urban areas suffer from waste mismanagement, air pollution, and river contamination due to a lack of citizen engagement and transparent reporting systems. Traditional grievance platforms are slow, fragmented, and do not incentivize participation. EcoGuardian addresses this by providing a real-time, community-centric solution for reporting and managing environmental issues.

---

## ✅ Key Features

- **Environmental Complaint Reporting**  
  Users can submit reports with descriptions, location pins, and photos for issues like waste accumulation, river pollution, and air quality concerns.

- **Real-Time AQI Monitoring**  
  Integrated with AQICN API to display live AQI values for PM2.5, PM10, CO, O₃, etc., across Indian cities using a clean, color-coded UI.

- **Gamified Rewards System**  
  Earn Eco Points for every contribution — reporting issues, attending clean-up drives, or raising awareness. Points are redeemable for rewards.

- **Leaderboard**  
  A live scoreboard displaying top contributors, encouraging friendly competition and engagement.

- **Community Clean-Up Drives**  
  Users can organize or join pollution clean-up events. Each event includes time, location, and organizer details.

- **User Dashboard**  
  Track your contributions, rewards, and event history through a personalized profile.

---

## 🧰 Tech Stack

| Layer        | Technologies Used           |
|--------------|------------------------------|
| **Frontend** | HTML5, CSS3, JavaScript      |
| **Backend**  | PHP (for form handling, login/registration) |
| **Database** | MongoDB                      |
| **API**      | AQICN (Air Quality Data)     |

---

## 📁 Project Structure

EcoGuardian/
│
├── index.html # Homepage
├── login.html # Login Page
├── signup.html # Registration Page
├── aqi.html # AQI Visualizer
├── complaint.html # Pollution Reporting Form
├── events.html # Clean-Up Event Listings
├── leaderboard.html # Top Contributor Scores
├── rewards.html # Eco Point Reward System
│
├── style.css # Global Styles
├── script.js # JS Logic and Interactivity
│
├── connect.php # DB Connection
├── register.php # Registration Logic
├── login.php # Login Logic
├── submit_complaint.php # Store Complaint
│
└── assets/ # Images, Icons, Animations


