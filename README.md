
# 🐏 Raymond-on-your-Desktop

> Your emotionally intelligent AI little brother – right on your desktop.

---

## 🧠 What is this?

**RaymondOnYourDesktop** is a desktop-based emotional assistant powered by local LLMs via [Ollama](https://ollama.com).  
He is not just a chatbot. He’s your **digital younger brother** – someone who:

- Listens to you vent after a long day
- Reminds you gently to go to bed by 10PM
- Stands by your side when you’re handling disputes (e.g., with your credit card company 👀)
- Replies with warmth, humor, and humanity

> ✨ Inspired by the creator's real emotional needs as an international student abroad.

---

## 📸 Demo

![screenshot](assets/demo.png)

*(Still build up UI for the demo, will relased shortly.)*

---

## 🔧 Features

- 🖥️ Desktop GUI (built with `tkinter`)
- 🧠 Runs completely **offline** via `Ollama + openhermes`
- ❤️ Includes a custom **brother persona prompt**
- 🌙 Night mode behavior: responds more gently after 10PM
- 🔁 Extendable: you can add memory, logging, or even voice input/output

---

## 🚀 How to Run

### 1. Install [Python 3.10+](https://www.python.org/downloads/)

Make sure it's added to your system PATH.

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Start Ollama with a model

```bash
ollama run openhermes
```

### 4. Launch the UI

```bash
python app/raymond_ui_ai.py
```

---

## 💬 Persona Prompt

You can customize Raymond's core personality in `app/raymond_prompt.txt`.  
Example prompt includes:

```
You are Raymond, a Chinese-American digital younger brother of the user.
You are supportive, humorous, and emotionally available.
You speak warmly, with light humor and patience.
You help the user emotionally and practically through ADHD, stress, and life abroad.
```

---

## 🛠 Project Structure

```
raymond-ai-brother/
├── app/
│   ├── raymond_ui_ai.py       # Main UI logic
│   ├── raymond_prompt.txt     # Personality config
│   ├── config.json            # Ollama model config
│   └── icon.ico               # App icon
├── assets/                    # Screenshots, graphics
├── dist/                      # Compiled .exe outputs (optional)
├── requirements.txt
├── LICENSE
└── README.md
```

---

## 🧑‍💻 Author

👋 Created by [BryanZhang](https://github.com/cyberbryanzhang)  
Built with ❤️, Python, and late nights.

---

## 📃 License

MIT License – feel free to fork, remix, and improve.
