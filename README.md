# 🔍 DeepLens

<div align="center">

### AI-Powered Image Captioning & Semantic Image Search

Generate intelligent image captions and perform semantic image retrieval using a Vision-Language Model (MiniCPM), all while preserving user privacy through local inference.

[![React](https://img.shields.io/badge/React-18-61DAFB?logo=react)]()
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript)]()
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi)]()
[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python)]()
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css)]()

[🚀 Live Demo](https://www.linkedin.com/posts/saatvik-goel-571644276_deeplens-ai-machinelearning-ugcPost-7319417820079869953-JG_D/) •
[📄 Research Paper](https://drive.google.com/file/d/1wQJCo13YLV5oA7Sx1a42A9a1Uof40XIV/view?usp=sharing)

</div>

---

## 📖 Overview

DeepLens is an AI-powered web application that combines **Vision-Language Models (VLMs)** with a modern web interface to automatically generate contextual image captions and perform semantic image search using natural language queries.

Unlike traditional cloud-based solutions, DeepLens emphasizes **privacy-first AI** by supporting **local model inference**, ensuring user images remain on the device while delivering fast and intelligent image understanding.

---

## ✨ Features

- 🖼️ Context-aware image caption generation
- 🔍 Semantic image search using natural language
- ⚡ Fast inference powered by MiniCPM Vision-Language Model
- 🔒 Local model execution for enhanced privacy
- 🎨 Modern and responsive React interface
- 🚀 REST API integration using FastAPI
- 📱 Clean, intuitive user experience

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| **Frontend** | React, TypeScript, Vite, Tailwind CSS |
| **Backend** | FastAPI, Python |
| **AI Model** | MiniCPM Vision-Language Model |
| **ML Framework** | PyTorch, Hugging Face Transformers |
| **API** | REST API |

---

# 🏗️ System Architecture

```text
                User Uploads Image
                        │
                        ▼
          React + TypeScript Frontend
                        │
                        ▼
               FastAPI Backend API
                        │
                        ▼
        MiniCPM Vision-Language Model
                        │
        ┌───────────────┴───────────────┐
        ▼                               ▼
 Contextual Caption Generation   Semantic Embeddings
        │                               │
        └───────────────┬───────────────┘
                        ▼
              Display Results to User
```

# 📂 Project Structure

```text
DeepLens
│
├── project
│   ├── src
│   │   ├── App.tsx
│   │   ├── main.tsx
│   │   └── ...
│   │
│   ├── public
│   ├── package.json
│   ├── vite.config.ts
│   ├── tailwind.config.js
│   └── ...
│
└── README.md
```

---

# 💡 Motivation

Image captioning and image retrieval systems are becoming increasingly important across accessibility, digital asset management, and intelligent search applications. However, many existing solutions depend heavily on cloud APIs, introducing privacy concerns and increased latency.

DeepLens addresses these limitations by integrating a locally deployable Vision-Language Model capable of understanding images, generating meaningful captions, and enabling semantic image search while keeping user data private.

---

# 🚀 Future Enhancements

- 🎙️ Voice-based image search
- 📄 OCR integration
- 📱 Mobile application
- ☁️ Cloud deployment
- 👥 User authentication
- 🖼️ Image similarity search
- 🌍 Multi-language caption generation

---

# 📊 Project Highlights

- ✅ Vision-Language Model powered application
- ✅ Local AI inference for enhanced privacy
- ✅ Context-aware image captioning
- ✅ Semantic image retrieval
- ✅ Modern React + FastAPI architecture
- ✅ Research-backed implementation

---

# 📄 Research Paper

This project is accompanied by a research paper describing its architecture, methodology, and evaluation.

📖 **Read the Paper:**  
https://drive.google.com/file/d/1wQJCo13YLV5oA7Sx1a42A9a1Uof40XIV/view?usp=sharing

---
