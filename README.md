# Awesome-Edge-Ready-LLM-Models
## Top Edge-Ready Small Language Models (SLMs) Ecosystem

**Curated List of Models & Open-Source GitHub Projects**  
*Focused on Efficient SLMs Optimized for Local, Edge & On-Device Inference*  
**Last updated: March 2026**

This repository tracks the **top edge-ready Small Language Models (SLMs)** — compact models (typically 1B to 4B parameters) optimized for local hardware via quantization (4-bit/8-bit), pruning, distillation, and efficient architectures. These models run efficiently on laptops, smartphones, Raspberry Pi, edge devices, and consumer GPUs with excellent performance for chat, coding, reasoning, and agentic tasks.

**Examples** include Google Gemma 3, Meta Llama 3.2, Microsoft Phi-4 Mini, and Mistral Ministral-3B (the category leaders). Models listed here prioritize **low memory footprint**, fast inference, and strong performance on consumer hardware.

**Open-source emphasis**: This section is heavily expanded with every major active open model, quantized versions (GGUF, ONNX, AWQ), and supporting tools for local deployment.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sources.

## Table of Contents
- [Proprietary / Hosted Models](#saas-products)
- [Open-Source Models & Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Proprietary / Hosted Models

### Core Edge-Optimized Models

- **[Google Gemma 3](https://ai.google.dev/gemma)**  
  Highly efficient family of models (1B–4B) optimized for on-device and edge inference with strong reasoning and safety features.

- **[Microsoft Phi-4 Mini](https://azure.microsoft.com/en-us/products/phi)**  
  Exceptional small model (3.8B) with outstanding reasoning capabilities, specifically designed for local and edge deployment.

- **[Mistral Ministral-3B](https://mistral.ai)**  
  Powerful 3B parameter model from Mistral AI optimized for speed and efficiency on consumer hardware.

### Advanced Models

**Other notable mentions**: Apple Intelligence models (on-device), and various quantized proprietary offerings.

## Open-Source GitHub Projects

### Leading Edge-Ready Open Models

- **[Meta Llama 3.2](https://github.com/meta-llama/llama-models)** (1B & 3B)  
  Excellent lightweight models from Meta optimized for edge devices with strong multilingual and reasoning performance. Available in GGUF for Ollama/LM Studio.

- **[Microsoft Phi-3 / Phi-4 Mini](https://github.com/microsoft/Phi-3)**  
  Industry-leading small models (3.8B–4B) with exceptional benchmark performance. Highly optimized for ONNX, GGUF, and mobile/edge deployment.

- **[Google Gemma 2 & Gemma 3](https://github.com/google/gemma)** (2B & 7B variants)  
  Open models with excellent efficiency and instruction-following capabilities. Widely used in quantized form for local inference.

- **[Mistral Ministral-3B / Mistral Small](https://github.com/mistralai)** (open weights versions)  
  High-performance 3B-class models optimized for low-latency inference on laptops and edge hardware.

- **[Qwen2.5-1.5B / Qwen2.5-3B](https://github.com/QwenLM/Qwen2.5)**  
  Outstanding small models from Alibaba with strong multilingual and coding abilities. Excellent quantized GGUF versions available.

- **[TinyLlama 1.1B](https://github.com/jzhang38/TinyLlama)**  
  Classic compact model designed specifically for edge and mobile deployment.

- **[StableLM 2 (1.6B–3B)](https://github.com/Stability-AI/StableLM)**  
  Efficient models from Stability AI optimized for local use and creative tasks.

- **[DeepSeek-R1-Distill-Qwen-1.5B / 7B](https://github.com/deepseek-ai)**  
  Strong reasoning-focused distilled models perfect for edge devices.

### Additional Strong Open-Source Options

- **[Gemma-2-2B](https://huggingface.co/google/gemma-2-2b)** and community fine-tunes
- **[Phi-3.5-Mini](https://huggingface.co/microsoft/Phi-3.5-mini-instruct)** — Highly optimized 3.8B model
- **[H2O-Danube-1.8B](https://huggingface.co/h2oai/h2o-danube-1.8b)** — Efficient European model
- **[MobileLlama / MobileBERT variants](https://github.com/search?q=mobile+llm)**
- **[OLMo-1B / OLMo-2B](https://github.com/allenai/OLMo)** from AllenAI
- **[Snowflake Arctic Embed](https://github.com/Snowflake-Labs)** and other compact embedding models
- **GGUF Quantized Collections** on Hugging Face (TheBloke, bartowski, etc.) for 4-bit/8-bit versions optimized for llama.cpp, Ollama, and LM Studio.

**Recommended Local Inference Tools**:
- **[Ollama](https://github.com/ollama/ollama)** — Easiest way to run these models locally
- **[llama.cpp](https://github.com/ggerganov/llama.cpp)** — Best for maximum efficiency and edge devices
- **[LM Studio](https://lmstudio.ai/)** and **[GPT4All](https://gpt4all.io/)** — User-friendly interfaces
- **[MLC-LLM](https://github.com/mlc-ai/mlc-llm)** — Excellent for mobile and web GPU inference

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, parameter size, 1–2 sentence description, and quantization options.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

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

**Made for developers, on-device AI enthusiasts, edge computing teams, and privacy-focused users.**  
Let's run powerful AI models locally, privately, and efficiently.
