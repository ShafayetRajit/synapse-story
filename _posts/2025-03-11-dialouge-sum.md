---
title: "Dialogue Summarization using Gemma 2B"
layout: post
date: 2025-03-11 22:48
star: false
image: 
headerImage: false
tag:
- nlp
- LLM
- projects
category: blog
author: shafayetrajit
description: 
---

Dialogue summarization is gaining importance with growing reliance on automated communication tools. Efficient summarization models can significantly impact areas such as customer service, meeting transcription, legal documentation, and interview analysis.

## Why Gemma 2B?

I chose Gemma 2B, a compact yet powerful Large Language Model (LLM), optimized for resource-limited environments. Its decoder transformer architecture, coupled with multi-head attention and rotary positional embeddings, provides the necessary computational efficiency for accurate dialogue summarization, albeit with some performance trade-offs compared to larger models.

## Leveraging DialogSum for Model Training

The DialogSum dataset, featuring 13,460 dialogues and associated summaries, was employed to fine-tune the Gemma model. This dataset is especially valuable due to its manual annotations, enabling the model to grasp the intricate dynamics of human conversations. Importantly, utilizing this dataset addresses real-world summarization needs, helping the model cater to diverse practical applications.

## Fine-Tuning and Model Evaluation

Fine-tuning Gemma 2B with DialogSum involved extensive experimentation with summarization tasks. Evaluation metrics like ROUGE-1, ROUGE-2, ROUGE-L, and ROUGE-Lsum were employed, with Gemma 2B achieving a moderate performance with scores around 0.34 (precision), 0.32 (recall), and 0.30 (F1 Score). Although these metrics show room for improvement, they reflect promising initial results, especially given the model’s compact size and accessibility.

## Insights and Potential Enhancements

Gemma's moderate ROUGE scores indicate both the model’s capability and the areas requiring refinement. Future enhancements through better prompt engineering and larger datasets can significantly improve accuracy and utility. 

## Key Takeaways

Gemma 2B demonstrates considerable potential in dialogue summarization. With continued fine-tuning and exploration of optimal prompt engineering, Gemma could become a reliable, efficient summarization tool tailored for practical applications across various industries.

<br>

*[Github repo](https://github.com/ShafayetRajit/Dialogue-Summarization-using-Gemma-2B)* 


<br>

<span style="color:gray"><em>This post provides a high-level overview of the project, covering key aspects and insights. It does not go in-depth but gives a general idea&mdash;how it was built and what it does. If you're curious about the details, feel free to explore the code or reach out!</em></span>