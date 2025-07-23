# Personal‑ai 🤖

A simple, personal AI assistant built in Python—designed to be lightweight, friendly, and easy to extend.

---

## 🔍 Project Overview

**Personal‑ai** creates an interactive AI companion ("Jarvis") that:

- Greets you with a custom intro.
- Responds in a friendly, respectful tone.
- Is easily modifiable for prompt or functionality enhancements.

**Core files**:

- `agent.py` — runs the main assistant loop
- `prompt.py` — contains `jarvis_intro` and `jarvis_response` variables

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x  
- Install dependencies:
  ```bash
  pip install -r Requirements.txt
  
git clone https://github.com/vasudxv-r/Personal-ai.git
cd Personal-ai

Run the assistant:
python agent.py console

Personal‑ai/
├── agent.py       # Handles I/O loop and AI calls
├── prompt.py      # Defines intro & response variables
├── Requirements.txt
└── .env.example   # For any needed secrets or configs
