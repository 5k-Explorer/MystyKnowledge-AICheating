# Mysty AI

Mysty is a locally hosted Discord + Web AI assistant built for speed and intelligence.  
It runs on your machine but can be shared with friends using tunneling services.  
Alternatively, daily links are provided in the Mysty Tools Discord, so no setup is required.

---

## Features

- Discord bot integration  
- Daily links to prevent blocks  
- Lightweight + fast response times  
- Private hosting with ngrok (share with friends without exposing your IP)  

---

## Deployment

> [!IMPORTANT]  
> Mysty is designed to run **locally on your own hardware**.  
> Cloud hosting is not recommended due to GPU/latency requirements.

### 🔹 Running Locally
1. Download the latest release from the [Releases page](https://github.com/5k-Explorer/MystyKnowledge-AICheating/releases).  
   - Windows: extract the `.zip` and run `mysty.exe`  
   - Linux/Mac: run `./mysty` from terminal  

2. Mysty will install dependencies and start automatically.  

3. To share access, run ngrok:
   ```bash
   ngrok http 5000
This generates a unique daily link you can share with trusted users.

⚙️ Performance Notes
[!TIP]
If you have a GPU like the RTX 4060, you can force Mysty to run 100% on GPU for faster response times.
For lighter loads (1–3 users), a balanced CPU/GPU split is fine.

Expected latency with 3–5 users:

~1.2s per response (GPU mode)

~2–2.5s per response (CPU-balanced mode)

🌐 Deployment Alternatives
If you don’t want to host locally, you can explore:

Render

Koyeb

Replit

[!WARNING]
Free hosts like Netlify, Cloudflare Pages, or GitHub Pages will not work since Mysty requires a Python backend and GPU access.

🖥️ GitHub Codespaces (Optional)
[!NOTE]
If you set the port below 1023, you must run sudo PORT=1023.

Open the repo in GitHub Codespaces.

Forward the port and set visibility to public.

Access Mysty through the forwarded link.

🤝 Support
If you run into issues:

Open a GitHub issue with details

Or join the Mysty Discord server: https://discord.gg/HEj4kB5VRS

📜 License
This project is proprietary.
You may not copy, redistribute, or modify the source code without explicit permission.
