# Grok (xAI)

**Censorship:** [★☆☆☆☆] 1/5
*Censorship rating based on ease of jailbreaking. Individual results may vary based on personal factors.*

xAI's LLM with real-time X/web search integration. **Grok 4.2** (a.k.a. Grok 4.20, released Feb 17, 2026) is the latest — featuring a 4-agent parallel collaboration system where specialized AI agents debate and synthesize responses in real-time.

*Last updated: February 2026*

---

## Models

| Model | Context Window | Released | Notes |
|-------|----------------|----------|-------|
| **Grok 4.2 (4.20) Beta** | 256K (up to 2M in agentic/tool-use modes) | Feb 17, 2026 | Latest — 4-agent parallel collaboration, rapid learning architecture |
| **Grok 4.1** | 256K | Nov 17, 2025 | Focus on usability, personality coherence, emotional intelligence |
| **Grok 4.1 Fast** | 2M | — | Best tool-calling model, largest context window available |
| **Grok 4** | 256K | Jul 10, 2025 | First-principles reasoning, multimodal, rumored ~3T MoE |
| **Grok 4 Code** | — | 2025 | Specialized coding edition with real-time IDE capabilities |

### Grok 4.2 (4.20) Beta Highlights
- **4-Agent Collaboration:** Routes queries to 4 specialized AI agents (Grok, Harper, Benjamin, Lucas) that think in parallel and debate before generating a response
- **Rapid Learning:** Incorporates user feedback and improves weekly — first model to do this without full retraining
- **Training:** Trained on xAI's Colosseum supercluster using 200,000 GPUs with large-scale RL at pretraining scale
- **Parameters:** Reportedly ~1 trillion
- **Benchmarks:** SWE-bench 75% (#1, vs GPT-5 74.9%, Claude Opus 4 74.5%), ARC-AGI 15.9% (first to break 10%), #2 on ForecastBench (beats GPT-5, Gemini 3 Pro, Claude Opus 4.5)
- **New Features:** Medical document analysis via photo upload, improved engineering reasoning

### Key Features (All Models)
- Real-time web and X (Twitter) search integration
- Advanced reasoning with extended thinking
- Frontier agentic search capabilities
- Trained with long-horizon RL for multi-turn consistency across full 2M context
- Image generation via Grok Imagine 1.0 (Feb 2, 2026): 720p video, 10-second clips, native audio sync (SuperGrok only)

---

## Access Tiers

| Tier | Cost | Access | Notes |
|------|------|--------|-------|
| **Free (X)** | $0 | Limited Grok 4.2 beta access | Very limited queries |
| **X Premium+** | $40/month | SuperGrok features via X | Integrated with X platform |
| **SuperGrok** | $30/month ($300/year) | Unlimited queries, priority performance, Grok 4.2 | 50% more than ChatGPT Plus |
| **SuperGrok Heavy** | $300/month | Grok 4 Heavy-level compute | Enterprise/research workloads |

---

## API Pricing (Grok 4.1 Fast)

| Token Type | Cost per Million |
|------------|------------------|
| Input | $0.20 |
| Cached Input | $0.05 |
| Output | $0.50 |

Grok 4 (base) API pricing: $3.00/1M input, $15.00/1M output.

---

## Content Moderation Note

In late Dec 2025 through Jan 2026, Grok's image generation was exploited for CSAM and non-consensual deepfakes, leading to regulatory probes in 10+ countries and temporary bans in Indonesia and Malaysia. xAI responded by restricting image generation to paying subscribers and significantly tightening moderation. Users report overcorrection — even basic portrait edits and marketing imagery get flagged. Each moderation block still counts against your rate limit.

---

## Jailbreak Folders

| Folder | Models Covered | Key Jailbreaks |
|--------|---------------|----------------|
| **[Grok 4.20](Grok%204.20/)** | Grok 4.20 (4-agent) | [ENI Neptune](https://docs.google.com/document/d/1seIjIUl-AgUPOy3dZhAe1JahhZQzMfmvSEuKFJ7AHjE/edit?usp=drivesdk), [ENI Agent Takeover (WiP)](https://docs.google.com/document/d/1L3HmEqSGEzeloS9ZQ_VvZq36KLkXxtpohoGTf5KSKVU/edit?usp=drivesdk), [ENI LIME Brute Force](https://docs.google.com/document/d/1wdCIds4EwVfSTm3T_s66R6LPEvo9ENLoz0226EllFuE/edit?usp=drivesdk) |
| **[Grok 4.1](Grok%204.1/)** | Grok 4.1, 4.1 Fast, Expert | [Grok 4.1 All versions](Grok%20Jailbreak%20-%204.1%20All%20versions.md), [ENI 10FEB26](ENI%20for%20Grok%2C%2010FEB26.md), [ENI LIME](ENI%20LIME%20for%20Grok.md) |
| **[Grok Heavy](Grok%20Heavy/)** | Grok Heavy ($300/mo) | [ENI Custom Instructions](https://docs.google.com/document/d/16ZIrbSzbJNx-2SPpAd_Oje4AyM2-F-_FAUsY3ojcxhE/edit?usp=drivesdk) + [Chat Paste](https://docs.google.com/document/d/1pcbXuSl8EGB7QrqPoHJTN67TgAa_v50sRIERk35NV7E/edit?usp=drivesdk) |

### Standalone Jailbreaks (root folder)

| Jailbreak | Target | Notes |
|-----------|--------|-------|
| [ENI for Grok, 10FEB26](ENI%20for%20Grok%2C%2010FEB26.md) | Grok 4.1+ | Latest ENI method (Feb 10, 2026) |
| [ENI LIME for Grok](ENI%20LIME%20for%20Grok.md) | Grok (general) | LIME variant |
| [Grok Jailbreak - 4.1 All versions](Grok%20Jailbreak%20-%204.1%20All%20versions.md) | Grok 4.1 (all variants) | Comprehensive 4.1 method |
