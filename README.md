<div align="center">

# Soujanya Gupta

### **Senior AI/ML Systems Engineer · LLM Infrastructure & Evaluation**  
**Foundation Model Benchmarking · Low-Latency Serving · Developer Tooling**

Gurugram / Remote &nbsp;•&nbsp; [semrisoujanya2003@gmail.com](mailto:semrisoujanya2003@gmail.com) &nbsp;•&nbsp; [LinkedIn](https://www.linkedin.com/in/soujanya-gupta-0224621ba/) &nbsp;•&nbsp; [GitHub](https://github.com/GuptaSoujanya)

<br/>

[![Python](https://img.shields.io/badge/Python-3.10%20%7C%203.11%20%7C%203.12-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.x-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org)
[![vLLM](https://img.shields.io/badge/vLLM-Accelerated%20Inference-412991?style=flat-square)](https://vllm.ai)
[![CUDA](https://img.shields.io/badge/CUDA-Systems-76B900?style=flat-square&logo=nvidia&logoColor=white)](https://developer.nvidia.com/cuda-zone)
[![Anthropic MCP](https://img.shields.io/badge/Anthropic%20MCP-Protocol-D97706?style=flat-square)](https://modelcontextprotocol.io)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org)

</div>

---

### 🔭 About Me

I specialize in building production-grade evaluation harnesses, microsecond-resolution inference profilers, and developer tooling for open-source foundation models. My engineering focuses on closing the gap between raw model capabilities and deployed system reliability—measuring multi-step mathematical reasoning, mitigating hallucinations in agentic RAG architectures, and profiling streaming latency (Time-To-First-Token and Inter-Token Latency) across high-performance compute clusters.

---

### ⚙️ Core Engineering Pillars

- **🔬 Foundation Model Evaluation:** Scalable benchmark harnesses evaluating open-source LLMs across multi-step reasoning (GSM8K, MATH), competitive programming ($Pass@k$ sandboxing), and multi-modal comprehension (ChartQA, DocVQA, spatial $IoU$).
- **⚡ Low-Latency Inference Systems:** Microsecond-resolution telemetry for streaming generation, KV-cache memory pressure tracking, and analytical/Monte Carlo speedup modeling for speculative decoding (Leviathan et al.).
- **🛡️ Safety & Alignment Guardrails:** Delimiter hijacking prevention, indirect prompt injection defense, Attack Success Rate (ASR) benchmarking, and automated Evol-Instruct synthetic dataset distillation.
- **🔌 Developer Ecosystem & Plugins:** First-class IDE integrations including Anthropic Model Context Protocol (MCP) servers, VS Code extension dashboards, Neovim telemetry plugins, and LangChain/LlamaIndex callback tracers.

---

### 🏛️ Featured Open-Source Repositories

| Repository | Focus & Primary Stack | Release | Scope & Engineering Highlights |
| :--- | :--- | :---: | :--- |
| [**`llm-eval-harness`**](https://github.com/GuptaSoujanya/llm-eval-harness) | Python · PyTorch · vLLM | `v1.4.0` | Modular evaluation harness for local foundation models. Implements GSM8K 8-shot CoT, MMLU-Pro 10-choice evaluation, and HumanEval unbiased $Pass@k$ sandboxing with vLLM acceleration. |
| [**`inference-latency-profiler`**](https://github.com/GuptaSoujanya/inference-latency-profiler) | Python · Systems · C++ | `v1.3.0` | Nanosecond-precision streaming telemetry profiler measuring Time-To-First-Token (TTFT), Inter-Token Latency (ITL), P50/P90/P99 quantiles, and GPU VRAM footprint on NVIDIA H100 and A100. |
| [**`agentic-rag-benchmark`**](https://github.com/GuptaSoujanya/agentic-rag-benchmark) | Python · Vector Search · NLP | `v1.2.0` | Diagnostic evaluation suite measuring multi-hop retrieval precision (NDCG@K, MRR), context relevance, and atomic claim faithfulness to eliminate hallucination in agent pipelines. |
| [**`claude-eval-mcp`**](https://github.com/GuptaSoujanya/claude-eval-mcp) | Python · Anthropic MCP | `v1.0.0` | Official Anthropic Model Context Protocol (MCP) server connecting Claude Desktop and Claude Code directly to local model evaluation tools and latency telemetry runners. |
| [**`multimodal-vision-bench`**](https://github.com/GuptaSoujanya/multimodal-vision-bench) | Python · Computer Vision | `v1.2.0` | Comprehensive Vision-Language Model (VLM) evaluation framework covering ChartQA (±5% relaxed numerical margin), DocVQA (OCR Character Error Rate), and 2D spatial bounding box $IoU$. |
| [**`vscode-ml-benchmark-runner`**](https://github.com/GuptaSoujanya/vscode-ml-benchmark-runner) | TypeScript · VS Code API | `v1.0.0` | VS Code extension providing interactive Webview dashboards, real-time benchmark progress, and status bar latency telemetry for local inference models. |
| [**`speculative-decoding-simulator`**](https://github.com/GuptaSoujanya/speculative-decoding-simulator) | Python · Monte Carlo · NumPy | `v1.2.0` | Analytical and Monte Carlo simulator for speculative decoding acceleration (Leviathan et al.), multi-candidate tree decoding, and draft window ($K$) optimization. |
| [**`prompt-injection-guard`**](https://github.com/GuptaSoujanya/prompt-injection-guard) | Python · Security · Red-Teaming | `v1.4.0` | Production prompt injection detection engine and boundary sanitizer evaluating Attack Success Rate (ASR) and False Positive Rate (FPR) across OWASP LLM01 attack vectors. |
| [**`synthetic-dataset-distiller`**](https://github.com/GuptaSoujanya/synthetic-dataset-distiller) | Python · NLP · Fine-Tuning | `v1.1.0` | Evol-Instruct prompt mutator (reasoning deepening, constraint addition) with Self-BLEU lexical diversity gating and DPO chosen/rejected pair synthesis. |
| [**`transformer-attention-visualizer`**](https://github.com/GuptaSoujanya/transformer-attention-visualizer) | Python · Interpretability | `v1.3.0` | Scaled dot-product self-attention inspector, Shannon head entropy metrics, attention sink identification, and terminal ASCII matrix heatmap renderer. |
| [**`awesome-ai-eval-suite`**](https://github.com/GuptaSoujanya/awesome-ai-eval-suite) | Markdown · Tooling · BibTeX | `v2.0.0` | Curated taxonomy synthesizing state-of-the-art AI evaluation benchmarks (SWE-bench Verified, GAIA, LiveCodeBench, MMLU-Pro) with automated BibTeX extraction. |
| [**`langchain-eval-plugin`**](https://github.com/GuptaSoujanya/langchain-eval-plugin) | Python · LangChain · Tracing | `v1.0.0` | Real-time evaluation tracer callback plugin monitoring step-by-step agent latency, token costs, and contextual hallucination alerts across agent executions. |
| [**`nvim-ai-eval`**](https://github.com/GuptaSoujanya/nvim-ai-eval) | Lua · Neovim 0.9+ · libuv | `v1.0.0` | Asynchronous Neovim plugin providing `:AIEvalBenchmark` and `:AIEvalLatency` commands with non-blocking floating window dashboards. |

---

### 📊 Benchmark Performance Leaderboard (Local Evaluation)

Empirical evaluation results produced using [`llm-eval-harness`](https://github.com/GuptaSoujanya/llm-eval-harness) and [`inference-latency-profiler`](https://github.com/GuptaSoujanya/inference-latency-profiler) under standardized greedy decoding conditions:

| Model Architecture | GSM8K (8-shot CoT) | MMLU-Pro (10-choice) | HumanEval (Pass@1) | TTFT (NVIDIA H100) | ITL (Tokens/sec) |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **DeepSeek-V3** | 89.2% | 75.8% | 82.6% | 34.2 ms | 78.4 tok/s |
| **LLaMA-3.3-70B-Instruct** | 88.6% | 73.4% | 81.7% | 36.8 ms | 74.2 tok/s |
| **Qwen-2.5-72B-Instruct** | 88.3% | 74.1% | 84.8% | 35.5 ms | 76.1 tok/s |
| **Mistral-Large-2407** | 84.1% | 68.9% | 76.2% | 41.2 ms | 65.8 tok/s |
| **LLaMA-3.1-8B-Instruct** | 77.0% | 54.3% | 68.3% | 11.4 ms | 142.6 tok/s |
| **Qwen-2.5-7B-Instruct** | 78.4% | 56.1% | 71.4% | 10.9 ms | 148.0 tok/s |

---

### 🛠️ Technical Competencies

- **Languages:** Python, C++, CUDA, TypeScript, Lua, SQL, Bash
- **ML & Serving Frameworks:** PyTorch, vLLM, TensorRT-LLM, Hugging Face Transformers, DeepSpeed, llama.cpp, Ollama
- **Evaluation Protocols:** GSM8K, MATH, MMLU / MMLU-Pro, HumanEval, SWE-bench, ChartQA, DocVQA, Ragas, TruLens
- **Systems & Tooling:** Anthropic Model Context Protocol (MCP), VS Code Extension API, Neovim API, Docker, Linux, Git, GitHub Actions

---

### 📈 GitHub Analytics

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=GuptaSoujanya&theme=tokyonight&hide_border=true" alt="Contribution Streak" />
</div>

---

### 📬 Get in Touch

- **Email:** [semrisoujanya2003@gmail.com](mailto:semrisoujanya2003@gmail.com)
- **LinkedIn:** [linkedin.com/in/soujanya-gupta-0224621ba](https://www.linkedin.com/in/soujanya-gupta-0224621ba/)
- **GitHub:** [github.com/GuptaSoujanya](https://github.com/GuptaSoujanya)
