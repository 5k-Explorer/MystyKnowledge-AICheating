# MystyKnowledge

Serving curious minds with AI answers since 2025.

MystyKnowledge is a lightweight AI-powered Q&A system built for Discord + Web, making it easy to spin up an Ollama-powered model (Gemma 3) and share it securely with others. It combines Discord bot commands, a FastAPI backend, and ngrok tunneling for remote access.

⚡ Fast,
🔒 Private,
💻 Self-hosted on your own machine.

✨ Features

Discord Integration
Control the AI directly from Discord using !MKlink and !status.

Gemma 3 Model (Ollama)
Uses the latest Gemma 3:4b model for reliable responses, math help, and more.

Web Access with ngrok
Share a secure link with friends across the country—no extra setup needed.

Auto Cloaking / Daily URL Rotation
ngrok ensures your public link changes daily for safety and privacy.

Simple Commands

!MKlink → Start or restart the AI server and generate a fresh link

!status → Check if the server is live

Math + Step-by-Step Explanations
Safe arithmetic evaluation is built in. If your question is math-related, you’ll get both the answer and an explanation.

🚀 How It Works (High-Level)

Discord Controller

Handles commands like !MKlink.

Spins up the FastAPI server if not running.

Returns the live ngrok link to Discord.

FastAPI Backend

Exposes endpoints (/ and /chat).

Hosts a simple frontend page and chat API.

Ollama + GPU Acceleration

Runs locally on your hardware.

Automatically leverages your GPU (RTX 4060 recommended).

ngrok Tunneling

Creates a temporary, secure URL accessible from anywhere.

No port forwarding or extra setup needed.

📊 Performance

Optimized for 3–5 users simultaneously.

Average response delay: ~2–4 seconds on GPU.

Handles medium-length questions without noticeable slowdown.

📦 Deployment Notes

This project is not open-source. The core code is private.

Deployment instructions are simplified since only maintainers have access to the actual backend files.

If you are part of the MystyKnowledge testing group:

Request access from the maintainer.

Use the ngrok link shared in Discord.

No extra setup required.

⚠️ Disclaimer

This project is closed-source. Redistribution, modification, or unauthorized deployment is not permitted.

If you are interested in contributing, please open an issue or contact me directly.

📞 Support

Join our Discord Community (private invite link for testers).

Open an issue here on GitHub.

🙌 Credits

Ollama for local model runtime.

Gemma 3 for powering the intelligence.

FastAPI + ngrok + Discord.py for the integration backbone.
