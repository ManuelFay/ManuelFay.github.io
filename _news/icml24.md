---
layout: post
title: Accepted paper at ICML 2024
date: 2024-05-04 07:59:00-0400
inline: false
related_posts: false
---

Our work on [Copyright Traps for Large Language Models](https://arxiv.org/abs/2402.09363) has been accepted at ICML 2024 !

***

To what extent do Large Language Models (LLMs) remember their training data? 
Can we detect whether a model has been trained on particular data samples?
What does that imply in terms of copyrighted content watermarking, and data privacy?
Our work "Copyright Traps for Large Language Models" that we are presenting this week at ICML in Vienna attempts to tackle these questions!

➡️ A little known fact about 🥐 CroissantLLM is that we inserted a few special text sequences amongst the 3 trillion token training set in order to study model memorization in a rare, randomized controlled experimental setup.
These "trap" sequences represent less than 0.04% of the data, and are designed to be unlikely to be filtered out by dataset preprocessing methods.
Measuring the extent to which CroissantLLM "remembers" these sequences enables us to better understand the settings under which memorization occurs.
Typically, we find that "trap" sequences that have been repeated in the training set a higher number of times, that are lengthier, or that are more "surprising" tend to be easier to detect.


💡 What does this mean? For CroissantLLM, in which internet data is never repeated more than 4 times, it reassures on the fact no individual sequence has a real chance of being remembered by the model. Thus, no risk of the model leaking out social security numbers or other sensitive information that slipped into the training set!

🪤 Focusing on the problem the other way around, it also means data owners could design and insert "copyright traps" within their data, to be able to accurately detect whether it has been used to train language models!

For more information, don't hesitate to go check out:

📜 Our paper: https://arxiv.org/abs/2402.09363

📰 The CroissantLLM report: https://arxiv.org/abs/2402.00786

🪧 For those attending #ICML, the poster session on July 23rd!

This work is a collaboration with Matthieu Meeus, Igor Shilov and Yves-Alexandre de Montjoye from The Computational Privacy Group of Imperial College London!
I was super glad to also be able to explore these privacy-related aspects of LLMs as part of my PhD with CentraleSupélec and Illuin Technology in which I generally focus on more industrial applications.
