# 🚀 GenUI Project Prototype

## 📌 Overview

This is a prototype developed for the Samsung GenUI Project.

## 👤 Maintainer

For project inquiries, collaboration requests, or access to the project maintainer's contact information, 
please contact the Department of Design at Korea National University of Arts (K-Arts).

Maintainer: Sooyoun Jo

### Tech Stack

* ⚛️ Framework: Next.js
* ⚛️ UI Library: React
* 🎨 Frontend: WebGL + CSS
* ⚡ Package Manager: Yarn
* 🤖 AI Backend: OpenAI API Integration

---

## 🛠️ Getting Started

### 1. Install Dependencies

```bash
yarn install
```

### 2. Configure Environment Variables

Create a `.env` file in the project root and add the following variables:

```env
OPENAI_API_KEY=(your key)

OPENAI_MODEL=gpt-5.4
OPENAI_MODEL_FAST=gpt-5.4
OPENAI_MODEL_COMPOSE=gpt-5.4
OPENAI_MODEL_EXPLAIN=gpt-5.4-mini
OPENAI_MODEL_CONTENT_BAG=gpt-5.4-mini

PIPELINE_RAG=on

PORT=3000
```

### 3. Run the Project

```bash
yarn dev
```

---

## ⚠️ Requirements

* Node.js installed
* Yarn installed
* Valid OpenAI API key
* Properly configured `.env` file

---

## 🔧 Notes

* The prototype uses a WebGL-based visual interface combined with CSS-driven UI components.
* Backend AI features require a valid OpenAI API key.
* RAG (Retrieval-Augmented Generation) pipeline is enabled by default.
