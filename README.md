# 💡 WizBulb Remote

Hey there! 👋 Welcome to my DIY Smart Home project. I've built a custom ecosystem to control my lights, bridging the gap between a modern web interface and physical hardware.

Check out the live project here: https://itswaferz.github.io/wiz-bulb-remote/

### 🏠 What’s this about?
The goal was to have full, seamless control over my lighting system through two synchronized channels:
1.  **The Web App:** A clean, responsive dashboard to toggle lights from any device.
2.  **The Physical Switch:** A **Shelly BLU Button 4**, which I programmed with 4 custom functions for tactile, multi-action control.

The "brain" of the operation is an **Arduino** (acting as the central controller). It listens for commands from the React frontend and simultaneously receives signals from the Shelly switch to update the bulb's state in real-time.

---

### 🛠️ Tech Stack
* **Frontend:** `React.js` (State management, Hooks, Responsive UI).
* **Hardware/Backend:** `Arduino / C++` (Managing system logic and device communication).
* **Connectivity:** `Wi-Fi / Bluetooth` (Handling the Shelly BLU 4 integration and frontend communication).

---

### ✅ Project Status
This project is **fully complete and operational**:

- [x] **Frontend:** The React web application is polished, responsive, and fully functional.
- [x] **Backend & Hardware:** Arduino logic successfully handles concurrent signal processing from both the web app and the Shelly BLU 4 switch with zero latency.
- [x] **Live Sync:** Real-time updates ensure the web dashboard, the physical switch inputs, and the smart bulbs are always perfectly perfectly in sync.

---

### 🤝 Contributing
Feel free to poke around the code! If you have any suggestions on how to further optimize the hardware-software synchronization or if you've done something similar, I’d love to hear from you. 🍻
