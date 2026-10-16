# 🧠 MindEase – Digital Mental Health and Psychological Support System

**MindEase** is a web-based psychological support and wellness interface designed for educational institutions. It bridges the gap between students seeking confidential mental health guidance and college counsellors, while providing daily self-care tools in a calm, stigma-free digital environment.

---

## ✨ Key Features

### 👨‍🎓 Student Portal
* **No-Forced-Login Landing:** Browse general wellness resources freely before signing in.
* **Role-Based Sign-In:** Email/password login and Google sign-in option with a selector for **Student** or **Counsellor** view.
* **Support Tickets:** Raise support tickets with optional **Urgent** tagging and **Anonymous Mode** (hides identity from the counsellor). The home card dynamically updates to display the latest active ticket.
* **Digital Diary:** Private personal journaling space with a live preview of the most recent entry on the home dashboard, plus pin and delete controls.
* **Visual / Image Space:** Personal gallery to add and view calming images or visual notes.
* **Wellness Hub:** Curated recommendations across **Books, Movies, and Games**, alongside a **Live Clock & Date** block.
* **Ambient Sound:** Built-in browser-generated calming ambient audio that triggers upon login (with a quick mute/unmute toggle in the header).
* **Activity Log & Profile Dashboard:** Track ticket history, diary counts, and saved items, complete with a three-dot menu to **Pin** or **Delete** entries.
* **🚨 Panic / SOS Button:** Instant access to a guided breathing animation, the **Tele-MANAS National Helpline (14416)**, and a one-click **"Alert My Counsellor"** trigger.

### 🧑‍⚕️ Counsellor Portal
* **Ticket Management Queue:** View all incoming student tickets in one organized dashboard (includes a one-click demo ticket loader for presentations).
* **Direct Resolution & Replies:** Respond directly to student queries and mark tickets as resolved.
* **Privacy-First Handling:** Student identities remain strictly masked on anonymous tickets.
* **Queue Controls:** Pin priority cases or delete tickets via the three-dot action menu.

---

## 🛠️ Tech Stack

* **Structure:** HTML5
* **Styling:** CSS3 (Responsive layout, calming color palette, breathing animations)
* **Logic & Interactivity:** Vanilla JavaScript (ES6+)
* **Audio:** Web Audio API (procedural browser-generated calming ambient sound, requiring no external audio files)
* **Data Persistence:** Browser `localStorage` (syncs tickets, diary entries, and gallery items seamlessly between Student and Counsellor views within the same browser)

---

## 🚀 How to Run Locally

No server installation or dependencies are required to run the frontend.

### 1. Clone the Repository
```bash
git clone [https://github.com/your-username/mindease.git](https://github.com/your-username/mindease.git)
cd mindease
