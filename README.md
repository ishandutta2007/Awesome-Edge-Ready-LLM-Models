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
**📅 Last updated: March 2026**

---

### 🔍 Overview

<p align="center">
  <img src="https://github.com/vdumoulin/conv_arithmetic/raw/master/gif/same_padding_no_strides.gif" width="300" />
  <br>
  <i>Visualizing Neural Network Operations - The core of SLM efficiency.</i>
</p>

This repository tracks the **top edge-ready Small Language Models (SLMs)** — compact models (typically 1B to 4B parameters) optimized for local hardware via **quantization** (4-bit/8-bit), **pruning**, **distillation**, and efficient architectures. These models run efficiently on laptops, smartphones, Raspberry Pi, edge devices, and consumer GPUs with excellent performance for chat, coding, reasoning, and agentic tasks.

**Key Highlights**:
- 📱 **On-Device AI**: Run LLMs on your phone or laptop.
- ⚡ **High Efficiency**: Optimized for low memory and fast inference.
- 🔒 **Privacy Focused**: No data leaves your device.
- 🛠️ **Developer Friendly**: Supports GGUF, ONNX, and AWQ.

---

## 📑 Table of Contents
- [🏢 Proprietary / Hosted Models](#-proprietary--hosted-models)
- [🔓 Open-Source Models & Projects](#-open-source-github-projects)
- [📚 Scientific Papers & Research](#-scientific-papers--research)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚖️ Disclaimer](#-disclaimer)

## 🏢 Proprietary / Hosted Models

### 💎 Core Edge-Optimized Models

- **[Google Gemma 3](https://ai.google.dev/gemma)** 🤖  
  Highly efficient family of models (1B–4B) optimized for on-device and edge inference with strong reasoning and safety features.

- **[Microsoft Phi-4 Mini](https://azure.microsoft.com/en-us/products/phi)** 🔬  
  Exceptional small model (3.8B) with outstanding reasoning capabilities, specifically designed for local and edge deployment.

- **[Mistral Ministral-3B](https://mistral.ai)** 🌪️  
  Powerful 3B parameter model from Mistral AI optimized for speed and efficiency on consumer hardware.

### 🚀 Advanced Models

**Other notable mentions**: Apple Intelligence models (on-device), and various quantized proprietary offerings.

## 🔓 Open-Source GitHub Projects

### 🏆 Leading Edge-Ready Open Models

- **[Meta Llama 3.2](https://github.com/meta-llama/llama-models)** (1B & 3B) 🦙  
  Excellent lightweight models from Meta optimized for edge devices with strong multilingual and reasoning performance. Available in GGUF for Ollama/LM Studio.

- **[Microsoft Phi-3 / Phi-4 Mini](https://github.com/microsoft/Phi-3)** 📐  
  Industry-leading small models (3.8B–4B) with exceptional benchmark performance. Highly optimized for ONNX, GGUF, and mobile/edge deployment.

- **[Google Gemma 2 & Gemma 3](https://github.com/google/gemma)** (2B & 7B variants) 💎  
  Open models with excellent efficiency and instruction-following capabilities. Widely used in quantized form for local inference.

- **[Mistral Ministral-3B / Mistral Small](https://github.com/mistralai)** (open weights versions) 💨  
  High-performance 3B-class models optimized for low-latency inference on laptops and edge hardware.

- **[Qwen2.5-1.5B / Qwen2.5-3B](https://github.com/QwenLM/Qwen2.5)** 🏮  
  Outstanding small models from Alibaba with strong multilingual and coding abilities. Excellent quantized GGUF versions available.

- **[TinyLlama 1.1B](https://github.com/jzhang38/TinyLlama)** 🤏  
  Classic compact model designed specifically for edge and mobile deployment.

- **[StableLM 2 (1.6B–3B)](https://github.com/Stability-AI/StableLM)** 🐎  
  Efficient models from Stability AI optimized for local use and creative tasks.

- **[DeepSeek-R1-Distill-Qwen-1.5B / 7B](https://github.com/deepseek-ai)** 🧠  
  Strong reasoning-focused distilled models perfect for edge devices.

### 🌟 Additional Strong Open-Source Options

- **[Gemma-2-2B](https://huggingface.co/google/gemma-2-2b)** and community fine-tunes
- **[Phi-3.5-Mini](https://huggingface.co/microsoft/Phi-3.5-mini-instruct)** — Highly optimized 3.8B model
- **[H2O-Danube-1.8B](https://huggingface.co/h2oai/h2o-danube-1.8b)** — Efficient European model
- **[MobileLlama / MobileBERT variants](https://github.com/search?q=mobile+llm)**
- **[OLMo-1B / OLMo-2B](https://github.com/allenai/OLMo)** from AllenAI
- **[Snowflake Arctic Embed](https://github.com/Snowflake-Labs)** and other compact embedding models
- **GGUF Quantized Collections** on Hugging Face (TheBloke, bartowski, etc.) for 4-bit/8-bit versions optimized for llama.cpp, Ollama, and LM Studio.

**🛠️ Recommended Local Inference Tools**:
- **[Ollama](https://github.com/ollama/ollama)** — Easiest way to run these models locally
- **[llama.cpp](https://github.com/ggerganov/llama.cpp)** — Best for maximum efficiency and edge devices
- **[LM Studio](https://lmstudio.ai/)** and **[GPT4All](https://gpt4all.io/)** — User-friendly interfaces
- **[MLC-LLM](https://github.com/mlc-ai/mlc-llm)** — Excellent for mobile and web GPU inference

## 📚 Scientific Papers & Research

The research behind these models is crucial for understanding their efficiency. Here are the key papers with their publication years:

| Paper / Technical Report | Year | Key Contribution |
| :--- | :---: | :--- |
| **[DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via RL](https://arxiv.org/abs/2501.12948)** | 2025 | Breakthrough in reasoning via pure Reinforcement Learning. |
| **[Llama 3.2: Revolutionizing Edge AI and Vision](https://ai.meta.com/blog/llama-3-2-connect-2024-vision-edge-mobile-devices/)** | 2024 | Introduction of 1B/3B lightweight multimodal models. |
| **[Gemma 2: Improving Open Language Models at a Practical Size](https://arxiv.org/abs/2408.00118)** | 2024 | Advanced distillation techniques for smaller architectures. |
| **[Phi-3 Technical Report: A Highly Capable Language Model on Your Phone](https://arxiv.org/abs/2404.14219)** | 2024 | Demonstrating that high-quality data can compensate for size. |
| **[Qwen2 Technical Report](https://arxiv.org/abs/2407.10671)** | 2024 | Strong multilingual performance in compact models. |
| **[MobileLLM: Optimizing Sub-billion Parameter Language Models](https://arxiv.org/abs/2402.14905)** | 2024 | Architectural innovations for on-device sub-1B models. |
| **[TinyLlama: An Open-Source Small Language Model](https://arxiv.org/abs/2401.02385)** | 2024 | Proving performance of 1.1B models trained on 3T tokens. |
| **[StableLM 2 1.6B Technical Report](https://arxiv.org/abs/2402.17834)** | 2024 | Efficient training recipes for competitive small-scale LLMs. |
| **[OLMo: Accelerating the Science of Language Models](https://arxiv.org/abs/2402.00838)** | 2024 | Fully open-source model, data, and training code. |

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

