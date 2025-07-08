---
layout: post
title: We release "Should We Still Pretrain Encoders with Masked Language Modeling?"
date: 2025-07-03 16:11:00-0400
inline: false
related_posts: false
---

Are BERT-style encoders with Masked Language Modeling (MLM) outdated? Our new study explores whether they outperform Causal Language Modeling (CLM) decoders for text representation tasks. By pretraining 30 models and finetuning 15k checkpoints, the research reveals that while MLM models edge out CLM decoders in performance, CLM offers better data efficiency and finetuning stability. A hybrid CLM+MLM pretraining approach emerges as a winner, blending the best of both worlds. Intriguingly, adapting pretrained CLM decoders with MLM outperforms continuing MLM on existing encoders, suggesting a cost-effective way to create state-of-the-art encoders. Check out the full paper and open-source models for more!

Twitter: https://x.com/ManuelFaysse/status/1940396582748422311

Arxiv: https://arxiv.org/abs/2507.00994

