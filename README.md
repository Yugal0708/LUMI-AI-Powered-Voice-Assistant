# 🎙️ Lumi — Personal Voice AI Assistant

Lumi is a desktop voice assistant built by **Yugal Bilawane**.  
It understands natural Hinglish conversation, performs system actions, searches the web, checks the weather, and runs Python tools in real time.

This project uses LiveKit Agents, custom tool logic, weather APIs, Google search automation, and local system controls like keyboard, mouse, files, and windows.

---

## 🚀 Features

### 🎤 Natural Hinglish Interaction
- Responds in a clean and friendly Hinglish style  
- Uses a custom personality prompt  
- Supports conversational understanding

### 🌦️ Live Weather Tool
- Detects city automatically using IP  
- Fetches weather using OpenWeather API  
- Provides conditions, temperature, humidity and wind

### 🔍 Google Search Integration
- Queries the web for answers  
- Summarizes results in a simple way  
- Works with custom tool calls

### 🖱️ Complete System Control
Lumi can perform real-time OS-level actions:

- Open/close applications  
- Play files (mp3, mp4, pdf, images, etc.)  
- Move mouse pointer  
- Click, scroll, drag  
- Type text  
- Press keys and hotkeys  
- Control system volume  
- Window management (minimize, maximize, switch)

### 🧠 Reasoning + Memory
- Custom reasoning loop  
- Optional memory system  
- Smooth tool-calling logic  
- Clear separation between prompt, reasoning, and action layers

---

## 📦 Project Structure

Your repository files:

├── .env # API keys and environment variables
├── agent.py # Main LiveKit agent setup
├── control_log.txt # Execution logs (mouse/keyboard/system)
├── keyboard_mouse_CTRL.py # Mouse + keyboard tool controls
├── Lumi_file_opner.py # File opener tool
├── Lumi_get_whether.py # Weather tool (IP + OpenWeather)
├── Lumi_google_search.py # Google search tool
├── Lumi_prompts.py # System and reply prompts for Lumi
├── lumi_reasoning.py # Reasoning and tool-calling logic
├── Lumi_window_CTRL.py # Window manager (open, close, switch)
├── memory_loop.py # AI memory update loop
└── memory_store.py # Persistent memory logic
