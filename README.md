# 🌐 NODE: SUSTAIN 
### *The Decentralized RFID Identity Hub*

**"Repurposing yesterday's e-waste for tomorrow's decentralized identity."**

---

## 🚀 The Hook: Fighting Planned Obsolescence
Every year, millions of networking devices are discarded as "e-waste" because they are deemed obsolete. **NODE: SUSTAIN** is a **Science, Technology, and Society (STS)** initiative that rejects this cycle. 

By modifying a discarded **Smart Bro Pocket Wi-Fi** and bridging it with an Arduino-based RFID edge, we have created a private, air-gapped "Ghost Network." We aren't just building a system; we are demonstrating **Digital Resilience**—proving that "trash" can power secure, private infrastructure.

### What does S.U.S.T.A.I.N. mean?
* **S**ustainable: Repurposing discarded hardware to reduce environmental impact.
* **U**niversal: Accessible by any device with a browser within the local node.
* **S**tudent: Specifically engineered for campus-level identity management.
* **T**racking & **A**uthentication: Seamless real-time logging via RFID.
* **I**dentity **N**etwork: A decentralized, off-grid infrastructure.

---

## 🛠️ Technical Architecture
The system bridges physical hardware interrupts with modern web protocols to create a zero-latency sync between the physical scan and the digital dashboard.

| Component | Technology | Role |
| :--- | :--- | :--- |
| **Hardware** | Arduino Uno R3 + MFRC522 | RFID Data Capture (The Edge) |
| **Edge Feedback** | LCD1602A (I2C) | Instant Visual Confirmation |
| **Networking** | Smart Bro Pocket Wi-Fi | Private Intranet / DHCP Gateway |
| **Backend** | Python (Flask & WebSockets) | Real-time Serial Bridge |
| **Database** | Google Sheets API | Cloud Data Persistence |

---

## 👥 The Development Team
* **Jairus Meneses (Technical Lead):** Systems Architecture, Backend Bridge (Flask/WebSockets), & Network Infrastructure.
* **Sigi (Project Manager):** Project Coordination, Arduino Firmware, & AppScript Database Management.
* **[Friend 1] (Frontend Developer):** HTML Structure & UI Data Mapping.
* **[Friend 2] (UI/UX Designer):** Minimalist Aesthetics & Responsive CSS.

---

## ♻️ STS & Sustainability Impact
1. **E-Waste Sustainability:** Extending the functional lifecycle of consumer electronics.
2. **Digital Resilience:** Creating modular tech that thrives in "dead zones" or network outages.
3. **Data Sovereignty:** Keeping student data within a private, localized radius to prevent third-party tracking.

---

## 🚦 Quick Start
1. **Hardware:** Flash the `main.ino` sketch to the Arduino.
2. **Network:** Connect your host machine and clients to the **Smart Bro Wi-Fi**.
3. **Install:** `pip install -r requirements.txt`.
4. **Launch:** `python server/app.py`.
5. **Access:** Navigate to `http://[Your-IP]:5000` on any device in the network.

> **Security Note:** The `credentials.json` file for the Google Sheets API is excluded via `.gitignore` to protect private API keys.

---

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.
