# 🧠🔊 Synapse
Synapse is an AI-powered voice-first assistant designed for early dementia detection and cognitive support, combining medical imaging, voice intelligence, and interactive tools into a unified platform.

## 🚀 Features

- 🧬 Dementia Detection (MRI-Based)  
  Analyze brain MRI scans to assist in early-stage dementia detection using AI models.

- 🎙️ Voice Recognition  
  Detect cognitive decline patterns through speech analysis and conversational inputs.

- 🤖 SLM Agent  
  Lightweight AI agent for real-time interaction, assistance, and intelligent task handling.

- 🧩 Mind Games  
  Interactive cognitive games designed to assess and improve memory, focus, and mental agility.

- 📊 Dashboard  
  Centralized dashboard to track user activity, cognitive metrics, and health insights.
## 📁 Repository Layout

- `FinalEclipse/` - Django project UI and app modules 🖥️  
- `src/synapse/` - voice pipeline, routing, workers, and training utilities 🔁🧠  
- `manage.py` - root launcher script 🚀  
- `faiss_memory/` - runtime memory artifacts 🧩  

## ⚡ Quick Start

1. Create and activate a virtual environment 🛠️  
2. Install dependencies from the project requirements files 📦  
3. Run the Django server from the project root:

```bash
python manage.py runserver
```


## 📝 Notes 
The repository ignores local and heavy runtime folders🚫: 
- .venv/
- dataset/
- resources/
