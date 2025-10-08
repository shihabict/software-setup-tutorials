## 🚀 Local AI Chatbot Setup Guide

A complete guide to setting up your own ChatGPT-like interface running locally on your Mac using Ollama and Open WebUI.

## 📋 What You'll Build

By following this guide, you'll have:
-  Ollama running locally on your Mac
-  A beautiful web interface(Open WebUI) to chat with your AI.
-  Complete privacy- everything runs on your machine!

## 🎯 Prerequisites
- Mac (works on both Intel and Apple Silicon M1/M2/M3)
- 8GB+ RAM (16GB recommended)
- 10GB+ free disk space (for models)
- Internet connection (for initial setup)

## 📦 Part 1: Install Ollama
### Step 1: Download Ollama
- Visit https://ollama.com/download
- Click "Download for macOS"
- Open the downloaded .dmg file
- Drag Ollama to your Applications folder
- Open Ollama from Applications

### Step 2: Verify Installation
Open Terminal and run:

```ollama --version```

You should see the version number ```(e.g., ollama version 0.x.x)```

## 🤖 Part 2: Download Your First LLM
### Step 1: Download a Model

```ollama pull deepseek-r1:7b```

### Step 2: Test Your Model

```ollama run deepseek-r1:7b```

You should see a chat interface! Try asking: ```Hello, how are you?```

To exit, type:``` /bye```
