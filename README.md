# 🛰️ URRT Task Board

**Mission-critical task management for the UIU Rescue Rover Team.**

![URRT Task Board](URRT_About_Logo.png)

The **URRT Task Board** is a specialized, lightweight management tool designed for engineering and robotics teams. It provides a centralized dashboard for tracking subteam progress, managing deadlines, and ensuring team-wide synchronization through an industrial-grade interface.

---

## 🚀 Key Features

### 🔐 Secure Access Control
*   **Universal Join Code**: Protects the team space. Only members with the code can view the board.
*   **Multi-Lead Management**: Support for multiple Team Lead accounts with independent credentials.
*   **Registration Toggle**: Existing Leads can enable or disable new admin registrations for maximum security.

### 🚨 Dynamic Alert Ticker
*   **Continuous Awareness**: A sliding sidebar ticker that auto-cycles through critical and overdue tasks.
*   **Motivation Engine**: Integrated meme GIFs and personalized "bonk" messages to keep the team focused.
*   **Real-time Progress**: Each alert card features a dynamic progress bar for visual tracking.

### 📋 Management & Audit
*   **Activity Log**: A full audit trail tracking every task addition, modification, and deletion.
*   **Subteam Organization**: Segregate tasks into specialized subteams (Software, Mechanical, Electrical, etc.).
*   **Deadline Tracking**: Visual badges for overdue, upcoming, and completed tasks.

---

## 🛠️ How to Use

### For Team Members
1.  Navigate to the deployed URL.
2.  Enter the **Team Join Code** provided by your Lead.
3.  View the real-time status of all subteam tasks and upcoming alerts.

### For Team Leads
1.  Click **"Login as Team Lead"** on the join screen.
2.  **First Time?** Register your account (if registrations are enabled).
3.  Once logged in:
    *   Add or remove subteams.
    *   Configure tasks, assign owners, and set deadlines.
    *   Manage team settings (Logo, Name, Join Code).
    *   Monitor the **Activity Log** to see who changed what.

---

## 📦 Deployment

This tool is a single-file application (`index.html`), making it perfect for **GitHub Pages**.

1.  Push the code to a GitHub repository.
2.  Go to **Settings** > **Pages**.
3.  Select the `main` branch and `/root` folder.
4.  Your dashboard is live!

*Note: Data is currently stored in the browser's LocalStorage. For cross-device real-time syncing, consider integrating a Firebase backend.*

---

## 💻 Tech Stack
*   **Frontend**: Pure HTML5, CSS3 (Custom Variables), Vanilla JavaScript.
*   **Fonts**: Inter, DM Mono (Google Fonts).
*   **Icons**: Native Emojis.
*   **Storage**: Browser LocalStorage / SessionStorage.

---

## 🤝 Credits
Developed for the **UIU Rescue Rover Team (#URRT)**. 
Developed by Athin 
Visit us at [rescuerover.uiu.ac.bd](http://rescuerover.uiu.ac.bd)

---
*Version 2.0 · Built for the mission.*
