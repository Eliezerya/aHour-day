# Synchronic - Custom Interval & Session Timer
**Synchronic** is a modern, responsive, and completely self-contained web-based custom interval timer. Built with a sleek glassmorphic aesthetic, it allows users to customize, sequence, and manage their productivity sessions (such as study, coding, or Duolingo) alongside break times.
---
## ✨ Features
- **Custom Session Queues**: Add, edit, delete, and jump directly between custom timer sessions. Define custom names, durations (minutes and seconds), and session types (Work/Study or Break).
- **Premium Glassmorphic Design**: Features a highly aesthetic design system with modern typography (`Outfit` and `Share Tech Mono`), vibrant gradients, subtle glow animations, and responsive CSS grid layout.
- **Web Audio API Synth Engine**: Generates audio alarms dynamically in the browser (Digital Beeps, Relaxing Chime, Sci-Fi Pulse, Simple Sine Wave). Completely self-contained with no external audio file dependencies.
- **Accuracy & Drift Protection**: Prevents browser background tab throttling from desynchronizing the timer using system clock timestamps (`Date.now()`) and the Page Visibility API.
- **LocalStorage Persistence**: Automatically saves your session list, volume settings, active alarm sound, and auto-start preference directly to the browser.
- **Fully Responsive**: Looks stunning on both desktop and mobile screens.
---
## 🛠️ Technology Stack
- **Structure**: Semantic HTML5
- **Styling**: Vanilla CSS3 (Custom Variables, Backdrop Blur, SVG Circular Progress, CSS Keyframe Animations)
- **Logic**: Pure Client-Side JavaScript (Web Audio API, LocalStorage, Page Visibility API)
---
## 🚀 Getting Started
Since **Synchronic** is a static web application, there is no installation or build step required.
1. Clone or download this repository.
2. Open [index.html](index.html) directly in any modern web browser (Chrome, Firefox, Safari, Edge).
3. Start configuring your interval sequence and boost your productivity!
---
## 📖 How to Use
1. **Start/Pause**: Click the **Mulai** (Start) / **Jeda** (Pause) button.
2. **Manage Sessions**:
   - Add sessions using the **Tambah Sesi Baru** form at the bottom right.
   - Edit an existing session by clicking the edit icon (pencil) or delete it with the trash icon.
   - Click directly on any session item in the list to jump to that session.
3. **Sound Settings**:
   - Change the alarm sound using the dropdown menu.
   - Adjust the alarm volume with the slider and test it with the **Test Suara** button.
   - Toggle **Mulai Sesi Otomatis** (Auto-start next session) to automatically transition from work to break without manual intervention.
---
## 🌐 Localization
- The application interface is designed in **Indonesian** (Bahasa Indonesia).
