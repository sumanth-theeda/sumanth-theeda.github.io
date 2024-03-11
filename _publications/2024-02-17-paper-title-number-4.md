---
title: "Optimization of process parameters in laser powder bed fusion of SS 316L parts using artificial neural networks"
collection: publications
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'In the present work, an exclusive neural network is developed to demonstrate the potential of a single neural network in optimizing multiple part properties of additively manufactured parts. The model is used to identify the optimal process parameter values for laser power, scan speed, and hatch spacing for the required surface roughness, relative density, microhardness, and dimensional accuracy in stainless steel parts.'
date: 2023-04-25
venue: 'Metals'
paperurl: 'https://doi.org/10.3390/met13050842'
citation: 'Theeda, Sumanth, et al. "Optimization of process parameters in laser powder bed fusion of SS 316L parts using artificial neural networks." Metals 13.5 (2023): 842.'
---

Additive manufacturing is rapidly evolving and revolutionizing the fabrication of complex metal components with tunable properties. Machine learning and neural networks have emerged as powerful tools for process–property optimization in additive manufacturing. These techniques work well for the prediction of a single property but their applicability in optimizing multiple properties is limited. In the present work, an exclusive neural network is developed to demonstrate the potential of a single neural network in optimizing multiple part properties. The model is used to identify the optimal process parameter values for laser power, scan speed, and hatch spacing for the required surface roughness, relative density, microhardness, and dimensional accuracy in stainless steel parts. In-house-generated experimental data are used to train the model. The model has seven neurons in the hidden layer, which are selected using hyperparameter optimization. K-fold cross-validation is performed to ensure the robustness of the model, which results in a mean squared error of 0.0578 and R2 score of 0.59. The developed model is then used to predict the optimal process parameters corresponding to the user-required part properties. The model serves as a significant pre-processing step to identify the best parameters before printing, thus saving time and costs for repeated part fabrication. The study provides more insights into the usage of a single artificial neural network for the optimization of multiple properties of printed metal parts.

![Neural Network Architechture for process parameters](/images/metals_opti.png)
