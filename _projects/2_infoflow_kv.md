---
layout: page
title: "InfoFlow KV: Information-Flow-Aware KV Recomputation for Long Context"
description: "Preprint &middot; Under review at ICML 2026 &middot; Co-first author"
importance: 1
category: paper
---

**Preprint** &nbsp;|&nbsp; Under review at ICML 2026 &nbsp;|&nbsp; Jun. 2025 – Feb. 2026

*\*Co-first author. With Prof. Shengjie Wang, Prof. Tianyi Zhou, and Prof. Danyang Zhuo.*

<a href="https://arxiv.org/abs/2603.05353" target="_blank" class="btn btn-sm z-depth-0" role="button">arXiv</a>

---

### Overview

Retrieval-augmented generation (RAG) for long-context question answering is bottlenecked by inference-time prefilling over large retrieved contexts. We propose **InfoFlow KV**, casting selective KV recomputation as an information flow problem.

---

### Contributions

- Built a **chunk-based KV prefilling and recomputation pipeline** enabling reusable KV caches and recovering cross-chunk attention under long-context inference across multiple LLMs (Qwen, LLaMA, ChatGLM).
- Proposed two information-flow-aware recomputation strategies: a **query-conditioned attention-norm** token selection method aligned with inference-consistent RoPE geometry, and a **chunk reordering** scheme that improves prompt–context interaction, achieving up to **+6% F1** score on HotpotQA over prior methods.
- Analyzed how RoPE positional geometry affects token selection in chunk-wise long-context inference, identifying frequency range and prompt–context proximity as key factors.
