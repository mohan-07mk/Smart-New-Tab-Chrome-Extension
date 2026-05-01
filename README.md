# 🚀 Smart New Tab Chrome Extension

Smart New Tab is a customizable Chrome extension that replaces the default new tab page with a smart productivity dashboard.  
It provides useful tools like clock, weather, timer, to-do list, reminders, and analytics in one place to improve daily productivity.

---

## ✨ Features

- 🕐 Real-time Clock and Date
- 🌤️ Live Weather Updates
- 🍅 Pomodoro Focus Timer
- ⏱️ Timer and Stopwatch
- ✅ To-Do List Manager
- 💧 Water Reminder Notifications
- 📊 Usage Analytics Dashboard
- 🔗 Custom Shortcuts
- 🎨 Multiple Themes and Personalization
- 🎯 Drag and Drop Widgets
- 🔔 Browser Notifications

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Chrome Extension APIs (Manifest V3)
- Chart.js
- OpenWeatherMap API

---

## 📦 Installation Guide

Follow these steps to install the extension manually:

1. Download the ZIP file from the GitHub repository
2. Extract the ZIP file
3. Open Google Chrome
4. Go to:
5. Enable **Developer Mode**
6. Click **Load Unpacked**
7. Select the extracted project folder

The extension will be installed successfully.

---

## 📁 Project Structure
smart-new-tab-extension/
│
├── manifest.json              # Chrome Extension config (Manifest V3)
├── newtab.html                # Main dashboard page (475 lines)
├── background.js              # Service worker (analytics tracking, alarms)
│
├── css/
│   ├── main.css               # Core layout, typography, and base styles
│   ├── themes.css             # Theme definitions (dark, light, ocean, etc.)
│   ├── widgets.css            # Widget-specific styles
│   └── animations.css         # Keyframe animations & transitions
│
├── js/
│   ├── app.js                 # Main app initialization & bootstrapping
│   ├── storage.js             # Chrome storage abstraction layer
│   ├── themes.js              # Theme switching & custom color logic
│   ├── clock.js               # Clock widget logic
│   ├── weather.js             # Weather widget + API integration
│   ├── pomodoro.js            # Pomodoro timer logic
│   ├── timer.js               # Timer/Stopwatch widget logic
│   ├── todo.js                # To-Do list widget logic
│   ├── water.js               # Water reminder widget logic
│   ├── search.js              # Smart search bar + suggestions
│   ├── shortcuts.js           # Custom shortcuts management
│   ├── aitools.js             # AI tools hub management
│   ├── googlehub.js           # Google services hub
│   ├── analytics.js           # Usage analytics + Chart.js integration
│   ├── notifications.js       # Browser & toast notifications
│   ├── widgets.js             # Widget toggle, drag-and-drop, visibility
│   └── settings.js            # Settings panel logic & data management
│
├── lib/
│   └── chart.min.js           # Chart.js library (data visualization)
│
└── assets/
    └── icons/
        ├── icon16.png         # Extension icon (16×16)
        ├── icon48.png         # Extension icon (48×48)
        └── icon128.png        # Extension icon (128×128)



---

## 🎯 Purpose of the Project

This project was developed to:

- Improve productivity
- Practice Chrome extension development
- Learn JavaScript modular architecture
- Build a real-world project for portfolio and GitHub
- Enhance frontend and API integration skills

---

## 🔮 Future Improvements

- More widgets and productivity tools
- Better UI customization options
- Performance optimization
- Additional analytics features

---

## 👨‍💻 Author

**Mohan Kumar**  
Electronics and Communication Engineering (ECE) Student  
Passionate about Electronics, Programming, and Innovation

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and share your feedback!
