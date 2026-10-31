# ⚡ AIDEVOPS — Official Documentation & Setup Portal

> **The Public Landing Page, Developer Guidance, and Enterprise Zero-Trust Guarantee Portal for [AIDEVOPS](https://github.com/Shubhamjkd01/AI_DevOps_X).**

This repository contains the standalone, high-performance web portal deployed on **Vercel**. It provides developers, organizations, and open-source contributors with a complete onboarding guide, laptop setup instructions, and code privacy guarantees.

---

## 🔗 Architecture & Repositories

| Repository | Purpose | Tech Stack | Live Link |
|---|---|---|---|
| **[AI_DevOps_X](https://github.com/Shubhamjkd01/AI_DevOps_X)** | **Core Engine & Agent Backend** (CI/CD self-healing, Google Gemini, AST validator, Streamlit dashboard) | Python 3.11, FastAPI, FAISS, Docker | [Core Repo ↗](https://github.com/Shubhamjkd01/AI_DevOps_X) |
| **aidevops_portal** *(This Repo)* | **Public Docs & Landing Portal** (Developer onboarding, where-to-change guide, security guarantees) | HTML5, CSS3 Glassmorphism, Vanilla JS | Deployed on Vercel |

---

## 📄 Pages Included

1. **`index.html` (`/`)**: Main landing page with animated terminal simulation, architecture overview, and About the Developer (Shubham).
2. **`docs.html` (`/docs`)**: Step-by-step developer laptop setup guide, including:
   - Prerequisites (Python 3.10+, Git, Gemini API key)
   - **"Where to Change & What to Edit"** critical file map (`.env`, `server/config.py`, `github_agent/agent.py`)
   - Connecting local machines to GitHub webhooks using Ngrok
   - Running FastAPI and Streamlit locally
   - Dry-run mock CI failure testing command
3. **`security.html` (`/security`)**: Enterprise Zero-Trust guarantee:
   - 4 Inviolable Security Pillars (One-way outbound webhooks, zero code retention, zero model training, AST syntax safety checks)
   - Architecture comparison table: Traditional 3rd-Party SaaS vs. AIDEVOPS Zero-Trust
   - Air-gapped on-premise & private VPC deployment guide
   - Security & privacy FAQ

---

## 🚀 1-Click Vercel Deployment

1. Create a new repository on GitHub named `aidevops-portal` or `aidevops-web`.
2. Push this directory to your new repo.
3. Import the repo into [Vercel](https://vercel.com).
4. Click **Deploy** — your documentation site will be live instantly with zero configuration!

---

## 👨‍💻 Created by
**Shubham** ([@Shubhamjkd01](https://github.com/Shubhamjkd01))  
*Autonomous DevOps & AI Systems Architect*
