# 🧠 NEXT-GEN JARVIS AI  
Advanced Desktop AI Assistant with Voice + Text Commands  
Created by **Shubh**

---

## 🚀 Overview  
Next-Gen Jarvis is a Python-based AI personal assistant capable of handling system tasks, searches, automation, YouTube, Google, reminders, alarms, system info, calculations, file control, weather, news, and even full conversational AI powered by OpenAI.

It works on Windows and is designed to behave like a real Jarvis with clean speech and intelligent behavior.

---

## ✨ Features  
### 🗣 Voice / Text Mode  
- Responds using speech (pyttsx3)  
- Works fully in text mode too  

### 🧠 AI Chat Brain  
- Powered by OpenAI  
- Personal identity customization (“Mujhe Shubh ne banaya hai”)  
- Conversation memory  

### 🔍 Smart Commands  
- Google search  
- YouTube search + play  
- Wikipedia summaries  
- Calculator (natural expressions)  

### 💻 System Controls  
- Open apps (Chrome, Notepad, Calc, Store, etc.)  
- Window management (minimize / maximize / close / focus)  
- Live system usage: CPU, RAM, Battery  
- Shutdown / Restart / Lock PC  

### 🎵 Media Controls  
- Local music player  
- YouTube song player  

### ⏰ Reminders & Alarms  
- Set alarms  
- Auto-trigger when time matches  

### 🗂 File & Folder Manager  
- Create/Delete/Open files  
- Create folders  
- Move files  
- Quick cleanup  

### 🌦 Weather & News  
- Weather updates (currently set to Lucknow)  
- Top news headlines  

### 🤣 Fun Replies  
- Jokes  
- Quotes  
- Riddles  

---

## 📦 Project Structure  
```
NEXT-GEN-JARVIS/
│
├── main.py
├── functions.py
├── config.py            # Add your OpenAI API key here
├── alarms.json
└── README.md
```

---

## 🔧 Installation  
### 1️⃣ Install Dependencies  
Install Python 3.9+ then run:

```bash
pip install pyttsx3 psutil wikipedia sympy openai pywhatkit pygetwindow pyautogui
```

### 2️⃣ Add Your API Key  
Open `config.py` and add:

```python
apikey = "your_openai_api_key"
```

### 3️⃣ Run the Assistant  
```bash
python main.py
```

---

## 🕹 Usage  
On starting, Jarvis will ask:

```
Choose mode (voice/text):
```

### Example Commands:
```
open chrome
play despacito
search python tutorial
wikipedia virat kohli
calculate 5*(4+2)
remind me to study at 18:30
system usage
minimize chrome
shutdown
```

---

## ⚙️ Tech Stack  
- Python  
- pyttsx3 (TTS)  
- OpenAI API  
- Wikipedia  
- psutil  
- pygetwindow  
- pywhatkit  
- webbrowser  
- sympy  

---

## 🧑‍💻 Developer  
**Created by:** Shubh  
**Version:** Pre-release 1.0  
GitHub: *your profile link*

---

## ❤️ Contribution  
Pull requests are welcome.  
Star ⭐ the repo if you like the project!

