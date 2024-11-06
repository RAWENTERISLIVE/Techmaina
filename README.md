# Techmaina
## Steps for Software Install

### 1. VS Code Install
https://code.visualstudio.com/sha/download?build=stable&os=win32-x64-user

### In VS Code

Open Desktop Folder

Then In Terminal from the top Bar

write 

```bash
pip install gTTS
```

### Or

Windows PowerShell

```bash
pip install gTTS
```

### 2. Ollama

https://ollama.com/download/OllamaSetup.exe

Windows Powershell

```bash
ollama pull mistral
ollama pull phi3
```

### 3. Docker Install

[https://desktop.docker.com/win/main/amd64/Docker Desktop Installer.exe?utm_source=docker&utm_medium=webreferral&utm_campaign=docs-driven-download-win-amd64&_gl=1*1oz3hfz*_gcl_au*MTcyMTkxNDU3Ni4xNzI2MzgxNTU4*_ga*MjA2NzEzODI1Ny4xNzI2MzgxNTU5*_ga_XJWPQMJYHQ*MTcyNzg5MTUzMC41LjEuMTcyNzg5MTU2MC4zMC4wLjA](https://desktop.docker.com/win/main/amd64/Docker%20Desktop%20Installer.exe?utm_source=docker&utm_medium=webreferral&utm_campaign=docs-driven-download-win-amd64&_gl=1*1oz3hfz*_gcl_au*MTcyMTkxNDU3Ni4xNzI2MzgxNTU4*_ga*MjA2NzEzODI1Ny4xNzI2MzgxNTU5*_ga_XJWPQMJYHQ*MTcyNzg5MTUzMC41LjEuMTcyNzg5MTU2MC4zMC4wLjA).

In Docker terminal (Bottom Right)
```
docker run -d -p 3000:8080 --add-host=host.docker.internal:host-gateway -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main
```

## Competition

Video - [https://www.pexels.com](https://www.pexels.com/) , [https://www.videvo.net](https://www.videvo.net/) , [https://www.shutterstock.com](https://www.shutterstock.com/) 

AI - Local Ollama , http://35.209.38.83:3000/ , ai.carbonguardian.tech:3000

TTS - gtts-cli "" --output hello.mp3
