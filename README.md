# Generative Engine Optimization (GEO) Tips, Guides, Research, Tools & Resources

Welcome to a curated collection of **Generative Engine Optimization (GEO)** tips, guides, research papers, and tools. The goal is to help creators, marketers, and builders improve **visibility and citations in AI-generated answers** across generative engines.

---

## ✨ What You'll Find Here

- **Frameworks & Methodologies**  
  Proven ways to structure content for better retrieval and summarization.

- **Metrics & Evaluation**  
  How to measure citation likelihood, answer quality, and discoverability in generative engines.

- **Checklists & Best Practices**  
  Practical steps for optimizing content and prompts.

- **Experiments & Case Studies**  
  Real-world results and GEO experiments.

- **Prompts & Templates**  
  Reusable prompt patterns for GEO research and testing.

- **Tools & Resources**  
  Open-source utilities, datasets, and research references (including platforms like [GeoZ AI](https://geoz.ai)).

---

## 📌 Why GEO Matters

Traditional SEO focuses on ranking in search results. GEO focuses on **being referenced, quoted, and trusted** in AI-generated answers. As LLMs become primary interfaces for search, GEO becomes critical for brand visibility and authority.

---

## 🤝 Contributing

Have resources, papers, tools, or experiments to share? Contributions are welcome.  
Open a PR or issue to suggest additions. If you’ve built something GEO-related (including work connected to [GeoZ AI](https://geoz.ai)), feel free to share it.

---

## 📚 Research Papers

Links will be added as they are provided. Each entry will include paper, code, and dataset links when available.

### 2025
- **Language Models are Injective and Hence Invertible** [Paper](https://arxiv.org/abs/2510.15511)
Shows that (decoder-only) transformer LMs are injective (no two prompts share the same hidden-state trajectory) and introduces SipIt to reconstruct the exact prompt from activations. For GEO, this implies “internal representations” can preserve full prompt intent, so prompt-to-answer behavior is more traceable, and storing activations/embeddings can leak query text—important for safe logging, audits, and optimization loops.

- **C-SEO Bench: Does Conversational SEO Work?** (NeurIPS D&B 2025) — [Paper](https://arxiv.org/abs/2506.11097) · [Github Repo](https://github.com/parameterlab/c-seo-bench) · [Hugging Fcae Dataset](https://huggingface.co/datasets/parameterlab/c-seo-bench)
Introduces C-SEO Bench, a benchmark to test “conversational SEO” methods across multiple tasks (QA + product recommendation), domains, and competitive adoption rates. Key GEO takeaway: many current “LLM-optimization edits” are ineffective or even hurt ranking, while classic SEO signals that improve retrieval/context inclusion work better; gains also shrink as more actors adopt, making GEO feel congested/zero-sum—so you need measurement that assumes competition, not single-page wins.

- **Dynamics Of Adversarial Attacks On Large Language Model‑Based Search Engines** — [Paper](https://arxiv.org/abs/2501.00745)
Models “black-hat GEO” as a repeated game where publishers decide to cooperate (don’t manipulate) or defect (ranking-manipulation attacks) in LLM-based search. For GEO, it explains when ecosystems tip into an arms race vs stabilize, and what levers matter (attack cost, success rate, long-term incentives) for designing robust ranking/anti-spam and realistic optimization strategies.

- **White Hat Search Engine Optimization using Large Language Models** — [Paper](TBD)
- **PoisonArena: Uncovering Competing Poisoning Attacks in Retrieval‑Augmented Generation** — [Paper](TBD)
- **Beyond SEO: A Transformer‑Based Approach for Reinventing Web Content Optimisation** — [Paper](TBD)
- **NExT‑Search: Rebuilding User Feedback Ecosystem for Generative AI Search** — [Paper](TBD)
- **Role‑Augmented Intent‑Driven Generative Search Engine Optimization** — [Paper](TBD)
- **StealthRank: LLM Ranking Manipulation via Stealthy Prompt Optimization** — [Paper](TBD)

### 2024
- **GASLITeing The Retrieval: Exploring Vulnerabilities In Dense Embedding‑Based Search** — [Paper](TBD)
- **GEO: Generative Engine Optimization** — [Paper](TBD)
- **What Evidence Do Language Models Find Convincing?** — [Paper](TBD)
- **CONFLICTBANK: A Benchmark for Evaluating Knowledge Conflicts in Large Language Models** — [Paper](TBD)
- **Adversarial Search Engine Optimization for Large Language Models** — [Paper](TBD)
- **Ranking Manipulation for Conversational Search Engines** — [Paper](TBD)
- **Persistent Pre‑Training Poisoning Of LLMs** — [Paper](TBD)
- **Manipulating Large Language Models to Increase Product Visibility** — [Paper](TBD)
