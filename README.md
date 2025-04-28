
Focus Flow - Chrome Extension

Focus Flow is a Chrome extension designed to help users manage their time effectively and boost productivity. It leverages proven techniques like the Pomodoro Technique, blocking distracting websites, setting task reminders, and organizing schedules — helping users stay focused and achieve more.

---

Features

- Pomodoro Timer  
  Work in focused intervals (default 25 minutes) followed by short breaks. Customizable durations to suit individual preferences.

- Focus Mode  
  Detects and blocks distracting websites (e.g., YouTube, Instagram, Netflix). Alerts users and redirects to a blank page when they try to access these sites.

- Task Reminders  
  Set customizable alerts to stay on top of tasks and deadlines with quick and easy scheduling.

- Timetable Manager  
  Organize daily tasks with notes, timings, and priorities. A simple and efficient way to plan your workday.

- Background Functionality  
  The Pomodoro Timer and notifications work seamlessly even when the extension window is closed.

---
Technical Architecture

- manifest.json: Defines extension metadata, permissions (storage, alarms, notifications, active tab), and script configurations.
- background.js: Manages background processes like alarms, notifications, and timer management.
- contentScript.js: Monitors active tabs, handles website blocking, and activates focus mode.
- index.html / styles.css: Provides the user interface components for the Pomodoro timer, reminders, and timetable features.

How to Install

1. Download or clone this repository.
2. Open Chrome and navigate to `chrome://extensions/`.
3. Enable **Developer Mode**.
4. Click **Load unpacked** and select the project directory.
5. Start using Focus Flow to stay productive!

---
 Stay Focused. Stay Productive. 


