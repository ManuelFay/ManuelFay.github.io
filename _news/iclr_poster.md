---
layout: post
date: 2025-04-25 07:59:00-0400
inline: false
related_posts: false
title: ICLR Poster Session
---

I presented our poster ["ColPali: Efficient Document Retrieval with Vision Language Models"](https://arxiv.org/abs/2407.01449) at ICLR !


The original paper starts to be a bit dated as it was released in June, but I decided to create a poster that stays true to the original work. For all the novelties, follow me on X!

![poster](/assets/img/colpali/ColPali-high-res.png)


### What about more recent stuff ? 

Since the release, newer and better ColVision models were released. Most of them are on the [online leaderboard](https://huggingface.co/spaces/vidore/vidore-leaderboard) but just to visualize a few:

![image](/assets/img/colpali/perf_vs_size.jpeg)

Don't forget about bi-encoder models, which work very well as well and can be more practical to deploy ! 

We also had to iterate on the ViDoRe benchmark as it was becoming too easy for recent models! While the V2 is a work in progress, and new tasks will get added, we managed to create harder tasks while keeping a consistent signal. Read more in the [blogpost](https://huggingface.co/blog/manu/vidore-v2).

![image](/assets/img/colpali/vidorev2.jpeg)
