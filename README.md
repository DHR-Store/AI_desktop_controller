# AI_desktop_controller

# 🚀 AI Desktop Controller  
### 🧠 Control Your Entire PC with AI — From Desktop or Smartphone 📱💻

<p align="center">
  <img src="https://img.shields.io/badge/AI-Powered-blue?style=for-the-badge&logo=robotframework" />
  <img src="https://img.shields.io/badge/Platform-Windows-success?style=for-the-badge&logo=windows" />
  <img src="https://img.shields.io/badge/Remote-Control-orange?style=for-the-badge&logo=android" />
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" />
</p>

---

<p align="center">
  <img src="https://media.giphy.com/media/QBd2kLB5qDmysEXre9/giphy.gif" width="600"/>
</p>

---

# 🔥 What is AI Desktop Controller?

AI Desktop Controller ek intelligent automation system hai jo:

✅ PC ko voice se control karta hai  
✅ Commands ko samajhta hai  
✅ Smartphone se remote control allow karta hai  
✅ System level automation karta hai  
✅ Fully Local – No Cloud Required  

---

# ✨ Core Features

## 🖥 Full Desktop Control
- Open / Close Applications  
- File & Folder Control  
- Shutdown / Restart / Sleep  
- Volume & Media Control  
- Browser Automation  
- Task Automation  

---

## 🎙 Smart Voice Assistant
- Offline Voice Recognition  
- Natural Language Processing  
- Custom Commands Support  
- Text to Speech Response  

---

## 📱 Smartphone Control Mode

> Phone se PC ko control karo real-time

- Same WiFi par connect
- Web-based control panel
- Instant command execution
- No extra software required

---
# 💖 Set Waifu & Connect MateEngine

This section explains how to setup your Waifu package and connect it with MateEngine.exe properly.

---

## 📦 Step 1 – Extract Waifu ZIP

1️⃣ Download the Waifu ZIP file  
2️⃣ Right-click the ZIP file  
3️⃣ Click **Extract Here** or **Extract to Folder**  
4️⃣ Make sure the extracted folder contains:

```
waifu/
├── model/
├── textures/
├── config.json
├── animations/
```

⚠ Important: Do NOT run directly from inside ZIP. Always extract first.

---

## 🖥 Step 2 – Place Waifu Folder

Move the extracted `waifu` folder inside:

```
AI_Desktop_Controller/assets/
```

Final structure should look like:

```
AI_Desktop_Controller/
│
├── assets/
│   ├── waifu/
│
├── MateEngine.exe
├── launcher.py
```

---

## ⚙ Step 3 – Connect MateEngine.exe

1️⃣ Make sure `MateEngine.exe` is in the root directory  
2️⃣ Double click `MateEngine.exe`  
3️⃣ Wait until engine fully loads  
4️⃣ Now run:

```bash
python launcher.py
```

If configured correctly, MateEngine will:

✔ Load Waifu Model  
✔ Initialize Animations  
✔ Start AI Sync  
✔ Connect to Desktop Controller  

---

## 🔌 Auto Connect Configuration

Open `config.json` and verify:

```json
{
  "mate_engine_path": "MateEngine.exe",
  "waifu_path": "assets/waifu/",
  "auto_connect": true
}
```

If MateEngine is installed somewhere else, provide full path:

```json
"mate_engine_path": "C:/Program Files/MateEngine/MateEngine.exe"
```

---

## 🧠 How Connection Works

1️⃣ Launcher checks MateEngine process  
2️⃣ If not running → auto start  
3️⃣ Engine loads waifu model  
4️⃣ Socket connection established  
5️⃣ AI commands sync with animation system  

---

## 🛠 Troubleshooting

### ❌ Waifu Not Loading
- Check folder name spelling
- Ensure model files exist
- Re-extract ZIP

### ❌ MateEngine Not Connecting
- Run as Administrator
- Check firewall permission
- Verify correct path in config.json

### ❌ Animation Not Working
- Confirm animations folder exists
- Check model compatibility version

---

## 🚀 Advanced Mode (Optional)

To auto-start MateEngine when Windows boots:

1️⃣ Press `Win + R`
2️⃣ Type:

```
shell:startup
```

3️⃣ Paste MateEngine shortcut inside Startup folder

Now your Waifu + AI will auto start with PC 🔥

---

# ✅ Setup Complete

Once connected successfully:

- Voice commands trigger animation
- Smartphone control syncs with Waifu
- Desktop automation shows live reactions

Your AI Waifu is now fully active 💖🤖


# 🛠 Tech Stack

| Technology | Purpose |
|------------|----------|
| Python | Core Engine |
| Flask / Socket | Communication Server | Unityhub
| SpeechRecognition | Voice Input |
| TTS Engine | Voice Output |
| Web Interface | Smartphone Control |
| Automation APIs | System Control |

---

# 📂 Project Structure

```
AI_Desktop_Controller/
│
├── core/
│   ├── ai_engine.py
│   ├── voice_module.py
│
├── server/
│   ├── app.py
│
├── client/
│   ├── mobile_interface/
│
├── models/
│
├── launcher.py
├── config.json
└── README.md
```

---

# ⚙ Installation Guide

## 1️⃣ Clone Repository

```bash
git clone https://github.com/YOUR-USERNAME/AI_desktop_controller.git
cd AI_Desktop_Controller
```

---

## 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 3️⃣ Run Application

```bash
python launcher.py
```

---

# 📱 How To Use Smartphone Control

1️⃣ PC par `launcher.py` run karo  
2️⃣ Terminal me local IP address show hoga  
3️⃣ Phone me browser open karo  
4️⃣ Enter karo:  

```
http://YOUR-PC-IP:PORT
```

5️⃣ Control panel open ho jayega 🎉  
6️⃣ Commands bhejo — PC execute karega instantly  

---

# 🎯 Example Commands

| Command | Action |
|---------|--------|
| Open Chrome | Browser launch |
| Shutdown PC | System shutdown |
| Increase volume | Volume up |
| Play music | Media control |
| Lock system | Windows lock |

---

# 🔐 Security System

- Local Network Only
- Token Based Access
- Permission Controlled Commands
- No Internet Dependency

---

# 🌟 Advanced Capabilities

- Custom Command Creation  
- Auto Startup Mode  
- Background Listener  
- AI Smart Response Mode  
- Multi-device Control Support  

---

# 🚀 Future Updates

- 🌐 Global Remote Access  
- 🔒 End-to-End Encryption  
- 🧩 Plugin System  
- 🧠 GPT Integration  
- 📊 System Monitoring Dashboard  

---

# 📸 Demo Preview

<p align="center">
  <img src="https://media.giphy.com/media/26xBukhGLPRU7sY3C/giphy.gif" width="500"/>
</p>

---

# 🤝 Contribution

Pull requests welcome 🚀  
Fork → Improve → Submit PR  

---

# 📜 License

MIT License

---

# 💎 Developer

Made with ❤️ by **DHR-Store**

---

# ⭐ If You Like This Project

Give it a star ⭐  
It motivates development 💪🔥

---

<p align="center">
  <img src="https://img.shields.io/badge/POWERED-BY-AI-red?style=for-the-badge" />
</p>
