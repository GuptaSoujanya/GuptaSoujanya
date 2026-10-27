# Soujanya Gupta

**Senior AI/ML Systems Engineer · LLM Infrastructure & Evaluation**  
Gurugram / Remote · [soujanya.gupta@ethara.ai](mailto:soujanya.gupta@ethara.ai) · [LinkedIn](https://www.linkedin.com/in/soujanya-gupta-0224621ba/) · [GitHub](https://github.com/GuptaSoujanya)

---

### About

I specialize in building production-grade evaluation harnesses, low-latency LLM inference runtimes, and developer tooling for foundation models. My engineering work focuses on measuring and accelerating open-source models across mathematical reasoning, agentic retrieval faithfulness, streaming token latency (TTFT / ITL), and developer workflows.

---

### Core Engineering Focus

- **Foundation Model Benchmarking:** Standardized evaluation harnesses covering multi-step reasoning (GSM8K, MMLU-Pro), code generation ($Pass@k$ sandboxing), and vision-language comprehension (ChartQA, DocVQA).
- **Inference Systems & Telemetry:** Microsecond-resolution latency profiling (Time-To-First-Token, Inter-Token Latency), KV-cache allocation monitoring, and speculative decoding speedup modeling.
- **Developer Plugins & Ecosystem:** Anthropic Model Context Protocol (MCP) servers, VS Code and Neovim IDE integrations, and real-time execution tracer callbacks for LangChain and LlamaIndex agents.
- **Data Distillation & Alignment:** Automated evolutionary prompt mutation (Evol-Instruct), lexical diversity quality gating, and prompt injection / delimiter hijacking defense.

---

### Selected Open-Source Repositories

| Repository | Focus & Stack | Description |
| :--- | :--- | :--- |
| [**`llm-eval-harness`**](https://github.com/GuptaSoujanya/llm-eval-harness) | Python, PyTorch, vLLM | Extensible evaluation harness for local foundation models across GSM8K, MMLU, and HumanEval with unbiased $Pass@k$ estimation. |
| [**`agentic-rag-benchmark`**](https://github.com/GuptaSoujanya/agentic-rag-benchmark) | Python, FAISS, Vector Search | Diagnostic evaluation suite measuring multi-hop retrieval precision (NDCG@K, MRR), context relevance, and claim faithfulness. |
| [**`inference-latency-profiler`**](https://github.com/GuptaSoujanya/inference-latency-profiler) | Python, Systems, Telemetry | High-precision streaming profiler for Time-To-First-Token (TTFT), Inter-Token Latency (ITL), and P50/P90/P99 latency across H100 and A100. |
| [**`claude-eval-mcp`**](https://github.com/GuptaSoujanya/claude-eval-mcp) | Python, Anthropic MCP | Official Model Context Protocol (MCP) server connecting Claude Desktop and Claude Code directly to local model evaluation tools. |
| [**`multimodal-vision-bench`**](https://github.com/GuptaSoujanya/multimodal-vision-bench) | Python, Computer Vision | Benchmarking framework for Vision-Language Models (VLMs) on ChartQA (±5% margin), DocVQA (CER), and 2D spatial $IoU$. |
| [**`vscode-ml-benchmark-runner`**](https://github.com/GuptaSoujanya/vscode-ml-benchmark-runner) | TypeScript, VS Code API | VS Code extension for configuring, running, and visualizing local AI model benchmarks directly inside the editor. |
| [**`nvim-ai-eval`**](https://github.com/GuptaSoujanya/nvim-ai-eval) | Lua, Neovim 0.9+ | Neovim plugin providing `:AIEvalBenchmark` and `:AIEvalLatency` commands for in-editor telemetry and model checks. |
| [**`langchain-eval-plugin`**](https://github.com/GuptaSoujanya/langchain-eval-plugin) | Python, LangChain | Real-time evaluation tracer callback plugin monitoring step-by-step agent latency, token costs, and hallucination scores. |
| [**`speculative-decoding-simulator`**](https://github.com/GuptaSoujanya/speculative-decoding-simulator) | Python, Monte Carlo | Analytical and Monte Carlo simulator for speculative decoding acceleration (Leviathan et al.) and draft window optimization. |
| [**`synthetic-dataset-distiller`**](https://github.com/GuptaSoujanya/synthetic-dataset-distiller) | Python, NLP | Evol-Instruct prompt mutator (reasoning deepening, constraint addition) and lexical diversity quality filtering pipeline. |
| [**`prompt-injection-guard`**](https://github.com/GuptaSoujanya/prompt-injection-guard) | Python, Red-Teaming | Security evaluation harness measuring prompt injection resilience, delimiter hijacking, and Attack Success Rate (ASR). |
| [**`transformer-attention-visualizer`**](https://github.com/GuptaSoujanya/transformer-attention-visualizer) | Python, NumPy | Scaled dot-product self-attention inspection, Shannon head entropy metrics, and terminal ASCII matrix heatmaps. |
| [**`awesome-ai-eval-suite`**](https://github.com/GuptaSoujanya/awesome-ai-eval-suite) | Markdown, Python | Curated taxonomy of SOTA AI evaluation benchmarks (SWE-bench Verified, GAIA, LiveCodeBench, MMLU-Pro). |

---

### Technical Expertise

- **Languages:** Python, C++, CUDA, TypeScript, Lua, SQL, Bash
- **ML / AI Infrastructure:** PyTorch, vLLM, TensorRT-LLM, Hugging Face Transformers, DeepSpeed, llama.cpp, Ollama
- **Evaluation & Alignment:** GSM8K, MMLU / MMLU-Pro, HumanEval, SWE-bench, ChartQA, DocVQA, Ragas, TruLens
- **Protocols & Developer Tooling:** Anthropic Model Context Protocol (MCP), VS Code Extension API, Neovim API, LangChain, LlamaIndex, Docker, Git

---

### Contact & Links

- **Email:** [semrisoujanya2003@gmail.com](mailto:semrisoujanya2003@gmail.com)
- **LinkedIn:** [linkedin.com/in/soujanya-gupta-0224621ba](https://www.linkedin.com/in/soujanya-gupta-0224621ba/)
- **GitHub:** [github.com/GuptaSoujanya](https://github.com/GuptaSoujanya)
