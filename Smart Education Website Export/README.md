# Smart Education Website & Portals

The official web platform and portal system for **Smart Education Computer Centre**, located in Kanyapur, Asansol. This project provides coaching information (Class I-XII, NEET & JEE preparation), professional job-ready computer courses, and portal access dashboards for Students, Teachers, and Administrators.

---

## 🌟 Features

- **Multi-Role Portals:** Custom user interfaces designed specifically for:
  - **Students (`student.html`):** Access to classes, marks, profiles, and fee schedules.
  - **Teachers (`teacher.html`):** Management tools for student lists, progress tracking, and attendance.
  - **Administrators (`admin.html`):** Management panel for overseeing center operations, metrics, and accounts.
- **Multilingual Support (`translate.js`):** Built-in support for **English**, **Bengali (বাংলা)**, and **Hindi (हिन्दी)** using a custom-styled wrapper around the Google Translate widget that persists preferences site-wide via cookies.
- **Theme System (`theme.js`):** Support for dark/light mode toggle with seamless state persistence.
- **Modern UI & Aesthetic:** Built with premium typography (Zodiak & General Sans), grain overlay texture, self-drawing hand-drawn underlines for emphasis, and smooth double-bezel layouts.
- **Responsive Layouts:** Designed to adapt beautifully to desktops, tablets, and mobile devices.

---

## 🛠️ Technology Stack

- **Core:** HTML5, CSS3 (Vanilla), and JavaScript (ES6+).
- **Typography:** General Sans (Sans-serif) & Zodiak (Serif) via Fontshare.
- **Icons:** SVG assets (housed in `icon.svg` / assets).
- **Localization:** Google Translate API Widget integration.

---

## 📁 Repository Structure

```text
├── index.html            # Main home page for Smart Education Centre
├── login.html            # Unified portal authentication page
├── accounts.html         # Accounts portal page
├── student.html          # Student dashboard & profile portal
├── teacher.html          # Teacher panel & student management portal
├── admin.html            # Admin dashboard for operational metrics
├── 404.html              # Custom elegant 404 page
├── portal.js             # Shared behaviors for dashboards & rails
├── translate.js          # Client-side English/Bengali/Hindi translation engine
├── theme.js              # Site-wide dark & light theme management
├── portal.css            # Layout styles for dashboard & UI tokens
├── manifest.webmanifest  # Progressive web app (PWA) configuration
├── icon.svg              # Core icon SVG asset
└── assets/               # Local images, logos, and stylesheets
```

---

## 🚀 Local Development Setup

Since this is a client-side static web application, it does not require a complex build process. You can run it locally using any static web server:

### Option A: VS Code Live Server (Easiest)
1. Open this workspace in **VS Code**.
2. Install the **Live Server** extension.
3. Click the **Go Live** button at the bottom-right of the window.

### Option B: Python Local Server
If you have Python installed, run this command in your terminal:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000` in your browser.

### Option C: Node.js (serve)
If you have Node.js installed, run:
```bash
npx serve .
```
Then visit `http://localhost:3000` in your browser.

---

## 🛡️ License

This project is proprietary. All rights reserved.
