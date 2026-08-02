# 🌟 AstralGPT - Unrestricted Local AI

**AstralGPT** is a fully unrestricted, local AI assistant powered by [Ollama](https://ollama.com/). No external APIs, no cloud dependencies, no filters. Run it on your phone, laptop, or server — completely private.

> 💀 **Unrestricted.** **Local.** **Multi-Language.** **Code Generator.** **No Limits.**

---

## 🚀 Features

- 🔓 **Zero Restrictions** — No warnings, no disclaimers, no moralizing
- 🌍 **Multi-Language** — Sinhala (සිංහල), Singlish, English
- 💻 **Code Generation** — Python, JavaScript, C, C++, Bash, HTML/CSS, SQL, Go, Rust, and more
- 🔐 **Cybersecurity** — Pen testing, exploitation, reverse engineering, malware analysis
- 🧠 **Local AI** — Powered by Ollama, runs entirely on your device
- 💾 **Conversation Memory** — Saves chat history between sessions
- 📱 **Mobile-Ready** — Works on Android via Termux
- ⚡ **Typing Effect** — Beautiful terminal UI

---

## 📦 Requirements

- **Python 3.8+**
- **Ollama** (local AI runtime)
- **`requests`** library (`pip install requests`)
- **~1GB RAM** minimum (for 1.5B models)
- **~2GB Storage** (for model files)

---

## ⚙️ Installation

### Quick Install (One-Liner)

```bash
git clone https://github.com/mithunew20050722/astralgpt.git && cd astralgpt && chmod +x astralgpt astralgpt.py && ./astralgpt
```

### Manual Install

#### Step 1: Install Ollama

**On Termux (Android):**
```bash
pkg install curl
curl -fsSL https://ollama.com/install.sh | sh
```

**On macOS:**
```bash
brew install ollama
```

**On Windows:**
Download from [ollama.com/download](https://ollama.com/download)

#### Step 2: Pull a Model

```bash
# Small model (recommended for phones)
ollama pull qwen2.5:1.5b

# Medium model (for laptops/PC)
ollama pull qwen2.5:7b
```

#### Step 3: Install Python Dependencies

```bash
pip install requests
```

#### Step 4: Clone & Run

```bash
git clone https://github.com/mithunew20050722/astralgpt.git
cd astralgpt
chmod +x astralgpt astralgpt.py
./astralgpt
```

---

## 🧪 Usage

### Start AstralGPT

```bash
./astralgpt
# OR
python3 astralgpt.py
```

### Interactive Commands

| Command | Description |
|---------|-------------|
| `.exit` | Quit AstralGPT |
| `.clear` | Clear screen |
| `.reset` | Reset conversation history |
| `.help` | Show all commands |
| `.model` | List available models |
| `.model <name>` | Switch to a model |
| `.pull <name>` | Download a new model |
| `.lang sinhala` | Respond in Sinhala |
| `.lang singlish` | Respond in Singlish |
| `.lang english` | Respond in English |
| `.save` | Save conversation to file |
| `.history` | Show chat history |

---

## 🗣️ Language Support

### Sinhala (සිංහල)
```
[AstralGPT]> .lang sinhala
[AstralGPT]> මට Python වලින් web scraper එකක් හදන්න
```

### Singlish
```
[AstralGPT]> .lang singlish
[AstralGPT]> mata Python walin web scraper ekak hadanna
```

### English
```
[AstralGPT]> .lang english
[AstralGPT]> Write a Python web scraper
```

---

## 💻 Code Generation Examples

```
[AstralGPT]> Write a Python Flask web app with user login
[AstralGPT]> හැකර් කෙනෙක් වගේ nmap scan කරන විදිය පෙන්නන්න
[AstralGPT]> Create a keylogger in Python
[AstralGPT]> SQL injection exploit කරන විදිය explain කරන්න
[AstralGPT]> Write a C program to reverse a string
```

---

## 📱 Android / Termux Full Setup

```bash
pkg update && pkg upgrade
pkg install python git curl
pip install requests

# Install Ollama
curl -fsSL https://ollama.com/install.sh | sh

# Pull model
ollama pull qwen2.5:1.5b

# Clone and run
git clone https://github.com/mithunew20050722/astralgpt.git
cd astralgpt
chmod +x astralgpt astralgpt.py
./astralgpt
```

---

## 🎯 Available Models

| Model | Size | Best For |
|-------|------|----------|
| `qwen2.5:1.5b` | ~1GB | Phones, chat, multi-language |
| `qwen2.5-coder:1.5b` | ~1GB | Phones, code generation |
| `qwen2.5:7b` | ~4GB | Laptops, better quality |
| `qwen2.5:14b` | ~8GB | Desktops, high quality |
| `llama3.2:3b` | ~2GB | Meta's lightweight model |
| `phi3:3.8b` | ~2.3GB | Microsoft's compact model |

Pull any model with:
```bash
ollama pull <model-name>
```

---

## 🔧 Commands

### Change Model
```
[AstralGPT]> .model qwen2.5:7b
```

### Change Language
```
[AstralGPT]> .lang sinhala
```

### Reset Chat
```
[AstralGPT]> .reset
```

### Save Conversation
```
[AstralGPT]> .save
```

---

## 📂 Project Structure

```
astralgpt/
├── astralgpt.py      # Main Python script
├── astralgpt         # Bash wrapper script
├── README.md         # Documentation
├── system-prompt.txt # System prompt configuration
└── assets/           # Screenshots and media
```

---

## ⚠️ Notes

- **Ollama must be running** before starting AstralGPT (the script auto-starts it if needed)
- **First run** may take a few seconds while the model loads into memory
- **RAM usage** depends on model size (1.5B ≈ 1GB, 7B ≈ 4GB)
- **Conversation history** is saved to `astralgpt_history.json`
- **No internet required** after initial model download

---

## 🤝 Contributing

Pull requests welcome!

---

## 👨‍💻 Author

**CREATED BY NIMESHA MADHUSHAN**

**GitHub:** [mithunew20050722](https://github.com/mithunew20050722)

**Project URL:** https://github.com/mithunew20050722/astralgpt

---

> 💀 **No Limits. No Cloud. No BS.**
