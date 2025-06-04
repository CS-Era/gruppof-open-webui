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

### 3. Download Ollama Models

Download a model (example: llama3.2:1b):

```bash
docker exec ollama-test ollama pull llama3.2:1b
```

Check downloaded models:

```bash
docker exec ollama-test ollama list
```

### 4. Access

Open your browser and navigate to:

```
http://localhost:3000
```

## 🔧 HTTPS Setup (Optional)

To expose publicly with HTTPS, modify `nginx/default.conf` with your domain and configure SSL certificates.

## 📚 Available Models

Browse and download models from [Ollama Library](https://ollama.ai/library).

To download any model:

```bash
docker exec ollama-test ollama pull model-name
```

## 👥 Development Team

**Developed by CyberHackademy GroupF:**
- Marco Melucci
- Erasmo Prosciutto
- Daniele Degni
- Luigi Maresca

---

Have fun with LLM models! 🚀

**Powered By**: CyberHackademy Unina 🎓
