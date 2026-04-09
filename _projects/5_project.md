---
layout: page
title: AI vs. Human Text Detection
description: Comparative analysis of fine-tuned LLMs for AI text detection.
importance: 5
category: Data Science
---

A comparative study in Natural Language Processing focused on identifying AI-generated text. This project involved fine-tuning multiple architectures using Parameter-Efficient Fine-Tuning (PEFT) and analyzing model decision-making through interpretability frameworks.

### Technical Stack
* **Primary Model:** RoBERTa-base (Fine-tuned)
* **Benchmark Models:** Llama 3.2 (1B), DistilBERT-base-uncased
* **Fine-Tuning:** [LoRA (PEFT)](https://huggingface.co/docs/peft/index), Hugging Face Transformers
* **Interpretability:** [LIME](https://github.com/marcotcr/lime) (Local Interpretable Model-agnostic Explanations)
* **Analysis:** McNemar Statistical Testing, Python, Flask

### Core Capabilities
* Targeted Fine-Tuning: Executed LoRA (Low-Rank Adaptation) on RoBERTa-base, optimizing only 0.71% of total parameters (887k) to achieve near-state-of-the-art performance with minimal hardware requirements.
* Comparative Benchmarking: Evaluated model performance across 480k records, identifying **RoBERTa as the optimal model** for production due to a 4x faster training speed compared to Llama 3.2 while maintaining a high 96.7% F1-score.
* Model Interpretability: Integrated LIME explanations to visualize linguistic feature importance, validating that the fine-tuned model correctly identified structural patterns in AI text rather than over-fitting on specific keywords.
* Statistical Validation: Applied McNemar tests to establish that RoBERTa significantly outperformed the DistilBERT baseline, proving the efficacy of the fine-tuning approach for complex text classification.
