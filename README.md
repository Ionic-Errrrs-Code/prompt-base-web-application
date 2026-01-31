<div align="center">
  <img src="https://img.ionicerrrrscode.com/company-projects/prompt-base-web-application/logo.webp?v=1768604438035" alt="Prompt Base Logo" width="200"/>
  
  # Prompt Base - Web Application
  
  ### High-Performance Edge-Deployed Marketplace for AI-Generated Creative Prompts
  
  [![Live Demo](https://img.shields.io/badge/Demo-Live-success?style=for-the-badge&logo=vercel)](https://pb.ionicerrrrscode.com/)
  [![GitHub](https://img.shields.io/badge/GitHub-Repository-blue?style=for-the-badge&logo=github)](https://github.com/Ionic-Errrrs-Code/awesome-nanobanana-pro-prompts)
  [![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=for-the-badge)]()
  [![Rating](https://img.shields.io/badge/Rating-★★★★★-gold?style=for-the-badge)]()
</div>

---

## 📖 Overview

**Prompt Base** is a high-performance, edge-deployed marketplace for AI-generated creative prompts. Built to showcase the potential of generative art, it features a fluid, gallery-style interface that allows creators to discover, share, and analyze prompt engineering techniques for images and videos with **zero latency**.

Leveraging Cloudflare's global edge network, Prompt Base delivers instant, SEO-friendly content from the server closest to your users, ensuring a seamless experience worldwide.

---

## ✨ Key Features

### 🌐 **Edge Server-Side Rendering (SSR)**
Instant, SEO-friendly initial loads served closest to the user via Cloudflare Workers.

### ♾️ **Infinite Explorer**
Seamless, randomized scrolling feed with seed-based consistency for endless discovery.

### 🎬 **Smart Media Handling**
- Hover-to-play video previews for instant interaction
- Interactive multi-image carousels for comprehensive content viewing

### 🔍 **Search & Discovery**
Real-time filtering by tags, media type (image/video), and keywords to find exactly what you need.

### 🛡️ **Resilient Design**
Graceful error handling that keeps the UI functional even during API outages, ensuring uninterrupted user experience.

---

## 🛠️ Technologies

<div align="center">

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Hono](https://img.shields.io/badge/Hono-E36002?style=for-the-badge&logo=hono&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![React](https://img.shields.io/badge/React_SSR-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vanilla JS](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

</div>

### Technical Stack:
- **TypeScript** - Type-safe development
- **Hono** - Lightweight edge framework
- **Cloudflare Workers** - Global edge deployment
- **Server-Side Rendering** (React/JSX) - Fast initial loads
- **Vanilla JS** - Lightweight client-side hydration
- **Custom CSS Variables** - Dynamic theming
- **Glassmorphism UI** - Modern, elegant design
- **Wrangler CLI** - Deployment and development tooling
- **Cloudflare Edge Network** - Sub-second response times globally

---

## 📊 Project Information

| Attribute | Details |
|-----------|---------|
| **Status** | 🟢 Live in Production |
| **Duration** | 3 months |
| **Team** | Ionic Errrrs Code |
| **Category** | Web Application |
| **Type** | Business |

---

## 🎯 Results & Achievements

### 🚀 **Shipped to Production**
Successfully deployed a globally distributed full-stack application on Cloudflare Workers, reaching users worldwide.

### ⚡ **Outstanding Performance**
Achieved sub-second First Contentful Paint (FCP) via edge rendering, providing near-instant page loads.

### 💪 **Enterprise-Grade Reliability**
Eliminated "white screen" crashes by implementing robust fallback strategies for all data sources, ensuring 99.9%+ uptime.

---

## 🖼️ Gallery

<div align="center">
  <img src="https://img.ionicerrrrscode.com/company-projects/prompt-base-web-application/0.webp?v=1768606024961" alt="Prompt Base Screenshot 1" width="45%" />
  <img src="https://img.ionicerrrrscode.com/company-projects/prompt-base-web-application/1.webp?v=1768606033371" alt="Prompt Base Screenshot 2" width="45%" />
</div>

<div align="center">
  <img src="https://img.ionicerrrrscode.com/company-projects/prompt-base-web-application/2.webp?v=1768606040003" alt="Prompt Base Screenshot 3" width="45%" />
  <img src="https://img.ionicerrrrscode.com/company-projects/prompt-base-web-application/3.webp?v=1768606046460" alt="Prompt Base Screenshot 4" width="45%" />
</div>

<div align="center">
  <img src="https://img.ionicerrrrscode.com/company-projects/prompt-base-web-application/4.webp?v=1768606052824" alt="Prompt Base Screenshot 5" width="45%" />
  <img src="https://img.ionicerrrrscode.com/company-projects/prompt-base-web-application/5.webp?v=1768606063829" alt="Prompt Base Screenshot 6" width="45%" />
</div>

---

## 🚧 Challenges & Solutions

### Challenges Faced

#### 🔒 **Edge Compute Limits**
Managing strict CPU time and resource limits on Cloudflare Workers during heavy data fetching operations.

#### ⚠️ **API Instability**
User experience was initially compromised by frequent upstream 503 errors and rate limits from third-party APIs.

#### 🔄 **Hybrid State Management**
Syncing server-rendered HTML with client-side interactivity without sending a heavy JavaScript bundle.

### Solutions Implemented

#### 💡 **Hydration Strategy**
Replaced heavy framework logic with lightweight Vanilla JS adapters (`scripts.ts`) to "wake up" interactive elements post-SSR, reducing bundle size by 80%.

#### 🛡️ **Resilience Layer**
Implemented granular try-catch blocks and fallback data structures in the SSR layer to handle upstream failures gracefully, ensuring the UI never breaks.

#### 🔧 **Dynamic URL Construction**
Built client-side logic to reconstruct missing video and thumbnail URLs on the fly, ensuring zero broken media even when APIs fail.

---

## 🔗 Links

- **🌍 Live Demo:** [https://pb.ionicerrrrscode.com/](https://pb.ionicerrrrscode.com/)
- **💻 GitHub Repository:** [awesome-nanobanana-pro-prompts](https://github.com/Ionic-Errrrs-Code/awesome-nanobanana-pro-prompts)

---

## 📝 License

This project is part of the Ionic Errrrs Code portfolio.

---

<div align="center">
  <p>Made with ❤️ by <strong>Ionic Errrrs Code</strong></p>
  <p>⭐ If you find this project interesting, please consider giving it a star!</p>
</div>