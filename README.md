<div align="center">

✨ Morphiq

Your pocket-sized Photoshop, powered by AI

A mobile-first, AI-assisted photo editing system. Just say what you want, and watch your photo transform.

</div>

⸻

🌟 What is Morphiq?

Morphiq reimagines Photoshop as a mobile-first, AI-driven editing app. Instead of hunting through menus and sliders, you can describe an edit, speak it out loud, or let the AI plan a multi-step edit for you.

This repository holds everything in one place: the full codebase (backend + web + mobile), the AI models, and the documentation.

⸻

🎨 Features

	Feature	What it does
🧊	3D Parallax Effects	Give flat photos depth and motion
🌗	Day → Night Timeline	Transform a scene from day to night, weather-aware
⚡	Fast Agent	Gemma 3-1B handles quick edits
🧠	Thinking Mode	Llama 3.2-3B handles multi-step reasoning
🗣️	Voice-based Editing	Speak your edits using Deepgram STT
🖼️	Full Vision Toolkit	Segmentation, depth, detection, inpainting, super-resolution, and filters
🔒	Local Inference	Runs through Ollama, so no cloud is required

⸻

📁 Repository Structure

Code/
.gitignore

* 🎯 Code: Contains the complete project codebase, including the backend, orchestrator, website, mobile app, AI model pipelines, and documentation.

⸻

🛠️ Tech Stack

Layer	Technologies
Backend	Python, FastAPI, ONNX Runtime, PyTorch
Frontend	React + Vite
Mobile App	React Native (Expo)
LLMs (via Ollama)	Gemma 3-1B, Llama 3.2-3B
Vision Models	YOLO11n, MobileSAM, BiRefNet, Depth-Anything-V2, MI-GAN, SwinIR

⸻

▶️ Quick Start

To run the full application (backend + web + mobile):

1. Install Ollama and pull the required models
2. Add the models inside /backend/models
3. Set environment variables in /backend/.env
4. Run:

.\SETUP.bat
.\START.bat

📖 For manual instructions, see the detailed README inside Code/README.md

⸻

📜 License

MIT License. See LICENSE for details.

⸻

<div align="center">

Built with ❤️ for creators everywhere.

Created by CodeCrusherG

</div>
