---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---
## Projects

### LSTM vs Transformers for Time Series Modeling
![Example graph of LSTM vs Transformers](/images/lstm_transformer_ex_graph.png)
A comparison analysis between LSTM and Transformer models in the context of time-series forecasting. While LSTMs have long been a cornerstone, the advent of Transformers has sparked significant interest due to their attention mechanisms. In this study, we pinpoint which particular features of time series datasets could lead transformer-based models to outperform LSTM models. [[**Blog**]](https://deep-learning-mit.github.io/staging/blog/2023/time-series-lstm-transformer/)
[[**Code**]](https://github.com/rwxhuang/lstm_vs_transformers)

### Predicting Volume from Silent Videos
![Architecture Diagram](/images/architecture_diagram.png)
From movies to video games, sound plays a crucial role in our perception of the world. In this project, we aim to predict the volume of visually indicated sounds (VIS) from silent video scenes. We present a model involving a recurrent-neural network composed of a CNN and an LSTM, trained on an existing drumsticks dataset and a novel impacts dataset of our making. We find that our model generally predicts the occurrences of auditory inflection points in video correctly, but needs further improvement in estimating the volume of the inflection points accurately. [[**Paper**]](/files/comp_vision_final_project.pdf)

## Research

### Empirical Bayes using Deep Neural Networks: g-modeling vs f-modeling
Researched empirical Bayes estimation via two main modeling strategies (g-modeling and f-modeling), and developing methodology to implement the above strategies using deep neural networks. Presented on Glow, a normalizing flow-based generative model with invertible 1x1 convolutions. [[**Presentation**]](/files/glow_presentation.pdf)
