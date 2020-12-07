---
layout: single
classes: wide
permalink: /neurips20
title: NeurIPS 2020 Tutorial
---

Welcome to the accompanying page for the NeurIPS 2020 tutorial on **"Explaining Machine Learning Predictions: State-of-the-art, Challenges, and Opportunities"**.

The live tutorial will take place on **Monday, December 7th, 2020**, at 1:30pm PT. A follow-up QA session will take place on **Wednesday, December 9th, 2020**, at 3:00am PT. Details and links to joining the sessions are available here:

<a class="btn btn--primary" href="https://neurips.cc/virtual/2020/public/tutorial_59e711d152de7bec7304a8c2ecaf9f0f.html">Virtual Site</a>



# Video

{% include video id="EbpU4p_0hes" provider="youtube" %}

<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/EbpU4p_0hes" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->

# Slides

<a class="btn btn--primary" href="assets/files/explainml-tutorial-neurips20.pdf">Download (PDF)</a>
<a class="btn btn--info" href="https://docs.google.com/presentation/d/e/2PACX-1vRXRfXCI_tuynZHD6wkoHO2TNh3WVPK1Q0IkEzWdHAtzm5jEEbMWbvS5eAvFeJuFS0IO01qLMGi7diT/pub?start=false&loop=false&delayms=3000">Google Slides</a>

<div style="position: relative;    width: 100%;    padding-top: 60%;    overflow: hidden;">
    <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRXRfXCI_tuynZHD6wkoHO2TNh3WVPK1Q0IkEzWdHAtzm5jEEbMWbvS5eAvFeJuFS0IO01qLMGi7diT/embed?start=false&loop=false&delayms=3000" frameborder="0" width="640" height="389" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true" style="position: absolute;    top: 0;    left: 0;    width: 100%;    height: 100%;"></iframe>

</div>


# Annotated Bibliography and Resources
In this section, we provide a pointer to relevant papers for the content of the tutorial. Due to time and space limitation, we were not able to discuss all relevant papers in the tutorial, but here, we provide an expanded overview of relevant literature. We are happy to update the material here with pointers to material that we might have missed. We will proceed according to the agenda discussed in the tutorial.

## Introduction
- Towards a rigorous science of interpretable machine learning. *Doshi-Velez and Kim 2017* [link](https://arxiv.org/abs/1702.08608)
- The Mythos of Model Interpretability. *Lipton 2017* [link](https://arxiv.org/abs/1606.03490)
- Transparency: Motivations and Challenges. *Weller 2017* [link](https://arxiv.org/abs/1708.01870)
- Explaining Explanations: An Overview of Interpretability of Machine Learning. *Gilpin et al. 2019* [link](https://arxiv.org/abs/1806.00069)
- Interpretable machine learning: definitions, methods, and applications. *Murdoch et al. 2019* [link](https://arxiv.org/pdf/1901.04592v1.pdf)
- Stop Explaining Black Box Machine Learning Models for High Stakes Decisions and Use Interpretable Models Instead. *Rudin 2019* [link](https://www.nature.com/articles/s42256-019-0048-x)

## Approaches for Post hoc Explainability
In this section, we provide pointers the approaches discussed in the tutorial.

### Local Explanations
Feature Importance approaches: Surrogate approaches.
- **LIME**: "Why Should I Trust You?" Explaining the Predictions of Any Classifier. *Ribeiro et al. 2017* [link](https://arxiv.org/abs/1602.04938)
- **SHAP**: A Unified Approach to Interpreting Model Predictions. *Lundberg and Lee, 2017* [link](https://arxiv.org/abs/1705.07874)
- **ANCHORS**: Anchors: High Precision Model-Agnostic Explanations. *Ribeiro et al. 2018* [link](https://homes.cs.washington.edu/~marcotcr/aaai18.pdf)

Feature importance techniques in the form of saliency maps.
- **Input-Gradient**: How to Explain Individual Classification Decisions. *Baehrens et. al. 2009* [link](https://arxiv.org/abs/0912.1128) and Deep Inside Convolutional Networks: Visualizing Image Classification Models and Saliency Maps. *Simonyan et. al. 2014* [link](https://arxiv.org/abs/1312.6034).
- **SmoothGrad**: SmoothGrad: removing noise by adding noise. *Smilkov et. al. 2018* [link](https://arxiv.org/abs/1706.03825)
- **Integrated Gradients**: Axiomatic Explanation form Deep Networks. *Sundararajan et. al. 2018* [link](https://arxiv.org/abs/1703.01365)
- **Gradient-Input**: Not Just a Black Box: Learning Important Features Through Propagating Activation Differences *Shrikumar et. al. 2016* [link](https://arxiv.org/abs/1605.01713) and Towards better understanding of gradient-based attribution methods for Deep Neural Networks *Ancona et. al. 2018* [link](https://arxiv.org/abs/1711.06104)

Saliency map techniques that derive relevance via a modified back-propagation process.
- **Guided BackProp**: Striving for simplicity: The all convolutional net. *Springenberg and Dosovitskiy et. al. 2015* [link](https://arxiv.org/abs/1412.6806)
- **DeConvNet**: Visualizing and understanding convolutional networks. *Zeiler and Fergus 2014* [link](https://arxiv.org/abs/1311.2901)
- **Layer Relevance Propagation Family (LRP)**: See link for discussion on these family of methods. [link](http://heatmapping.org/)

For an overview of additional saliency methods we refer to:

- **Overview Article**: Toward Interpretable Machine Learning:
Transparent Deep Neural Networks and Beyond. *Samek and Montavon 2020* [link](https://arxiv.org/pdf/2003.07631.pdf)
