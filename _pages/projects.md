---
layout: page
permalink: /projects/
title: Projects
description: Open research in language models and document retrieval.
nav: true
nav_order: 2
---

<div class="research-projects">
  <p class="projects-intro">Three projects spanning how we read documents, train language models, and bring context into search. Explore the papers and use the open-source tools below.</p>

  <div class="project-cards">
    <article class="research-card project-vision" aria-labelledby="project-colpali">
      <div class="project-visual" aria-hidden="true">
        <img src="{{ '/assets/img/publication_preview/colpali.png' | relative_url }}" alt="" width="512" height="512">
        <span>Read beyond text</span>
      </div>
      <div class="project-content">
        <p class="project-category">Visual document retrieval</p>
        <h2 id="project-colpali">ColPali &amp; ViDoRe</h2>
        <p>Search documents directly from page images, preserving the tables, figures, and layouts that text extraction can miss. ColPali builds visual retrieval models; ViDoRe provides the benchmarks to evaluate them.</p>
        <nav class="project-links" aria-label="ColPali and ViDoRe resources">
          <a class="project-paper" href="https://arxiv.org/abs/2407.01449">Paper <span aria-hidden="true">&#8599;&#65038;</span></a>
          <a href="https://github.com/illuin-tech/colpali">Code <span aria-hidden="true">&#8599;&#65038;</span></a>
          <a href="https://huggingface.co/vidore">Models <span aria-hidden="true">&#8599;&#65038;</span></a>
          <a href="https://github.com/illuin-tech/vidore-benchmark">Benchmark <span aria-hidden="true">&#8599;&#65038;</span></a>
        </nav>
      </div>
    </article>

    <article class="research-card project-language" aria-labelledby="project-croissant">
      <div class="project-visual" aria-hidden="true">
        <img src="{{ '/assets/img/publication_preview/croissant.png' | relative_url }}" alt="" width="512" height="512" loading="lazy">
        <span>Two languages. One model.</span>
      </div>
      <div class="project-content">
        <p class="project-category">Language model pretraining</p>
        <h2 id="project-croissant">CroissantLLM</h2>
        <p>A 1.3B-parameter language model trained for both French and English. An open pretraining effort sharing the models, training code, and data to make bilingual language model research easier to reproduce.</p>
        <nav class="project-links" aria-label="CroissantLLM resources">
          <a class="project-paper" href="https://arxiv.org/abs/2402.00786">Paper <span aria-hidden="true">&#8599;&#65038;</span></a>
          <a href="https://github.com/CoderPat/croissant-llm-training">Code <span aria-hidden="true">&#8599;&#65038;</span></a>
          <a href="https://huggingface.co/croissantllm">Models &amp; data <span aria-hidden="true">&#8599;&#65038;</span></a>
        </nav>
      </div>
    </article>

    <article class="research-card project-context" aria-labelledby="project-context">
      <div class="project-visual" aria-hidden="true">
        <img src="{{ '/assets/img/publication_preview/context.png' | relative_url }}" alt="" width="512" height="512" loading="lazy">
        <span>Keep the bigger picture</span>
      </div>
      <div class="project-content">
        <p class="project-category">Contextual embeddings · ConTEB &amp; InSeNT</p>
        <h2 id="project-context">Context is Gold</h2>
        <p>Give each passage the context of its surrounding document. ConTEB tests retrieval when context matters, while InSeNT trains embeddings to use it through late chunking and in-sequence negative training.</p>
        <nav class="project-links" aria-label="Context is Gold resources">
          <a class="project-paper" href="https://arxiv.org/abs/2505.24782">Paper <span aria-hidden="true">&#8599;&#65038;</span></a>
          <a href="https://github.com/illuin-tech/contextual-embeddings">Code <span aria-hidden="true">&#8599;&#65038;</span></a>
          <a href="https://huggingface.co/illuin-conteb">Models &amp; data <span aria-hidden="true">&#8599;&#65038;</span></a>
        </nav>
      </div>
    </article>
  </div>

  <p class="projects-more">Explore more <a href="{{ '/publications/' | relative_url }}">publications</a> and <a href="{{ '/repositories/' | relative_url }}">repositories</a>, or <a href="https://manuelfay.github.io/web-thesis/">read my thesis</a>.</p>
</div>
