# Autonomous EQ Mixer (AI-powered for Behringer X32)

**Features:**
- Connects to Behringer X32 via OSC
- Detects active input channels
- Analyzes audio streams per channel
- Applies expert-level EQ (vocals, instruments, drums, etc.)
- Logs each EQ decision (timestamp, channel, parameter, value) in JSONL
- Simple web UI shows EQ curves in real time

**Tech Stack:** Python, PyTorch (AI), OSC protocol, React (client), FastAPI/Flask (server)

**Directories:**
- `/client` – Web UI
- `/server` – OSC bridge, REST API, logging
- `/ai-engine` – AI model, EQ logic