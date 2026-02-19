# AI_Desktop_Controller

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

AI Desktop Controller is an intelligent automation system that allows you to:

✅ Control your PC using voice commands  
✅ Understand and execute smart commands  
✅ Remotely control your PC from a smartphone  
✅ Perform system-level automation  
✅ Operate fully locally — No cloud dependency  

---

# ✨ Core Features

## 🖥 Full Desktop Control

- Open / Close Applications  
- File & Folder Management  
- Shutdown / Restart / Sleep  
- Volume & Media Control  
- Browser Automation  
- Task Automation  

---

## 🎙 Smart Voice Assistant

- Offline Voice Recognition  
- Natural Language Processing  
- Custom Command Support  
- Text-to-Speech Responses  

---

## 📱 Smartphone Control Mode

> Control your PC in real-time from your phone

- Connect via same WiFi network  
- Web-based control panel  
- Instant command execution  
- No additional software required  

---

# 💖 Set Waifu & Connect MateEngine

This section explains how to set up your Waifu package and connect it with `MateEngine.exe`.

---

## 📦 Step 1 – Extract Waifu ZIP

1️⃣ Download the Waifu ZIP file  
2️⃣ Right-click the ZIP file  
3️⃣ Select **Extract Here** or **Extract to Folder**  
4️⃣ Ensure the extracted folder contains:

```
waifu/
├── model/
├── textures/
├── config.json
├── animations/
```

⚠ Important: Do NOT run files directly from the ZIP archive. Always extract first.

---

## 🖥 Step 2 – Place Waifu Folder

Move the extracted `waifu` folder into:

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

1️⃣ Make sure `MateEngine.exe` is placed in the root directory  
2️⃣ Double-click `MateEngine.exe`  
3️⃣ Wait until the engine fully loads  
4️⃣ Then run:

```bash
python launcher.py
```

If configured correctly, MateEngine will:

✔ Load Waifu model  
✔ Initialize animations  
✔ Start AI synchronization  
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

If MateEngine is installed elsewhere, provide the full path:

```json
"mate_engine_path": "C:/Program Files/MateEngine/MateEngine.exe"
```

---

## 🧠 How the Connection Works

1️⃣ Launcher checks if MateEngine process is running  
2️⃣ If not running → auto-starts it  
3️⃣ Engine loads Waifu model  
4️⃣ Socket connection is established  
5️⃣ AI commands sync with animation system  

---

## 🛠 Troubleshooting

### ❌ Waifu Not Loading

- Check folder name spelling  
- Ensure model files exist  
- Re-extract the ZIP file  

### ❌ MateEngine Not Connecting

- Run as Administrator  
- Check firewall permissions  
- Verify correct path in `config.json`  

### ❌ Animations Not Working

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

3️⃣ Place a MateEngine shortcut inside the Startup folder  

Now your Waifu + AI system will automatically start with your PC 🔥

---

# ✅ Setup Complete

Once successfully connected:

- Voice commands trigger animations  
- Smartphone control syncs with Waifu  
- Desktop automation shows live AI reactions  

Your AI Waifu is now fully active 💖🤖  

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|----------|
| Python | Core Engine |
| Flask / Socket | Communication Server |
| SpeechRecognition | Voice Input |
| TTS Engine | Voice Output |
| Web Interface | Smartphone Control |
| Automation APIs | System Control |
| Unity Hub | Engine Management |

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

1️⃣ Run `launcher.py` on your PC  
2️⃣ The terminal will display your local IP address  
3️⃣ Open your phone browser  
4️⃣ Enter:

```
http://YOUR-PC-IP:PORT
```

5️⃣ The control panel will open 🎉  
6️⃣ Send commands — your PC will execute instantly  

---

# 🎯 Example Commands

| Command | Action |
|---------|--------|
| Open Chrome | Launch browser |
| Shutdown PC | System shutdown |
| Increase volume | Volume up |
| Play music | Media control |
| Lock system | Lock Windows |

---

# 🔐 Security System

- Local Network Access Only  
- Token-Based Authentication  
- Permission-Controlled Commands  
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

Pull requests are welcome 🚀  
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
