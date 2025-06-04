# Open WebUI - Deployment con Docker Compose

Accessible on: **https://gruppof.marcomelucci.me**

## Setup

1. Clone the repository on your system:
   ```bash
   git clone https://github.com/tuo-utente/open-webui-deploy.git
   cd open-webui-deploy
2. Use these commands:
   ```bash
   cd open-webui-deploy
   docker compose up -d
3. Install an ollama model (in this case llama3.2:1b)
   ```bash
   docker exec ollama-test ollama pull llama3.2:1b
   #then check if it was successfully downloaded
   docker exec ollama-test ollama list

## You can download different models on https://ollama.com/library and download them locally following step 3
