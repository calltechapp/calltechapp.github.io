---
title: "Evaluating Turkish Speech-to-Text Models: A Research Perspective from Calltech"
layout: single
date: 2025-04-15
author_profile: true
tags: [speech-to-text, whisper, wav2vec2, research, turkish]
---

As part of our ongoing research at Calltech, we’re excited to share a peer-reviewed publication exploring the performance of two leading speech-to-text (STT) models for Turkish: **Whisper-Small** and **Wav2Vec2-XLS-R-300M**.

📄 **The full paper is available here:**  
👉 <a href="https://dergipark.org.tr/tr/pub/tbbmd/issue/80549/1252487" target="_blank" rel="noopener noreferrer">Read the article</a>


### 🔍 Research Context

In our study, we fine-tuned both models on the open-source **Common Voice 11.0** dataset for Turkish. We then evaluated their performance on both that dataset and a **private call center audio set** that was never seen during training.

| Model               | WER (Test) | CER | Notes |
|--------------------|------------|-----|-------|
| Whisper-Small      | **0.16**   | 0.04| Faster training, better punctuation |
| Wav2Vec2-XLS-R-300M| 0.28       | 0.06| Longer training, but more flexible |

While Whisper-Small outperformed its counterpart in most areas, both models struggled slightly with noisy call center recordings, emphasizing the importance of real-world data during model training.

### 🤝 Why It Matters for Calltech

At Calltech, our platform processes thousands of call center conversations each day. This research strengthens our internal tools by guiding model selection and optimization for **accurate, Turkish-language STT** — a critical component in our **emotion detection** and **operator performance analytics** pipeline.

By blending academic research and commercial development, we aim to keep **Calltech.app** at the forefront of **voice AI for Turkish businesses**.

---
🧠 *This study was funded by TÜBİTAK TEYDEB 1501 (Project No: 3210713).*