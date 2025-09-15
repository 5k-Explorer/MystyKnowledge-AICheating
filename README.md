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
> Cloud hosting is not recommended due to GPU/latency requirements and hosting the AI.

### 🔹 Running Locally
1. Download the latest release from the [Releases page](https://github.com/5k-Explorer/MystyKnowledge-AICheating/releases).  
   - Windows: extract the `.zip` and run `mysty.exe`  
   - No other OS with directly guaranteed support

2. Mysty will install dependencies and start automatically.  

3. To share access, use the Ngronk URL provided when you run the app build.
   - This generates a unique daily link you can share with trusted users.

> [!NOTE]  
> In the Discord server, daily links are posted at 12AM every day.  
> However, the links generally become active around 10AM or later (estimated).

⚙️ Performance Notes
Expected latency with 3–5 users:

~1.2s per response (GPU mode)

~2–2.5s per response (CPU-balanced mode)

Note that these Performance notes were taken on a high-end GPU.

🌐 Deployment Alternatives
If you don’t want to host locally, you can explore:

Render

Koyeb

Replit

> [!IMPORTANT]  
> Free hosts like Netlify, Cloudflare Pages, or GitHub Pages will not work since Mysty requires a Python backend and GPU access.

🤝 Support
If you run into issues:

Open a GitHub issue with details

Or join the Mysty Discord server: https://discord.gg/HEj4kB5VRS

📜 License
This project is proprietary.
You may not copy, redistribute, or modify the source code without explicit permission.
