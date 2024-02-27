---
layout: post
title: Paper accepted at EMNLP 2023 (Oral) !
date: 2023-11-07 16:11:00-0400
inline: false
related_posts: false
---

LinkedIn post in French detailing the work !

***

Les Large Language Models #LLMs sont partout...
➡️ Entre les modèles d'OpenAI (GPT4, GPT3.5), leurs concurrents propriétaires (Anthropic, Google, Cohere) et la panoplie de modèles libres d'accès qui émergent (Mistral, Llama2, Yi), comment faire le bon choix pour son cas d'usage ?

Il y a évidemment des considérations pratiques qui entrent en jeu (souveraineté des données, coût d'hébergement, vitesse d'inférence) mais le plus important reste souvent la performance ! Et alors que les modèles génératifs d'il y a quelques années étaient souvent spécialisés sur une unique tâche (traduction, résumé) qu'on arrivait (plutôt) bien à évaluer automatiquement, les modèles actuels sont justement intéressants car ils sont généralistes et capable de répondre à des instructions arbitraires !


Pour évaluer la qualité de génération de ces LLMs automatiquement, il faut donc trouver des métriques d'évaluation automatique qui:

1️⃣ sont fortement corrélées avec le jugement humain

2️⃣ notent sur une échelle cohérente quelle que soit la tâche

3️⃣ sont auto-portantes et ne nécessitent pas d'exemple de réponse correcte pour calculer leur notes...


💡 C'est le sujet de l'article qu'on présentera à Singapour début décembre pour #emnlp2023, la meilleure conférence du domaine ! On trouve notamment que se servir d'autres LLMs en tant qu'évaluateurs présente un réel interet par rapport aux solutions actuelles, ce qui nous permet dans un deuxième temps de tirer plein d'enseignements sur les processus d'entrainement optimaux pour adapter des LLMs open-source à des cas d'usage industriels !

Pour ceux qui veulent rentrer davantage dans les détails techniques, je mets les liens en commentaire de l'article et de mon Twitter !

Travail effectué avec Pierre Colombo Gautier Viaud Celine Hudelot, le premier article de mon doctorat au sein de CentraleSupélec et ILLUIN Technology !