# Awesome AI Benchmark And Leaderboard

<p align="center">
  <a href="README.md">English</a> |
  <a href="README.ja.md">日本語</a>
</p>


## General Comparison & Rankings

| Name | Description |
| --- | --- |
| [Artificial Analysis](https://artificialanalysis.ai/) | An independent site that compares AI models and API providers across quality, price, output speed, and latency. Also offers a proprietary intelligence index and hallucination rate evaluation. |
| [LLM Stats](https://llm-stats.com/) | A platform that compares 289+ AI models on benchmark performance, pricing, and throughput using independent, reproducible methods. Covers language models as well as image, video, and audio generation. |
| [Scale Labs Leaderboard](https://labs.scale.com/leaderboard) | Scale's AI model evaluation platform aggregating expert-driven benchmarks across multiple categories including agentic capabilities, frontier reasoning, and safety (SWE-Bench Pro, Humanity's Last Exam, etc.). |
| [Vellum LLM Leaderboard](https://www.vellum.ai/llm-leaderboard) | A leaderboard comparing leading LLMs across public benchmarks such as GPQA Diamond, AIME, SWE-Bench Verified, and ARC-AGI, along with throughput and cost efficiency. |
| [Nejumi Leaderboard 4](https://nejumi.ai/) | A Japanese LLM evaluation leaderboard operated by Weights & Biases. Comprehensively assesses Japanese generation accuracy, practical application development capabilities, and safety to support LLM selection for the Japanese market. |

## User-Driven Rankings

| Name | Description |
| --- | --- |
| [LM Arena](https://lmarena.ai/ja/leaderboard) | A community-driven platform where users anonymously compare AI model outputs and vote to form Elo-based rankings. Covers a wide range of categories including text, image, and video generation. |
| [Yupp Leaderboard](https://yupp.ai/leaderboard) | A leaderboard that ranks AI models based on community evaluation data, surfacing model quality through collective user insights from real-world usage. |
| [Open WebUI Leaderboard](https://openwebui.com/leaderboard) | A leaderboard ranking 100+ models based on actual user usage and ratings within the Open WebUI open-source LLM frontend community. |

## Coding & Software Development

| Name | Description |
| --- | --- |
| [DeepSWE](https://deepswe.datacurve.ai/) | Measuring frontier coding agents on original, long-horizon engineering tasks. |
| [SWE-rebench](https://swe-rebench.com/) | A software engineering benchmark that continuously updates with new tasks and uses time-window analysis to detect and eliminate data contamination. Designed to address contamination issues in SWE-bench. |
| [SWE-Bench Pro (Public)](https://labs.scale.com/leaderboard/swe_bench_pro_public) | A large-scale benchmark by Scale with 1,865 tasks. Uses copyleft-licensed code to prevent data contamination and rigorously evaluates AI problem-solving across diverse real-world tasks from B2B, consumer apps, and developer tools (public dataset). |
| [SWE-bench](https://www.swebench.com/) | A benchmark measuring how well AI can resolve bug fixes and feature implementations using real GitHub issues from OSS projects such as Django and Matplotlib. Offers multiple variants including Verified, Multilingual, and Multimodal. |
| [Convex LLM Leaderboard](https://www.convex.dev/llm-leaderboard/with-guidelines) | A leaderboard evaluating code generation quality for the Convex platform. Compares performance with and without guidelines, measuring the impact of prompt design in practice. |

## AI Agents

| Name | Description |
| --- | --- |
| [Terminal-Bench](https://www.tbench.ai/) | A benchmark evaluating AI agents' terminal operation capabilities by success rate across tasks spanning software development, ML, security, and data science. |
| [SanityHarness](https://sanityboard.lr7.dev/) | A high-signal leaderboard evaluating AI coding agents with weighted scoring across 26 tasks in multiple languages including Dart, Go, Kotlin, Rust, TypeScript, and Zig. |
| [τ-bench](https://taubench.com/#leaderboard) | A benchmark that simulates business scenarios such as airlines and retail, measuring AI agents' ability to complete tasks through user interaction and dialogue. |

## Math & Reasoning

| Name | Description |
| --- | --- |
| [FrontierMath](https://epoch.ai/frontiermath/tiers-1-4?view=graph&tab=leaderboard&tier=Core+%28Tiers+1-3%29) | A benchmark developed by Epoch AI that measures advanced mathematical reasoning with problems ranging from undergraduate level to unsolved research questions of increasing difficulty. |

## Creative Writing & Role-Playing

| Name | Description |
| --- | --- |
| [Japanese-RP-Bench](https://github.com/tegnike/Japanese-RP-Bench) | A benchmark for Japanese role-playing LLMs that evaluates conversation quality, role fidelity, persona stability, resistance to persona replacement and misleading instructions, and recovery afterward. Version 2 retains the original 30-role, 10-exchange base evaluation while adding adversarial challenge scenarios. |
| [Hemingway-bench](https://surgehq.ai/benchmarks/hemingway-bench) | A writing benchmark and leaderboard evaluated by professional writers across creative, business, and everyday writing tasks. It emphasizes taste, originality, coherence, and emotional intelligence, aiming to reward genuinely effective writing rather than surface-level signals such as elaborate metaphors. |
| [LLM Creative Story-Writing Benchmark](https://github.com/lechmazur/writing) | A short-story benchmark in which every model receives the same constrained creative brief and must meaningfully incorporate ten required elements, including a character, object, concept, attribute, action, method, setting, timeframe, motivation, and tone. Matched story pairs are judged by evaluator models, and the results are aggregated into a relative comparison score; the repository also publishes prompts, outputs, uncertainty ranges, and diagnostics such as word-count compliance. |
| [EQ-Bench Longform Creative Writing](https://eqbench.com/creative_writing_longform.html) | An LLM-judged long-form writing benchmark that tests planning a story from a minimal prompt, reflecting on and revising the plan, and writing a novella across eight roughly 1,000-word turns. Its rubric covers nuanced characters, emotional engagement, plot, coherence, tone, character consistency, plan and prompt adherence, as well as weak dialogue, tell-don't-show, clichés, amateurish writing, purple prose, and forced metaphors; it also reports repetition, LLM “slop,” and quality degradation across chapters. |
| [EQ-Bench Creative Writing](https://eqbench.com/creative_writing.html) | An LLM-judged creative writing leaderboard that evaluates outputs from 32 prompts using both rubric scoring and pairwise comparisons with a modified Glicko rating system. It assesses qualities such as originality, character authenticity, coherence, and instruction following, while also reporting repetition and overused LLM phrase (“slop”) metrics. |
| [Arena Creative Writing Leaderboard](https://arena.ai/leaderboard/text/creative-writing) | A community-driven Text Arena ranking for open-ended creative-writing tasks. Models are compared through anonymous user votes and ranked with an Elo-style score, with vote counts and uncertainty shown alongside the results; the page provides a large, continuously updated cross-model view, but the rankings reflect user preference rather than a fixed rubric or a single reproducible test set. |

## Cybersecurity

| Name | Description |
| --- | --- |
| [DeepSecBench](https://vercel.com/ai-gateway/leaderboards/deepsecbench) | A leaderboard measuring how effectively AI models find security vulnerabilities in application code using the DeepSec cyber harness. It combines recall and precision into a benchmark score and also compares false positives, cost, and execution time. |

## Embedding Models

| Name | Description |
| --- | --- |
| [MTEB Leaderboard](https://huggingface.co/spaces/mteb/leaderboard) | The Massive Text Embedding Benchmark leaderboard on Hugging Face, evaluating and comparing text embedding models across multiple tasks and languages using standardized methods. |
| [MMEB Leaderboard](https://huggingface.co/spaces/TIGER-Lab/MMEB-Leaderboard) | The Multimodal Embedding Benchmark leaderboard by TIGER-Lab, evaluating models that represent text and images in a unified embedding space. |

## Speech Recognition

| Name | Description |
| --- | --- |
| [Open ASR Leaderboard](https://huggingface.co/spaces/hf-audio/open_asr_leaderboard) | A Hugging Face leaderboard for automatic speech recognition (ASR) models, comparing recognition accuracy across multiple datasets. |
