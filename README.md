# 💸 AI Influencer Autopilot (v2026)
## "The Invisible Media Empire Builder"

> **"You are not a content creator. You are a MEDIA MOGUL."**

![n8n](https://img.shields.io/badge/Workflow-n8n-FF6D5A?style=for-the-badge&logo=n8n)
![OpenAI](https://img.shields.io/badge/Brain-GPT--4o-412991?style=for-the-badge&logo=openai)
![Status](https://img.shields.io/badge/Status-Production%20Ready-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)

---

## 🚨 What Is This?

This is **NOT** just another mundane n8n workflow. It is a **fully autonomous media company** compressed into an executable workflow.

Most automation tutorials sell simple copy-paste text scrapers. **This system is fundamentally different.** It is engineered to **reverse-engineer the Instagram & TikTok recommendation algorithms**. It monitors top viral videos in real-time, deconstructs why they went viral (Visuals + Audio + Context), and rewrites high-converting video scripts tailored specifically for your **Virtual AI Influencer** (such as Aitana Lopez or Lil Miquela).

### 💀 Core Philosophy
Social media is an attention war. You are competing against algorithms that process audience retention data in milliseconds.
*   **The Outdated Way:** Waiting for "inspiration", manual editing, burnout, and inconsistent posting.
*   **The Autonomous Way:** Mining **Verified Viral Datasets** and transforming algorithmic momentum into an unfair competitive advantage.

---

## ⚡ Key Architectural Features

```
┌────────────────────────────────┐       ┌────────────────────────────────┐
│   Apify Video Scraper          │ ────> │   Multimodal Vision Engine     │
│   (Thumbnail + Transcript)     │       │   GPT-4o Scene & Mood Analysis │
└────────────────────────────────┘       └────────────────────────────────┘
                                                         │
                                                         ▼
┌────────────────────────────────┐       ┌────────────────────────────────┐
│   Google Sheets Database       │ <──── │   Persona & POV Injection      │
│   & Automated Dispatch         │       │   Acting Directives & Captions │
└────────────────────────────────┘       └────────────────────────────────┘
```

### 1. 👁️ Multimodal Vision Intelligence ("The Eye")
Unlike primitive scrapers that only parse caption text, this system analyzes **Visual Context & Scene Framing**:
*   **Inputs:** Cover Thumbnail + Audio Transcript + Metric Engagement Velocity.
*   **Analysis:** GPT-4o examines the visual setting (e.g., gym workout, luxury car vlog, tech desk setup).
*   **Output:** Generates a script complete with **scene-aware acting directives** (e.g., `[Wipes sweat from forehead] "Guys, leg day was brutal..."`).

### 2. 🛡️ Fault-Tolerant Pipeline ("The Shield")
*   **Automated Retry Loops:** Exponential backoff if social APIs rate-limit or fail.
*   **Input Guardrails:** Gracefully handles missing captions or audio without breaking execution batches.
*   **Batched Throughput:** Processes top viral content in chunks of 5 for optimal token efficiency.

### 3. 🧠 Persona & POV Injection ("The Soul")
It doesn't merely summarize; it executes **Automated Creative Direction**:
*   Converts dry third-person commentary into relatable **First-Person POV** influencer narratives.
*   Embeds emotional anchors and physical cues: `[Laughs]`, `[Deep sigh]`, `[Points to camera]`.

---

## 🛠️ Installation & Setup Guide

### Prerequisites
*   [n8n](https://n8n.io/) (Self-Hosted instance or n8n Cloud)
*   **Apify Account** (For Instagram/TikTok video scraping actor)
*   **OpenAI API Key** (GPT-4o access)
*   **Google Account** (Google Sheets for data logging & Gmail for alerts)

### Step 1: Import the Workflow
1.  Download `n8n.json` from this repository.
2.  Open your n8n interface.
3.  Click **"Import from File"** and select `n8n.json`.

### Step 2: Configure Credentials
Within your n8n workflow canvas, configure credentials for the following nodes:
*   `Apify API Key` -> For **Scrape Hashtag** & **Transcribe Video** nodes.
*   `OpenAI API Key` -> For **AI Agent / GPT-4o** processing node.
*   `Google Sheets OAuth2` -> For **Append to Sheet** node.

### Step 3: Set Your Niche Target
Open the configuration node and specify your target parameters:
```json
{
  "target_hashtags": ["fitness", "lifestyle", "techvlog"],
  "min_view_count": 50000,
  "language": "en",
  "persona_tone": "charismatic, energetic, direct"
}
```

---

## 🎯 Use Case Scenarios

*   **Virtual AI Influencer Scaling:** Fuel AI avatar pipelines (HeyGen, Midjourney, ElevenLabs) with pre-validated viral scripts.
*   **Faceless YouTube Shorts / TikTok Channels:** Fully automated research and scripting for daily mass-publishing.
*   **Affiliate & E-Commerce Arbitrage:** Turn trending viral hooks into high-converting product recommendation scripts.

---

**Maintained by:** [xCodeWraith DEV.](https://github.com/xCodeWraith)  
**License:** [MIT](LICENSE)
