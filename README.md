
<!-- Profile README: albertrw/albertrw -->

<p align="center">
  <img src="https://raw.githubusercontent.com/albertrw/albertrw/main/github-banner.jpg" alt="Albert Abayisenga — Software Developer" width="100%" />
</p>

<h1 align="center">Albert Abayisenga (albertrw)</h1>

<p align="center">
  Software Developer · Graphic Designer · Co-Director at <a href="https://bakamelabs.com">Bakame Labs</a>
</p>

<p align="center">
  <a href="https://bakamelabs.com"><img alt="Bakame Labs" src="https://img.shields.io/badge/Bakame%20Labs-Website-111827?style=for-the-badge"></a>
  <a href="https://albertrw.github.io/albert-portfolio/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-Live-0ea5e9?style=for-the-badge"></a>
  <a href="https://linkedin.com/in/abayisengaalbert"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-2563eb?style=for-the-badge"></a>
  <a href="mailto:abayisengaalbert@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-Contact-ef4444?style=for-the-badge"></a>
</p>

<p align="center">
  <img
    src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=16&pause=1200&center=true&vCenter=true&width=900&lines=Building+modern+web+apps+and+IoT-ready+systems;Real-time+dashboards%2C+secure+APIs%2C+clean+UX;Open+to+collaboration+and+impactful+projects"
    alt="Typing intro"
  />
</p>

---

## About

I build production-ready web apps and IoT systems with a focus on:
- Real-time dashboards, notifications, and live updates
- Clean UI and fast workflows
- Secure, maintainable APIs and databases
- Scalable architecture (device → broker → backend → web)

---

## Featured Project — IoT Dashboard System

**IoT Dashboard System** is a real-time platform for registering devices, ingesting telemetry, controlling components, and monitoring device/component health from a web dashboard.

**What it does**
- Device onboarding with claim tokens and long-lived device secrets
- Telemetry ingestion and latest-state tracking per component
- Live updates to the dashboard via WebSockets
- MQTT-based device communication (telemetry + commands)
- Offline detection and notification flow for devices/components

**Architecture (high level)**

flowchart LR
  D[Device / Firmware] -->|MQTT Telemetry| B[(MQTT Broker)]
  UI[Web Dashboard] <-->|WebSocket| API[Backend API]
  API -->|Subscribe/Publish| B
  API --> DB[(Database)]
  UI -->|REST| API


**Tech Stack**
- Dashboard: React, TypeScript, Vite, Tailwind CSS
- Backend: Node.js, Express, TypeScript
- Realtime: MQTT, WebSockets
- Database: PostgreSQL

Repository: https://github.com/albertrw/iot-dashboard

---

## Featured Project — Digital Menu System

**Digital Menu** is a responsive web application for restaurants and lodges. Guests can browse items, view details, and place orders digitally to improve service speed and experience.

**Highlights**
- Menu browsing with images and item details
- Filtering and sorting by name and price
- Admin dashboard (CRUD) for menu and services
- Export to PDF/CSV
- AJAX-powered updates without page reload
- Mobile-ready UI

**Tech Stack**
- Frontend: EJS, Tailwind CSS, JavaScript
- Backend: Node.js, Express.js
- Database: MySQL

Repository: https://github.com/albertrw/digital-menu-system  
Demo: https://bakamelabs.com/project/5

---

## Toolbox

<p>
  <img src="https://skillicons.dev/icons?i=js,ts,nodejs,express,react,tailwind,postgres,mysql,sqlite,flutter,php,python,git,figma&perline=7" alt="Skills" />
</p>

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=albertrw&show_icons=true&hide_title=true&theme=tokyonight" height="160" alt="GitHub stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=albertrw&theme=tokyonight" height="160" alt="GitHub streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=albertrw&theme=tokyo-night&hide_border=true" alt="Activity graph" />
</p>

---

## Contact

Portfolio: https://albertrw.github.io/albert-portfolio/  
Email: abayisengaalbert@gmail.com  
Phone/WhatsApp: +250 792 044 484  
LinkedIn: https://linkedin.com/in/abayisengaalbert  
Instagram: https://www.instagram.com/derekpro_/

---

<p align="center">
  <i>Building technology that makes daily experiences smarter and smoother.</i>
</p>
