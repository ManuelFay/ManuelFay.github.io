---
layout: post
title: We release EuroBERT !
date: 2025-03-10 16:11:00-0400
inline: false
related_posts: false
---


🚨 Today, we release EuroBERT: a multilingual encoder model family (210M to 2.1B parameters) trained on 5T tokens across 15 languages, with support for sequences up to 8,192 tokens. It’s open-source and designed to power multilingual retrieval, classification, and embeddings.


🔹 Why EuroBERT?

✅ State-of-the-art performance across multilingual retrieval, classification, and regression

✅ Long-context support (8,192 tokens) for document-level understanding

✅ Mathematics & Code training for improved reasoning

✅ Outperforms XLM-RoBERTa, mGTE, and other leading models


EuroBERT builds upon our team’s experience training EuroLLM & CroissantLLM, but encoders are NOT decoders and require specific design decisions! We ran extensive ablations on masking ratios, language and data distributions, annealing, and data quality to ensure optimal performance.

📢 Beyond the results we report, nothing beats people fine-tuning the model for their usecases and sharing real-world feedback, so feel free to do so, everything is on the HuggingFace page !

More details and links in the [blog](https://lnkd.in/e9PRm_YS)

Work led by Nicolas BOIZARD Hippolyte Gisserot-Boukhlef Duarte Alves Pierre Colombo and with many other great co-authors !
