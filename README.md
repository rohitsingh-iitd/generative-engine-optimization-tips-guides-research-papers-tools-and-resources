# Generative Engine Optimization (GEO): Research, Guides, Experiments & Tools

**Understand how AI search works. Improve how your brand appears in its answers.**

Welcome to a curated collection of **Generative Engine Optimization (GEO)** research, practical guides, experiments, frameworks, and tools from [The GEO Community](https://thegeocommunity.com/).

Built for marketers, founders, SEO professionals, researchers, and developers, this collection explores how AI systems discover information, select sources, generate recommendations, and attribute their answers.

Whether you are learning the fundamentals or building your own optimization systems, start here to understand the research and turn it into better experiments.

**[Explore The GEO Community](https://thegeocommunity.com/) · [Start Learning GEO](https://thegeocommunity.com/start/) · [Discover Mavey](https://www.mavey.ai/)**

---

## What You’ll Find Here

- **Research papers explained:** Clear breakdowns of GEO studies, retrieval research, benchmarks, and evaluation methods, including what the findings mean and where they apply.
- **Frameworks and methodologies:** Approaches to content strategy, search intent, source selection, and AI visibility.
- **Metrics and evaluation:** Ways to assess brand mentions, citations, source influence, answer accuracy, and changes over time.
- **Experiments and case studies:** Practical investigations that connect an optimization hypothesis to a measurable result.
- **Guides, prompts, and templates:** Resources for planning research, testing content changes, and building repeatable workflows.
- **Tools and implementation resources:** Coverage of systems that support research, content production, measurement, and ongoing marketing work.

**New to the field? Follow [The GEO Community’s guided learning path](https://thegeocommunity.com/start/).**

---

## Meet Mavey: Your Always-On AI Marketing Team

Learning GEO is one part of the work. Keeping research, strategy, content, publishing, and analysis moving takes ongoing effort.

[**Mavey**](https://www.mavey.ai/) brings your marketing work into one conversation, helping founders and growing teams coordinate SEO, GEO, content, and social marketing.

Mavey is built around three capabilities:

- **Persistent memory:** Keep your brand context, preferences, and past decisions available as your work develops.
- **Autopilot:** Keep recurring marketing workflows moving within the scope and permissions you set.
- **Recursive self-improvement:** Use feedback and previous work to refine how recurring tasks are carried out.

Bring your goals into the conversation, develop your marketing plan, and build a consistent publishing rhythm with an AI marketing team that carries context forward.

### [Explore Mavey at www.mavey.ai →](https://www.mavey.ai/)

---

## Why GEO Matters

AI-generated answers create another place where people discover brands, compare products, and decide what to investigate next.

**Generative Engine Optimization focuses on improving how your brand and content appear in those answers**, including whether your information is found, used, cited, and represented accurately.

For answers grounded in web search, visibility depends on several connected stages: retrieving relevant material, selecting sources, composing the answer, and attributing its claims. Research increasingly evaluates these stages together because an improvement at one stage may not survive the rest of the process.

This collection helps you investigate practical questions:

- Can the system find your content?
- Does it select your page for the question being asked?
- Does the answer use your information accurately?
- Is your brand mentioned, recommended, or cited?
- Do the results hold across repeated tests and different engines?
- How does that visibility connect to your marketing goals?

---

## Research Papers & Benchmarks

Every paper entry below links to **The GEO Community’s explanation or analysis**.

The list is organized by the paper’s first public release. Conference publication dates and later revisions may fall in a different year.

### 2026: Citations, Content Structure & Better Evaluation

#### [What Drives AI Citations? Content, Retrieval and Model Knowledge](https://thegeocommunity.com/blogs/generative-engine-optimization/why-does-chatgpt-cite-some-websites-ignore-others/)

Examines how content relevance, retrieval, and a model’s existing knowledge influence citations and brand mentions. Useful for understanding why a relevant webpage may still be overlooked, and why receiving a citation and receiving a brand recommendation are separate outcomes.

#### [Retrieval Augmented Generation Compositionality: LASAGNA](https://thegeocommunity.com/blogs/generative-engine-optimization/lasagna-rag-compositionality-ai-search-evaluation/)

Investigates whether improvements to individual retrieval and generation components remain useful when combined. Introduces a framework for evaluating complete RAG pipelines, making this useful background for anyone building GEO simulations or retrieval experiments.

#### [MAGEO: Multi-Agent GEO with Reusable Strategy Learning](https://thegeocommunity.com/blogs/generative-engine-optimization/mageo-multi-agent-geo-reusable-strategy-learning/)

Explores a system that plans content changes, applies them, evaluates visibility and attribution fidelity, and saves successful patterns for reuse. Useful for understanding how GEO workflows might accumulate engine-specific strategies across experiments.

#### [FeatGEO: Feature-Level Optimization for Generative Citation Visibility](https://thegeocommunity.com/blogs/generative-engine-optimization/feat-geo-paper-feature-level-optimization/)

Studies optimization through interpretable structural, content, and linguistic features. It balances citation visibility with content quality, then uses a language model to turn selected feature configurations into readable text. Useful for designing more systematic content experiments.

#### [GEO-SFE: Structural Feature Engineering for GEO](https://thegeocommunity.com/blogs/generative-engine-optimization/geo-sfe-structural-feature-engineering-citation/)

Examines how document architecture, information chunking, and visual emphasis affect citation behavior. Useful for treating content structure as something you can define, change, and measure in an experiment.

#### [SAGEO Arena: Evaluating the Full Generative Search Pipeline](https://thegeocommunity.com/blogs/generative-engine-optimization/sageo-arena-realistic-geo-benchmark/)

Evaluates GEO across retrieval, reranking, and answer generation. Its experiments show why a content change that looks promising after selection can still reduce visibility earlier in the pipeline. Essential reading for designing realistic GEO evaluations.

### 2025: Optimization Methods, Competition & Source Influence

#### [C-SEO Bench: Does Conversational SEO Work?](https://thegeocommunity.com/blogs/generative-engine-optimization/c-seo-bench-does-conversational-seo-work/)

Tests conversational SEO across tasks, domains, and competing publishers. Many tested rewriting tactics produced limited or negative gains, while source position in the model’s context remained influential. Useful for understanding why an optimization must be tested against both a baseline and competing content.

#### [AutoGEO: Learning What Generative Engines Prefer](https://thegeocommunity.com/blogs/generative-engine-optimization/autogeo-framework-iclr-2026-cmu/)

Explores automated discovery of generative-engine preferences and their use in content rewriting. The framework evaluates both source visibility and the usefulness of the generated answer. Read alongside SAGEO Arena to understand why generation-stage improvements also need retrieval testing.

#### [E-GEO: Generative Engine Optimization for E-Commerce](https://thegeocommunity.com/blogs/generative-engine-optimization/e-geo-paper-ecommerce-geo/)

Introduces an e-commerce benchmark for testing how product-description changes affect generative recommendations. It also explores iterative prompt optimization, making it useful for teams studying product discovery and recommendation visibility.

#### [CC-GSEO-Bench: Measuring Source Influence in AI Search](https://thegeocommunity.com/blogs/generative-engine-optimization/cc-gseo-bench-source-influence-generative-search/)

Evaluates a source’s influence through exposure, faithful credit, and causal impact. Useful for asking how much a document contributes to an answer, whether it receives appropriate attribution, and what changes when that source is removed.

#### [RAID G-SEO: Role-Augmented Intent-Driven Optimization](https://thegeocommunity.com/blogs/generative-engine-optimization/raid-geo-intent-driven-generative-search-optimization/)

Infers likely search intents and user roles from source content, then uses those insights to guide optimization without access to future user queries. Useful for exploring how one page can serve several related information needs.

#### [Language Models Are Injective and Hence Invertible](https://thegeocommunity.com/blogs/generative-engine-optimization/language-models-injective-invertible-arxiv-2510-15511/)

Investigates how transformer hidden states preserve input information and introduces SipIt for reconstructing prompts from hidden activations. Useful background for understanding internal representations, interpretability, and the privacy implications of storing model activations.

### Foundational Research: 2023–2024

#### [GEO: Generative Engine Optimization](https://thegeocommunity.com/blogs/generative-engine-optimization/geo-princeton-paper-original-study/)

The foundational paper introduces the GEO framework, GEO-bench, and visibility metrics for generated answers. It evaluates how content interventions affect visibility under controlled conditions. First released in 2023 and published at KDD 2024, it provides a starting point for understanding later GEO research.

#### [Evaluating Verifiability in Generative Search Engines](https://thegeocommunity.com/blogs/generative-engine-optimization/verifiability-generative-search-engines-emnlp-2023/)

Examines whether generated claims have supporting citations and whether those citations actually support the associated claims. Useful for understanding citation completeness, citation accuracy, and the difference between visible attribution and verifiable evidence.

**[Explore the full GEO research and benchmark reading list →](https://thegeocommunity.com/blogs/generative-engine-optimization/generative-engine-optimization-research-papers-benchmarks-2023-2026/)**

---

## Turn the Research into an Experiment

Use these papers to develop a question you can test.

1. **Define the outcome.** Decide whether you are measuring retrieval, citations, brand mentions, recommendations, answer accuracy, or a business result.
2. **Record a baseline.** Document the engine, model, questions, content, date, and measurement method.
3. **Make a clear intervention.** Change a specific aspect of the content or workflow so the result is interpretable.
4. **Repeat the evaluation.** Use comparable conditions and enough repeated observations to understand variability.
5. **Report the limits.** Explain where the finding held, where it failed, and what remains uncertain.

A useful contribution gives someone else enough detail to repeat the experiment and assess the result.

---

## Contribute to the Collection

Have a useful study, implementation, tool, or experiment to share? **Open an issue or submit a pull request.**

For research additions, include the paper title, a short explanation of its relevance, and a link to its coverage on **The GEO Community**. If a paper has not been covered yet, suggest it for a future review.

For experiments, include the question, setup, baseline, changes tested, results, and limitations. Unexpected or negative findings are welcome.

---

## Keep Learning. Keep Building.

Explore the research, contribute your findings, and help make GEO easier to understand and test.

**[Learn with The GEO Community →](https://thegeocommunity.com/)**

Ready to build a more consistent marketing workflow?

**[Meet Mavey, your always-on AI marketing team →](https://www.mavey.ai/)**

If this collection helps you, **star the repository and share it with someone working on AI search visibility.**
