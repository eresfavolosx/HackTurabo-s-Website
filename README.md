# HackTurabo 2016 — Collegiate Hackathon Web Platform & Server

[![Event](https://img.shields.io/badge/Event-HackTurabo_2016-FF5722?style=flat-square)](https://novu.works)
[![University](https://img.shields.io/badge/Host-Universidad_del_Turabo-002D62?style=flat-square)](https://ut.suagm.edu/)
[![Node.js](https://img.shields.io/badge/Node.js-Express-339933?style=flat-square&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Firebase](https://img.shields.io/badge/Firebase-Hosting%20%26%20Database-FFCA28?style=flat-square&logo=firebase&logoColor=black)](https://firebase.google.com/)
[![Material Design](https://img.shields.io/badge/UI-Bootstrap%20%26%20MDL-00BCD4?style=flat-square)](https://getmdl.io/)

> **Collegiate Hackathon Initiative:** HackTurabo was one of the premier collegiate hackathons organized at Universidad del Turabo (Puerto Rico), gathering student developers, designers, and innovators to build rapid prototypes solving pressing civic, commercial, and educational challenges.

---

## 📖 Background & Stanford UIF Initiative

As part of the **Stanford University Innovation Fellows (UIF)** movement to foster campus entrepreneurship and technical innovation in Puerto Rico, this web platform served as the official landing page, participant registration engine, challenge tracker, and sponsor showcase for HackTurabo 2016.

---

## 🛠️ Architecture & Tech Stack

- **Server:** Node.js & Express (`index.js`), configured for both local execution and multi-environment deployment (Heroku `Procfile` and Firebase Hosting).
- **Client Frontend:** Responsive Material Design layout powered by Material Design Lite (MDL), Bootstrap Material Design, and Google Material Icons.
- **Data & Registration:** Firebase Realtime Database integration for real-time attendee intake, team formations, and judging schedules.

---

## 📂 Project Structure

```
HackTurabo-s-Website/
├── index.js               # Node.js Express static server
├── Procfile               # Cloud deployment process definition
├── firebase.json          # Firebase Hosting configuration
├── database.rules.json    # Realtime Database security rules
├── package.json           # Node.js dependencies
└── public/
    ├── index.html         # Hackathon landing page, schedule & sponsors
    ├── 404.html           # Custom fallback page
    ├── Pages/             # Track guidelines, rules, and rubric subpages
    └── assets/            # CSS stylesheets, branding, icons, and JavaScript
```

---

## 🚀 Running Locally

```bash
# Clone the repository
git clone https://github.com/eresfavolosx/HackTurabo-s-Website.git
cd HackTurabo-s-Website

# Install dependencies
npm install

# Start the Express server
npm start
# Server will listen on http://localhost:3000
```

Alternatively, serve the static directory:

```bash
cd public
python3 -m http.server 8080
# Open http://localhost:8080
```

---

## 👨‍💻 Event Organizer & Lead Developer

**Fabián Vélez Vicente**  
- Portfolio: [novu.works](https://novu.works)  
- GitHub: [@eresfavolosx](https://github.com/eresfavolosx)  
- LinkedIn: [Fabián Vélez Vicente](https://www.linkedin.com/in/fabian-velez-vicente/)
