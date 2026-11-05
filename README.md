[github_repository_readme.md](https://github.com/user-attachments/files/34406661/github_repository_readme.md)
# 🌟 Phoenix Chang - Professional Portfolio & Resume Website

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Google Apps Script](https://img.shields.io/badge/Google%20Apps%20Script-4285F4?style=flat&logo=google&logoColor=white)](https://developers.google.com/apps-script)

An elegant, modern, responsive, and feature-packed personal portfolio website built for **Phoenix Chang**. Featuring a single-page interactive layout with Tailwind CSS styling, dark/light theme toggling, custom Web Audio API synthesizer, dynamic category filtering, and direct contact form submission integrated with Google Apps Script (GAS).

---

## ✨ Features

- 🌓 **Light / Dark Mode Toggle**: Smooth theme switching using Tailwind CSS dark class and local storage persistence.
- 🎵 **Built-in Web Audio Synthesizer**: Interactive custom music visualizer and audio player playing ambient tones ("Logistics of Grace") generated dynamically via Web Audio API.
- 🗂️ **Interactive Experience Filter**: Instant filtering of work experience across *Education & Clinic* and *Corporate & Procurement* domains.
- ✉️ **Contact Form Integration**: Fully functional contact form linked directly to a Google Sheet via Google Apps Script (GAS) Web App endpoint.
- 📋 **One-Click Quick Copy**: Instant feedback toast notifications when copying contact information.
- 📱 **Fully Responsive Layout**: Designed with a mobile-first mindset using clean glassmorphism UI elements.

---

## 👤 Profile Overview

**Phoenix Chang** is a dynamic, empathetic bilingual professional (Mandarin / English) with extensive cross-industry experience spanning:
- **Healthcare Operations & Clinical Assistance** (Acupuncture, herbal pharmacy, patient relations)
- **Higher Education Admissions & International Student Support** (Credential evaluation, document translation, event organization)
- **International Logistics & Procurement** (SAP, shipping documentation, customs clearance, vendor negotiations)

### 🎓 Education
- **M.S. in Acupuncture & Oriental Medicine** — South Baylo University (SBU), USA (2022)
- **B.A. in English Language & Literature** — Fu Jen Catholic University, Taiwan (2007)
- **B.A. in Philosophy** — Fu Jen Catholic University, Taiwan (2007)

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, Tailwind CSS (via CDN), Vanilla JavaScript (ES6+)
- **Icons & Fonts**: Font Awesome 6.4, Plus Jakarta Sans, Noto Sans TC
- **Audio Engine**: Native Web Audio API (`AudioContext`, `OscillatorNode`, `GainNode`)
- **Backend / Form Endpoint**: Google Apps Script (GAS) + Google Sheets API

---

## 🚀 Quick Start

Since this portfolio is built as a single, self-contained `index.html` file, no complex build steps or Node.js dependencies are required.

### 1. Local Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/phoenix-chang-portfolio.git
   ```
2. Navigate into the project folder:
   ```bash
   cd phoenix-chang-portfolio
   ```
3. Open `phoenix_chang_resume_portfolio (1).html` (or rename to `index.html`) directly in your browser:
   ```bash
   open index.html  # On macOS
   # or double click the file in File Explorer
   ```

### 2. Form Backend Configuration (Google Apps Script)
To connect the contact form to your own Google Sheet:
1. Create a new Google Sheet.
2. Go to **Extensions > Apps Script** and paste your script handling `doPost(e)`.
3. Deploy as a **Web App** (Execute as: *Me*, Who has access: *Anyone*).
4. Update the `GAS_WEB_APP_URL` variable in the `<script>` section of `index.html`:
   ```javascript
   const GAS_WEB_APP_URL = "YOUR_DEPLOYED_GAS_WEB_APP_URL";
   ```

---

## 🌐 Deployment

### Deploy with GitHub Pages
1. Rename the main HTML file to `index.html`.
2. Push the code to your GitHub repository.
3. Navigate to **Settings > Pages**.
4. Select `main` (or `master`) branch as the source and save.
5. Your portfolio will be live at `https://<your-username>.github.io/<repo-name>/`!

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
