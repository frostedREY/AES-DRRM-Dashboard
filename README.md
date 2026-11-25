# AES-DRRM Dashboard

> Automated Emergency System - Disaster Risk Reduction and Management Dashboard for Philippine Schools

AES-DRRM Dashboard is a real-time School Disaster Risk Reduction and Management (SDRRM) information system designed to enhance school preparedness, situational awareness, emergency communication, and disaster education.

Unlike traditional information boards that only display announcements, AES-DRRM Dashboard integrates live hazard monitoring, school status management, emergency information dissemination, DRRM awareness campaigns, and educational content into a single platform.

The system is specifically designed for Philippine schools and supports school administrators, SDRRM coordinators, teachers, learners, and stakeholders by providing critical information before, during, and after disaster-related events.

---

## 🎯 Project Objectives

- Improve disaster preparedness and response capabilities in schools.
- Increase access to real-time hazard and environmental information.
- Provide a centralized platform for DRRM announcements and advisories.
- Support informed decision-making during emergencies.
- Promote disaster awareness through continuous educational content.
- Enhance school resilience using low-cost digital technologies.

---

# ✨ Key Features

## 🌦 Real-Time Weather Monitoring

Displays live weather information including:

- Temperature
- Humidity
- Wind Speed
- Rain Probability
- Visibility
- UV Index
- Air Pressure
- Dew Point
- Cloud Cover
- Sunrise and Sunset

The dashboard also generates easy-to-understand weather summaries that help users quickly assess environmental conditions.

---

## 🌫 Air Quality Monitoring

Provides real-time Air Quality Index (AQI) information including:

- AQI Level
- PM2.5 Concentration
- Air Quality Status Classification
- Health-Based Recommendations

This feature helps schools decide when outdoor activities may need adjustment due to unhealthy air conditions.

---

## 🌪 Philippine Area of Responsibility (PAR) Monitoring

Monitors weather systems affecting the Philippines, including:

- Tropical Cyclones
- Low Pressure Areas (LPA)
- Intertropical Convergence Zone (ITCZ)

This feature allows school communities to stay informed about hazards that may affect school operations.

---

## 🌍 Earthquake Monitoring

Automatically retrieves and displays:

- Latest Earthquake Events
- Magnitude
- Location
- Depth
- Event Time

The dashboard continuously evaluates nearby seismic events and highlights earthquakes with potential impacts on school operations.

---

## 🚨 Automated School Status Engine

One of the unique features of AES-DRRM Dashboard is its ability to translate hazard information into actionable school status indicators.

### Available Status Levels

| Status | Meaning |
|----------|----------|
| ✅ NORMAL | Regular operations |
| ⚠️ MONITORING | Potential hazard detected |
| 🟠 SUSPENDED | Classes officially suspended |
| 🔴 EMERGENCY | Active emergency situation |

The system can automatically recommend a status based on monitored hazard conditions while still allowing manual administrator overrides.

---

## 📢 School Announcement Center

Allows schools to publish:

- Daily Announcements
- Emergency Advisories
- Upcoming Events
- School Notices

Updates can be deployed remotely through simple JSON files hosted on GitHub, eliminating the need for a dedicated server.

---

## 🖼 Emergency Information Takeover Mode

A unique awareness feature that transforms the dashboard into a digital DRRM information board.

The system can periodically display:

- Evacuation Maps
- Emergency Procedures
- Disaster Preparedness Posters
- Safety Advisories
- Awareness Campaign Materials

This enables continuous passive DRRM education for learners and visitors.

---

## 🎥 DRRM Educational Video Rotation

The dashboard automatically plays disaster preparedness and safety videos covering topics such as:

- Earthquake Preparedness
- Fire Safety
- Flood Safety
- Emergency Preparedness
- CPR and First Aid
- Emergency Survival Skills

This feature supports continuous disaster risk awareness within the school community.

---

## 📱 Hidden Administrative Console

Authorized users can access administration features through a long-press interface.

Administrative functions include:

- School Status Management
- Announcement Management
- Emergency Overrides
- Import and Export Configuration
- Image Rotation Management

This allows public displays to remain secure while providing easy administration.

---

# 🏫 Intended Users

- School Heads
- SDRRM Coordinators
- Teachers
- Learners
- Parents and Guardians
- Local Government Units
- Disaster Response Agencies

---

# 🛠 Technology Stack

### Frontend

- HTML5
- CSS3
- Vanilla JavaScript

### APIs and Data Sources

- Open-Meteo Weather API
- Open-Meteo Air Quality API
- USGS Earthquake API
- PAGASA-Based PAR Monitoring Data
- YouTube Embedded Player API

### Hosting

- GitHub Pages
- GitHub Raw JSON Configuration Files

---

# 🚀 Deployment

### Clone Repository

```bash
git clone https://github.com/frostedREY/AES-DRRM-Dashboard.git
```

### Open Dashboard

Simply open:

```text
index.html
```

or deploy through:

- GitHub Pages
- Netlify
- Vercel
- Any Static Web Server

---

# 📂 Project Structure

```text
AES-DRRM-Dashboard/
│
├── index.html
├── announcement.json
├── school_status.json
├── par_status.json
│
├── images/
│   ├── evac-map.png
│   ├── fire-drill.jpg
│   ├── earthquake-drill.jpg
│   ├── dengue-advisory.jpg
│   └── typhoon-safety.jpg
│
└── README.md
```

---

# 💡 Innovation Highlights

✅ Integrates multiple DRRM information sources into a single interface

✅ Designed specifically for Philippine school settings

✅ Uses free and publicly available hazard monitoring services

✅ Supports low-cost deployment on TVs, monitors, and school display systems

✅ Combines monitoring, awareness, communication, and preparedness functions

✅ Works without requiring expensive server infrastructure

✅ Promotes proactive rather than reactive disaster management

---

# 🌱 Future Development

Planned enhancements include:

- SMS Alert Integration
- Telegram Notifications
- School-Wide Public Alert System
- PAGASA Automatic Feed Integration
- PHIVOLCS Integration
- GIS Hazard Mapping
- Student Attendance and Accountability Module
- Visitor Emergency Information Kiosk Mode
- IoT Sensor Integration (ESP32-Based Monitoring Devices)

---

# 📈 Potential Impact

AES-DRRM Dashboard supports the digital transformation of School Disaster Risk Reduction and Management by helping schools:

- Improve preparedness
- Strengthen emergency communication
- Increase disaster awareness
- Support evidence-based decisions
- Enhance overall school resilience

---

# 👨‍🏫 Author

**Reynaldo Apas**  
Teacher I  
Department of Education - Region VIII  
Antipolo Elementary School

GitHub: https://github.com/frostedREY

---

# 🤝 Contributions

Contributions, feature suggestions, and improvement proposals are welcome.

If you would like to contribute, feel free to submit an issue or pull request.

---

# 📜 License

This project is licensed under the MIT License.

Feel free to use, modify, and adapt the project for educational and disaster preparedness purposes.
