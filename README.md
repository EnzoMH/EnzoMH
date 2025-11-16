<div align="center">

# 신명호 Shin Myeongho

**AI/ML Engineer** | LLM Fine-tuning & Production RAG

[![HuggingFace](https://img.shields.io/badge/🤗_MyeongHo0621-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/MyeongHo0621)
[![HuggingFace](https://img.shields.io/badge/🤗_soka0000-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/soka0000)
[![Email](https://img.shields.io/badge/isfs003@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:isfs003@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=notion&logoColor=white)](https://www.notion.so/Shin-Myeong-Ho-32b17c808b3642a583ea457a0c68df5a)

</div>

---

## 👋 About Me

AI/ML Engineer focusing on **Korean LLM fine-tuning**, **RAG systems**, and **production-grade inference**.

- 🧠 Building my own **Korean LLM lineup** (7B / 14B / 3B) with Qwen2.5-based models
- 🤖 Reduced RAG + LLM inference latency by **75%** (20s → 5s) using vLLM & architecture tuning
- 🏭 Currently: AI/Backend Engineer at a **Digital Twin & warehouse automation** startup (VisionSpace)
- ☁️ Shipping real services on **AWS & GCP** with Docker, CI/CD, and observability in mind

---

## 🧠 Korean LLM Lineup

### 1. **Qwen2.5-14B-Korean** (Instruction-Tuned) ⭐
> Korean-focused 14B instruction model based on Qwen2.5-14B-Instruct

[![Model on 🤗](https://img.shields.io/badge/🤗_Qwen2.5--14B--Korean-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/MyeongHo0621/Qwen2.5-14B-Korean)

- Fine-tuned on ~680k Korean instruction / multi-turn / math & reading comprehension samples
- **Benchmarks (Korean):**
  - GSM8K-Ko: 83.5% (167/200)
  - KorQuAD 1.0: 74.2% (371/500)
- Optimized for **long-context Korean reasoning** and multi-turn dialogue

---

### 2. **vclm-korean-7b** ⭐
> 7B Korean LLM with heavily customized chat format & tokenizer behavior

[![Model on 🤗](https://img.shields.io/badge/🤗_vclm--korean--7b-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/soka0000/vclm-korean-7b)

- Designed as a **playground model** for experimenting with chat templates & instruction styles

---

### 3. **Qwen2.5-3B-Korean (WIP)** 🔧
> Lightweight Korean multi-turn assistant for local & edge deployment

- Base: `Qwen/Qwen2.5-3B-Instruct`
- Goal: Instruction tuning on **SmolTalk-style Korean multi-turn data (~460k)**  
  to build a 3B model that runs on **consumer GPUs (e.g., 6GB VRAM + GGUF)**.
- Plan:
  - LoRA-based SFT (v0) → nf4 / GGUF quantization → `llama.cpp` / Ollama support

---

## 🚀 Featured Projects

### 1. **Industrial Digital Twin & RAG Platform** ⭐
> Backend systems for warehouse automation with AGV/AMR/CNV/RTV integration

**Impact:**
- ⚡ **75% latency reduction** in AI inference (20s → 5s) via vLLM + RAG optimization
- 🗄️ Built a **document RAG** pipeline for real-time equipment / SOP retrieval
- 📊 XGBoost-based ROI/KPI prediction within simulation environments

**Tech:** Python, FastAPI, Next.js 15, vLLM, ROS, PostgreSQL, AWS EC2, Docker

**Status:** 🟢 Production (Aug 2025 – Present)

---

### 2. **Multi-LLM Document Automation System** ⭐
> Enterprise proposal generation system with Claude, Gemini, GPT, EXAONE integration

**Impact:**
- 📝 **80% reduction** in proposal creation time for exhibition & B2B clients
- 🤖 Multi-LLM orchestration (routing + fallback) with real-time monitoring
- 📋 Template-based generation while preserving brand tone & structure

**Tech:** FastAPI, LangChain, Next.js, Docker, AWS EC2

**Status:** 🟢 Production

---

### 3. **SOLAR-10.7B Korean Fine-tuning** ⭐
> MLOps pipeline for Korean language model optimization on H100E

[![Model on 🤗](https://img.shields.io/badge/🤗_eeve--vss--smh-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/MyeongHo0621/eeve-vss-smh)

**Impact:**
- End-to-end MLOps pipeline for **distributed training, logging, and hyperparameter search**
- Published fine-tuned model on HuggingFace for community usage
- Hands-on experience with **H100E GPU** cluster configuration

**Tech:** PyTorch, HuggingFace Transformers, CUDA, H100E

**Status:** 🟢 Active Research

---

## 💻 Tech Stack

**LLM & NLP:** Qwen2.5, Llama, SOLAR, EXAONE, vLLM, HuggingFace, RAG, LangChain  
**Training:** LoRA / QLoRA, H100E, bitsandbytes, Unsloth, CUDA  
**Backend:** Python, FastAPI, PostgreSQL, Redis, WebSocket  
**Frontend:** Next.js 15, React, TailwindCSS  
**Cloud & DevOps:** AWS (EC2, ECS, ECR), GCP (Compute Engine), Docker, GitHub Actions

---

## 📊 Impact Summary

| Metric              | Value          | Context                          |
|---------------------|----------------|----------------------------------|
| Inference Latency   | **-75%**       | 20s → 5s via vLLM optimization   |
| Document Time Saved | **-80%**       | Proposal & doc automation        |
| Production Systems  | **3+**         | Multi-cloud, customer-facing     |
| Public LLMs         | **3+**         | Korean-focused models on HF      |

---

## 💼 Experience

**AI/Backend Engineer** @ VisionSpace (Digital Twin & Automation)  
*Aug 2025 – Present*

**AI Product / Backend Engineer** @ Nuckl  
*Jan 2025 – Feb 2025*

**AI Developer** @ GIWorks (Exhibition & LED Production)  
*Jul 2024 – Dec 2024*

---

<div align="center">

![](https://komarev.com/ghpvc/?username=EnzoMH&color=blue&style=flat-square)

**"From Korean LLM research to production RAG systems."**

</div>
