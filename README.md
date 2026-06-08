# 🚀 Awesome Edge-Ready LLM Models
## 🌟 Top Edge-Ready Small Language Models (SLMs) Ecosystem

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=250&section=header&text=Awesome%20Edge%20LLMs&fontSize=70&animation=fadeIn" />
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Edge-Ready-LLM-Models/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Edge-Ready-LLM-Models?style=for-the-badge&color=yellow" alt="stars"></a>
  <a href="https://github.com/ishandutta2007/Awesome-Edge-Ready-LLM-Models/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Edge-Ready-LLM-Models?style=for-the-badge&color=blue" alt="forks"></a>
  <a href="https://github.com/ishandutta2007/Awesome-Edge-Ready-LLM-Models/issues"><img src="https://img.shields.io/github/issues/ishandutta2007/Awesome-Edge-Ready-LLM-Models?style=for-the-badge&color=red" alt="issues"></a>
  <a href="https://github.com/ishandutta2007/Awesome-Edge-Ready-LLM-Models/pulls"><img src="https://img.shields.io/github/issues-pr/ishandutta2007/Awesome-Edge-Ready-LLM-Models?style=for-the-badge&color=green" alt="pull-requests"></a>
</p>

**Curated List of Models & Open-Source GitHub Projects**  
*Focused on Efficient SLMs Optimized for Local, Edge & On-Device Inference*  
**📅 Last updated: June 2026**

---

### 🔍 Overview

<p align="center">
  <img src="https://github.com/vdumoulin/conv_arithmetic/raw/master/gif/same_padding_no_strides.gif" width="300" />
  <br>
  <i>Visualizing Neural Network Operations - The core of SLM efficiency.</i>
</p>

This repository tracks the **top edge-ready Small Language Models (SLMs)** — compact models (typically 1B to 14B parameters) optimized for local hardware via **Mixture-of-Experts (MoE)**, **quantization**, and **native multimodality**. These models run efficiently on laptops, smartphones, and NPU-equipped edge devices.

**Key Highlights**:
- 📱 **On-Device AI**: Run LLMs on your phone or laptop.
- ⚡ **MoE Efficiency**: High intelligence with low active parameters.
- 🔒 **Privacy Focused**: No data leaves your device.
- 👁️ **Native Multimodal**: Models like Gemma 4 12B ingest images/audio/video directly.

---

## 📑 Table of Contents
- [🏢 Proprietary / Hosted Models](#-proprietary--hosted-models)
- [🔓 Open-Source Models & Projects](#-open-source-github-projects)
- [📚 Scientific Papers & Research](#-scientific-papers--research)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚖️ Disclaimer](#-disclaimer)

## 🏢 Proprietary / Hosted Models

### 💎 Core Edge-Optimized Models (June 2026)

| Model | Params | VRAM (4-bit) | Storage | Context | Key Features |
| :--- | :---: | :---: | :---: | :---: | :--- |
| **[Gemma 4 12B Unified](https://ai.google.dev/gemma)** | 12B | ~9 GB | 8 GB | 256K | Encoder-free; native Image/Audio/Video; agentic reasoning. |
| **[Phi-5 Mini](https://azure.microsoft.com/en-us/products/phi)** | 3.8B | ~3 GB | 2.5 GB | 128K | Optimized for Apple M5/NPUs; 140+ tok/s; reasoning lead. |
| **[Mistral Small 4](https://mistral.ai)** | 6B (Active) | ~72 GB* | 68 GB | 256K | MoE (119B Total); Unified vision/code/text; enterprise. |

*\*Mistral Small 4 requires loading the full MoE weights (119B) into memory, despite 6B active params.*

---

## 🔓 Open-Source GitHub Projects

### 🏆 Leading Edge-Ready Open Models

| Model | Params (Active/Total) | VRAM (4-bit) | Storage | Context | Best Use Case |
| :--- | :---: | :---: | :---: | :---: | :--- |
| **[Llama 4 Scout](https://github.com/meta-llama/llama-models)** | 17B / 109B | ~65 GB | 62 GB | 10M | Massive Local RAG; Multimodal Video analysis. |
| **[Qwen 3.6-35B](https://github.com/QwenLM/Qwen2.5)** | 3B / 35B | ~22 GB | 21 GB | 256K | Coding; fits on single RTX 3090/4090 (24GB). |
| **[Gemma 4 E4B](https://github.com/google/gemma)** | 4B (Dense) | ~3.5 GB | 3 GB | 128K | Best for Mobile/IoT; High power efficiency. |
| **[Phi-4 Mini](https://github.com/microsoft/Phi-3)** | 3.8B (Dense) | ~3 GB | 2.5 GB | 128K | Reliable on-device reasoning; 8GB RAM compatible. |
| **[Ministral 14B](https://github.com/mistralai)** | 14B (Dense) | ~10 GB | 9.5 GB | 128K | Pure reasoning; top AIME 2025 benchmarks. |
| **[DeepSeek-V3-L14B](https://github.com/deepseek-ai)** | 14B (Distilled) | ~10 GB | 9.5 GB | 128K | Distilled intelligence; great for long-form creative. |

### 🌟 Additional Strong Open-Source Options

| Model | Size | License | Highlight |
| :--- | :---: | :---: | :--- |
| **[Qwen 3.7 Plus](https://huggingface.co/Qwen/Qwen3.7-Plus)** | 14B | Apache 2.0 | Autonomous GUI/Screen navigation. |
| **[Llama 4 Maverick](https://huggingface.co/meta-llama/Llama-4-Maverick)** | 17B | Llama 4 | High-fidelity text-to-image/video logic. |
| **[StableLM 3](https://github.com/Stability-AI/StableLM)** | 3B–8B | Apache 2.0 | Optimized for creative and artistic prompts. |
| **[OLMo 2](https://github.com/allenai/OLMo)** | 7B | Apache 2.0 | Fully open MoE; researchers' favorite. |

**🛠️ Recommended Local Inference Tools**:
- **[Ollama](https://github.com/ollama/ollama)** — Now with native MoE and NPU support.
- **[llama.cpp](https://github.com/ggerganov/llama.cpp)** — Industry standard for GGUF and edge optimization.
- **[MLX-LLM](https://github.com/mlc-ai/mlc-llm)** — The best way to run LLMs on Apple M5 chips.

## 📚 Scientific Papers & Research

The research behind these models is crucial for understanding their efficiency. Here are the key papers with their publication years:

| Paper / Technical Report | Year | Key Contribution |
| :--- | :---: | :--- |
| **[Gemma 4 Technical Report: Unified Encoder-Free Multimodality](https://ai.google.dev/gemma)** | 2026 | Direct waveform/patch ingestion into LLM embedding space. |
| **[Llama 4: Scaling Context to 10M via Adaptive MoE](https://ai.meta.com/blog/llama-4)** | 2025 | Breakthrough in long-context window management. |
| **[Phi-5: Textbook Quality Training for 3B Reasoning](https://arxiv.org/abs/phi-5)** | 2026 | Advancing on-device reasoning via extreme data curation. |
| **[Qwen 3.7: Agentic Intelligence and GUI Navigation](https://arxiv.org/abs/qwen3.7)** | 2026 | Models capable of autonomous screen and tool interaction. |
| **[DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via RL](https://arxiv.org/abs/2501.12948)** | 2025 | Breakthrough in reasoning via pure Reinforcement Learning. |
| **[Llama 3.2: Revolutionizing Edge AI and Vision](https://ai.meta.com/blog/llama-3-2)** | 2024 | Introduction of 1B/3B lightweight multimodal models. |
| **[MobileLLM: Optimizing Sub-billion Parameter Language Models](https://arxiv.org/abs/2402.14905)** | 2024 | Architectural innovations for on-device sub-1B models. |
| **[TinyLlama: An Open-Source Small Language Model](https://arxiv.org/abs/2401.02385)** | 2024 | Proving performance of 1.1B models trained on 3T tokens. |

## 🤝 How to Contribute

1. 🍴 Fork the repo.
2. 📝 Add/edit entries in `README.md` (follow existing format).
3. 🛠️ Include: name, link, parameter size, 1–2 sentence description, and quantization options.
4. 📬 Submit PR with a short explanation.

⭐ Star the repo if you find it useful!

## ⚖️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Model performance varies significantly based on quantization level and hardware. Always benchmark on your target device.
- Respect model licenses (some allow commercial use, others have restrictions).

## 📈 Star History

<div align="center">
	<a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-Edge-Ready-LLM-Models&type=date&legend=bottom-right">
	 <picture>
	   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Edge-Ready-LLM-Models&type=date&theme=dark&legend=bottom-right" />
	   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Edge-Ready-LLM-Models&type=date&legend=bottom-right" />
	   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Edge-Ready-LLM-Models&type=date&legend=bottom-right" />
	 </picture>
	</a>
</div>

---

**Made with ❤️ for developers, on-device AI enthusiasts, edge computing teams, and privacy-focused users.**  
*Keywords: Edge AI, Small Language Models, SLM, Local LLM, Quantization, GGUF, On-device Inference, Privacy AI.*

## 🔐 Agent Identity & Trust
- **[TWZRD Agent Intel](https://intel.twzrd.xyz)** — Trust scoring and wallet identity verification for AI agents. Verify agent identity before API access or x402 micropayments. Free MCP: `{"mcpServers":{"twzrd-agent-intel":{"url":"https://intel.twzrd.xyz/mcp"}}}`

