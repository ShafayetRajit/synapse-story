---
title: "Multi-label Classification of Bengali Hate Comments on Social Media"
layout: post
date: 2025-03-09 22:48
image: 
headerImage: false
tag:
- nlp
- projects
category: blog
author: shafayetrajit
description: 
---
The internet is a powerful platform for communication, but it also exposes users to toxic content. From hate speech to trolling, online discussions can sometimes become hostile. To address this, our project explores a multi-label classification model that detects different types of toxicity in comments.

## Understanding Toxicity Classification

Unlike simple binary classification (toxic or not), this project identifies multiple forms of toxicity in a single comment. We categorized toxicity into six distinct types:

- Insult
- Troll
- Threat
- Religious intolerance
- Hate speech
- Vulgar language



A multi-label classifier was trained to recognize these categories, allowing a single comment to be classified under multiple labels.

## The Model: CNN-BiLSTM with BERT Encoding

We leveraged CNN-BiLSTM architecture combined with BERT encoding to analyze textual data efficiently.

- BERT (Bidirectional Encoder Representations from Transformers) was used for high-quality text embeddings.
- CNN (Convolutional Neural Networks) helped capture local word dependencies.
- BiLSTM (Bidirectional Long Short-Term Memory) retained contextual meaning from both past and future words.

## Optimizing Performance
To enhance the model's accuracy, we experimented with:

- Activation Functions: Compared ReLU, Sigmoid, and Tanh to determine the best fit.
- Optimizers: Tested Adam, RMSprop, and SGD for optimal convergence.
- Regularization: Applied dropout and L2 regularization to prevent overfitting.
- Normalization: Standardized input data to improve stability.



After extensive testing, we found that ReLU as the activation function, Adam as the optimizer, and Dropout for regularization produced the best results, delivering improved accuracy and robustness in toxicity classification.

## Key Takeaways

Our findings highlight the importance of fine-tuning parameters for better text classification. Future work could explore transformer-based architectures like GPT for even better accuracy. With AI-driven moderation, online spaces can become safer and more inclusive.

<br>

*[Github repo](https://github.com/ShafayetRajit/Multi-label-Classification-of-Bengali-Hate-Comments-on-Social-Media)*


<br>

<span style="color:gray"><em>This post provides a high-level overview of the project, covering key aspects and insights. It does not go in-depth but gives a general idea&mdash;how it was built and what it does. If you're curious about the details, feel free to explore the code or reach out!</em></span>