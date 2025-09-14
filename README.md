#  Mysty AI

Mysty is a locally hosted Discord + Web AI assistant built for speed, sarcasm, and customizability.  
It runs on your machine but can be shared securely with friends using tunneling services.

---

##  Features

-  Discord bot integration  
-  Daily Links to prevent blocks
-  Lightweight + fast response times  
-  Private hosting with ngrok (share with friends without exposing your IP)  

---

##  Deployment

> [!IMPORTANT]  
> Mysty is designed to run **locally on your own hardware**.  
> Cloud hosting is not recommended due to GPU/latency requirements.

### 🔹 Running Locally
```bash
git clone https://github.com/YourUser/Mysty.git
cd Mysty
pip install -r requirements.txt
python main.py
🔹 Sharing Access (Ngrok)
Run ngrok to create a temporary secure link:

bash
Copy code
ngrok http 5000
This generates a unique URL (refreshes daily) you can share with trusted users.
Supports up to 5 concurrent users on mid-range GPUs without noticeable slowdown.

⚙️ Performance Notes
[!TIP]
If you have a GPU like the RTX 4060, you can force Mysty to run 100% on GPU for faster response times.
For lighter loads (1–3 users), a balanced CPU/GPU split is fine.

Expected latency with 3–5 users:

 ~1.2s per response (GPU mode)

 ~2–2.5s per response (CPU-balanced mode)

🌐 Deployment Alternatives
If you don’t want to host locally, you can explore:

🔹 Render

🔹 Koyeb

🔹 Replit

[!WARNING]
Free hosts like Netlify, Cloudflare Pages, or GitHub Pages will not work since Mysty requires a Python backend and GPU access.

🖥️ GitHub Codespaces (Optional)
[!NOTE]
If you set the port below 1023, you must run sudo PORT=1023

Create a GitHub account if you haven’t already.

Click Code → Create Codespace on main.

Run:

bash
Copy code
pip install -r requirements.txt
python main.py
Forward the port in Codespaces and set it to public visibility.

🤝 Support
If you run into issues:

Open a GitHub issue with details

Or join the Mysty Discord server (https://discord.gg/HEj4kB5VRS)

📜 License
This project is proprietary.
You may not copy, redistribute, or modify the source code without explicit permission.
