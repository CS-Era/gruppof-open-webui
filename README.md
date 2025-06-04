# Open WebUI - Docker Compose Deployment

Deploy Open WebUI with Ollama using Docker Compose and Nginx.

**Live Demo**: https://gruppof.marcomelucci.me

## 🚀 Quick Start

### 1. Clone and Setup

```bash
git clone https://github.com/your-username/open-webui-deploy.git
cd open-webui-deploy
cp .env.example .env
```

### 2. Start Services

```bash
docker compose up -d
```

### 3. Enjoy


## 🔧 HTTPS Setup (Optional)

To expose publicly with HTTPS, modify `nginx/default.conf` with your domain and configure SSL certificates.

## 📚 Available Models

Browse and download models from [Ollama Library](https://ollama.ai/library).

To download any model modify the .env file or download directly from the GUI in Administration Panel -> Settings -> Models

## 👥 Development Team

**Developed by CyberHackademy GroupF:**

- 🔵 [@marcomelucci](https://github.com/marcomelucci)
- 🟢 [@erasmoprosciutto](https://github.com/erasmoprosciutto)
- 🟡 [@danieledegni](https://github.com/danieledegni)
- 🟣 [@luigimaresca](https://github.com/luigimaresca)

---

Have fun with LLM models! 🚀

**Powered By**: CyberHackademy Unina 🎓
