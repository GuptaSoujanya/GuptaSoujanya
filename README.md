<div align="center">

# Soujanya Gupta

### AI/ML Benchmarking · LLM Systems Infrastructure · Developer Plugins

[![GitHub Followers](https://img.shields.io/github/followers/GuptaSoujanya?label=Followers&style=for-the-badge&color=blue)](https://github.com/GuptaSoujanya)
[![GitHub Stars](https://img.shields.io/github/stars/GuptaSoujanya?label=Total%20Stars&style=for-the-badge&color=gold)](https://github.com/GuptaSoujanya)
[![Profile Views](https://komarev.com/ghpvc/?username=GuptaSoujanya&color=007ec6&style=for-the-badge)](https://github.com/GuptaSoujanya)

<br/>

```
Specializing in high-throughput LLM evaluation harnesses, Time-To-First-Token (TTFT) microsecond latency profiling,
speculative decoding acceleration, and agentic RAG verification pipelines.
```

</div>

---

### 🚀 Technical Overview & Research Focus

```mermaid
mindmap
  root((Soujanya Gupta))
    AI & ML Benchmarking
      MMLU / MMLU-Pro
      GSM8K Multi-Step CoT
      HumanEval Pass@k Sandbox
      Multimodal ChartQA & DocVQA
    LLM Inference & Infra
      vLLM & TensorRT-LLM Acceleration
      Speculative Decoding (Leviathan Simulation)
      TTFT & Inter-Token Latency (ITL) Profiling
      Evol-Instruct Synthetic Data Distillation
    Developer Tooling & Plugins
      Claude Model Context Protocol (MCP) Server
      VS Code ML Benchmark Extension
      Neovim In-Editor Evaluation (Lua)
      LangChain / LlamaIndex Real-Time Tracer
    Safety & Security
      Prompt Injection & Delimiter Hijacking Defense
      Atomic Claim Faithfulness & Hallucination Audits
      Attention Head Entropy & Sink Analysis
```

---

### 🛠️ Featured Open-Source Repositories

#### 1. Core AI/ML Benchmarking Engines
- **[`llm-eval-harness`](https://github.com/GuptaSoujanya/llm-eval-harness)** — Extensible benchmark harness for local open-source models (Llama-3.3, Qwen-2.5, Mistral) across GSM8K, MMLU, and HumanEval with unbiased $Pass@k$ estimation.
- **[`agentic-rag-benchmark`](https://github.com/GuptaSoujanya/agentic-rag-benchmark)** — Diagnostic toolkit evaluating multi-hop agent retrieval trajectories, NDCG@K ranking, and atomic claim-level faithfulness.
- **[`multimodal-vision-bench`](https://github.com/GuptaSoujanya/multimodal-vision-bench)** — Evaluation suite for Vision-Language Models (VLMs) targeting ChartQA (±5% margin), DocVQA (Normalized CER), and 2D spatial $IoU$.

#### 2. LLM Systems & Latency Profiling
- **[`inference-latency-profiler`](https://github.com/GuptaSoujanya/inference-latency-profiler)** — Microsecond-precision profiler for Time-To-First-Token (TTFT), Inter-Token Latency (ITL), and P50/P90/P99 latency across NVIDIA H100, A100, RTX 4090, and Apple Silicon.
- **[`speculative-decoding-simulator`](https://github.com/GuptaSoujanya/speculative-decoding-simulator)** — Monte Carlo simulation and analytical modeling of draft acceptance rate $\alpha$, optimal window $\gamma$, and Leviathan speedup factors.
- **[`synthetic-dataset-distiller`](https://github.com/GuptaSoujanya/synthetic-dataset-distiller)** — Automated synthetic reasoning evolution (Evol-Instruct), prompt constraint mutators, and lexical diversity quality gating.

#### 3. Developer Plugins & Ecosystem Tooling
- **[`claude-eval-mcp`](https://github.com/GuptaSoujanya/claude-eval-mcp)** — Official Anthropic **Model Context Protocol (MCP)** server exposing model benchmarking, latency profiling, and security auditing directly to Claude Desktop & Claude Code.
- **[`vscode-ml-benchmark-runner`](https://github.com/GuptaSoujanya/vscode-ml-benchmark-runner)** — Modern VS Code extension in TypeScript featuring Activity Bar integration and interactive HTML/CSS Webview dashboards.
- **[`nvim-ai-eval`](https://github.com/GuptaSoujanya/nvim-ai-eval)** — Blazing-fast Neovim Lua plugin providing in-editor `:AIEvalBenchmark` and `:AIEvalLatency` telemetry.
- **[`langchain-eval-plugin`](https://github.com/GuptaSoujanya/langchain-eval-plugin)** — Real-time evaluation tracer callback plugin for LangChain and LlamaIndex pipelines.

#### 4. Interpretability & Safety
- **[`prompt-injection-guard`](https://github.com/GuptaSoujanya/prompt-injection-guard)** — Security and red-teaming evaluation harness testing delimiter hijacking, jailbreak resilience, and Attack Success Rate (ASR).
- **[`transformer-attention-visualizer`](https://github.com/GuptaSoujanya/transformer-attention-visualizer)** — Scaled dot-product attention inspection, Shannon head entropy diagnostics, and terminal ASCII heatmaps.
- **[`awesome-ai-eval-suite`](https://github.com/GuptaSoujanya/awesome-ai-eval-suite)** — Curated authoritative taxonomy of frontier AI evaluation benchmarks (SWE-bench Verified, GAIA, LiveCodeBench, MMLU-Pro).

---

### 📊 Benchmark Performance Matrix (Selected Models)

| Model Name | Parameters | GSM8K (CoT) | MMLU (5-shot) | HumanEval (Pass@1) | H100 TTFT (ms) | Throughput (tok/s) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Meta-Llama-3.3-70B-Instruct** | 70B | **88.6%** | **86.4%** | **81.7%** | 38.4 ms | 48.2 tok/s |
| **Qwen-2.5-72B-Instruct** | 72B | 87.2% | 85.3% | 80.5% | 39.1 ms | 46.8 tok/s |
| **Meta-Llama-3.1-8B-Instruct** | 8B | 79.6% | 68.4% | 62.2% | **18.2 ms** | **142.5 tok/s** |
| **Mistral-7B-Instruct-v0.3** | 7B | 61.2% | 62.7% | 45.1% | 19.5 ms | 155.0 tok/s |

---

### 💻 Technologies & Languages

<div align="left">

**Languages & Systems:**  
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white)
![Bash](https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)

**AI / ML Frameworks & Backends:**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![vLLM](https://img.shields.io/badge/vLLM-4B0082?style=for-the-badge&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-6B46C1?style=for-the-badge&logoColor=white)
![Model Context Protocol](https://img.shields.io/badge/Anthropic_MCP-000000?style=for-the-badge&logo=anthropic&logoColor=white)

**Tooling & Environments:**  
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=for-the-badge&logo=neovim&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

---

### 📬 Connect with Me

- **Email:** [soujanya.gupta@ethara.ai](mailto:soujanya.gupta@ethara.ai)
- **LinkedIn:** [linkedin.com/in/soujanya-gupta-0224621ba](https://www.linkedin.com/in/soujanya-gupta-0224621ba/)
- **GitHub:** [github.com/GuptaSoujanya](https://github.com/GuptaSoujanya)
