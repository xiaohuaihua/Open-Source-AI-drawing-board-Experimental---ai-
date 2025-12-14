# Open-Source-AI-drawing-board-Experimental---ai-
An open-source AI canvas built to lower the barrier for AI art education. Developed through a multi-day collaborative process with AI, where I architected the logic to solve API fragmentation and the AI assisted in implementation. It runs purely in the browser, offering a cost-effective alternative for beginners.
# Open Source AI Drawing Board (Experimental)

[English](README.md) | [中文](README_zh.md)

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-0.37-green.svg)
![Vue.js](https://img.shields.io/badge/Made%20with-Vue.js-42b883.svg)

> An open-source, node-based AI canvas running entirely in the browser.

## 📖 Introduction

This project is a visual interface for Generative AI. It allows users to drag and drop nodes to construct image generation workflows flexibly.

Designed as a **Client-Side (Pure Frontend)** application, it connects directly to AI APIs (OpenAI/Gemini) from your browser. This eliminates the need for high-end hardware or complex backend installations, making it an accessible tool for learning and experimentation.

## 💡 Why I Built This? (The Story)

I have been involved in **AI Art Popularization and Education**. During this process, I identified two major barriers for beginners and teachers:
1.  **High Costs**: Many platforms require monthly subscriptions, making it difficult to share workflows or for students to practice freely.
2.  **Hardware Limits**: Local tools (like ComfyUI) often require powerful GPUs, which not everyone possesses.

I wanted to create a solution that lowers these barriers.
*   **For Beginners**: A tool that runs on most computers with a browser, sufficient for learning the logic of AI workflows.
*   **The Goal**: To solve the **API Fragmentation** problem (unifying OpenAI and Google Gemini protocols) so users can focus on creativity rather than technical configurations.

## 🤝 Development Journey: Human-AI Collaboration

I want to be transparent: **This project was built through a collaboration between a Human Product Manager and AI.**

This process represents a multi-day journey of iterative product development:
*   **My Role (Product Manager & Creator)**: I identified the user needs in AI education, conceptualized the product features, and defined the logic to handle complex API behaviors (such as Gemini's protocol shifts). I directed the development strategy and verified the results.
*   **AI's Role (Developer)**: Under my guidance, the AI assisted in writing the code, implementing the UI logic, and iterating on specific functions to meet the product requirements.

We solved problems step-by-step—from basic node rendering to complex data handling. This project stands as a sincere experiment in how **Product Thinking** can leverage AI to build real software.

## ✨ Key Features

*   **Adaptive Parser**: Automatically handles various API response formats (Base64, JSON, URLs) from different providers and proxies.
*   **Smart Routing**: Intelligently switches protocols between OpenAI and Google Gemini based on your model selection.
*   **Local Gallery (IndexedDB)**: Saves your generated images persistently in the browser database, solving the issue of data loss upon refresh.
*   **Low Barrier to Entry**: No backend server required. Your API keys and data never leave your device.

## 🚀 Quick Start

No installation needed. No Node.js required.

1.  **Download**: Clone this repo or download the `index.html` file.
2.  **Open**: Double-click `index.html` to open it in Chrome, Edge, or Firefox.
3.  **Setup**:
    *   Click **Settings** (top right).
    *   Add your API Key (OpenAI or Gemini).
    *   Start creating!

## 🛠️ Tech Stack

*   **Framework**: Vue.js 3 (Composition API)
*   **Styling**: Tailwind CSS
*   **Data Storage**: IndexedDB (via idb-keyval)
*   **Tools**: JSZip (for downloading images)

## 📄 License

This project is licensed under the **MIT License**.

---
*Created by Junjun Huai- 2025*
