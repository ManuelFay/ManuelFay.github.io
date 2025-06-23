---
layout: post
title: We release the "Context is Gold" paper on Contextual Document Embeddings !
date: 2025-06-02 16:11:00-0400
inline: false
related_posts: false
---

🚨 Excited to share our latest research: "Context Is Gold to Find the Gold Passage: Evaluating and Training Contextual Document Embeddings"!

📌 Why does context matter in retrieval?
 Standard dense retrievers typically embed passages in isolation, overlooking crucial context when relevant information spans multiple passages. Our research shows this limitation significantly impacts retrieval performance (RAG pipelines), especially in long & complex documents like those found in the industry.

📊 Introducing ConTEB (Contextual Text Embedding Benchmark): We've created ConTEB to quantify how well retrieval systems handle context. Results reveal major shortcomings in traditional embedding methods and highlight the benefits of embedding documents with contextual awareness.

✨ Our Solution: Combining Late Chunking with InSeNT loss
Late Chunking is a recent approach by Jina AI that computes embeddings by first encoding the entire document in one go, then pooling back into chunks. We optimize the technique with In-Sequence Negative Training, a lightweight fine-tuning strategy mixing in-sequence and in-batch negatives to further improve information propagation between document chunks.

📈 Results: Late Chunking alone yields a 9.0 nDCG@10 improvement on ConTEB. Combining Late Chunking with InSeNT achieves an impressive average boost of 23.6 nDCG@10! The benefits of training are even greater for Late Interaction models (ColBERT, ColPali) giving us many future ideas for how to improve text and visual document retrievers going forward!

More details and links in the blogpost 📰 : https://huggingface.co/blog/manu/conteb

Special thanks to my amazing co-first author Max Conti, as well as and to ILLUIN Technology, CentraleSupélec and IDRIS (CNRS) for their invaluable support!
