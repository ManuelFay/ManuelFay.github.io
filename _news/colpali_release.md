---
layout: post
title: We release ColPali - Efficient Document Retrieval with Vision Language Models 👀 !
date: 2024-06-21 07:59:00-0400
inline: false
related_posts: false
---

***

We release [ColPali: Efficient Document Retrieval with Vision Language Models](https://arxiv.org/abs/2407.01449).
Super nice response from the community !

Our newest research project is out, and aims to solve one of the biggest current problem in RAG (Retrieval Augmented Generation) with PDF documents ! Introducing "ColPali: Efficient Document Retrieval with Vision Language Models".

🔍 In many practical use cases, to answer a user query, it is first useful to search for relevant information in a given corpus before attempting to answer. Modern "document retrieval" systems often rely on complex pipelines to first parse the PDF documents in the corpus (running OCR, segmenting pages into paragraphs / titles / figures, captioning the images, etc.), then embed all textual content using deep learning models to store the resulting vectors in an index database. After indexing, user queries can be matched "online" rapidly to the most relevant documents in the index.

❌ This whole indexing process tends to be complex and slow, and often fails to consider much of the more visual elements of a page (tables, figures, images but also fonts and text colors), that also carry a lot of the information...

💡Our concept: Instead of first extracting the text from the document, we just embed an image of the document page directly to keep most of the information ! To obtain good performance with this concept, we leverage modern Vision Language Models that are able to read and understand text, tables, and figures from the images. We also boost performance using "late interaction" mechanisms which enable us to store multiple embeddings per page to maximize information content, all the while maintaining the super fast query-matching speeds modern systems enable.

📈 Turns out it works super well ! Our model ColPali largely outperforms very strong baselines on visually rich document retrieval, all the while enabling orders of magnitude faster indexing speeds ! The concept has already been quite a hit in the research community, and there's still a ton of improvements we will be rolling out to continue pushing this paradigm we really believe in !

📝 The paper: https://lnkd.in/ejq4hnJf
🗃️ The benchmark: https://lnkd.in/e7r9PQ7N
👀 The model: https://lnkd.in/eed2eB3F
📰 The blogpost: https://lnkd.in/eJg5Mu-d

Joint work with Hugues Sibille, Tony Wu, Bilel Omrani, Gautier Viaud from ILLUIN Technology, and Celine Hudelot + Pierre Colombo from CentraleSupélec, with compute funding from the amazing team at CINES !
