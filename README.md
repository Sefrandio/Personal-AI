# My Personal AI Assistant (DeepSeek-R1 + Open WebUI)

This project is a fully self-hosted personal AI assistant running locally on Ubuntu. It leverages **Ollama** as the inference engine and **Open WebUI** for a ChatGPT-like interface. Secure remote access is managed via **Tailscale**, allowing access from mobile devices without exposing ports to the public internet.

## 🚀 Key Features
- **100% Privacy:** All chat data and models are stored locally on your machine.
- **GPU Acceleration:** Fully utilizes NVIDIA CUDA for fast inference speeds.
- **Tailnet Access:** Secure remote access via Tailscale (no port forwarding required).
- **Models:** Optimized for DeepSeek-R1, Llama 3.1, and other Ollama-compatible models.

## 🛠️ System Requirements
- **OS:** Ubuntu 22.04 / 24.04 (LTS recommended)
- **Hardware:** NVIDIA GPU with installed drivers
- **Software:** - Docker & Docker Compose
  - NVIDIA Container Toolkit
  - Tailscale
  - Ollama (Running natively on host)
