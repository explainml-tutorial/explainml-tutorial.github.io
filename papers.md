
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
In this section, we provide pointers to the approaches discussed in the tutorial.

### Local Explanations

#### Feature Importance Approaches
- **LIME**: "Why Should I Trust You?" Explaining the Predictions of Any Classifier. *Ribeiro et al. 2017* [link](https://arxiv.org/abs/1602.04938)
- **SHAP**: A Unified Approach to Interpreting Model Predictions. *Lundberg and Lee, 2017* [link](https://arxiv.org/abs/1705.07874)
- **ANCHORS**: Anchors: High Precision Model-Agnostic Explanations. *Ribeiro et al. 2018* [link](https://homes.cs.washington.edu/~marcotcr/aaai18.pdf)

#### Feature Importance Approaches: Saliency Maps / Feature Attributions
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

#### Prototype / Example Based Approaches
- **Influence Functions**: Understanding Black-box Predictions via Influence Functions. *Koh and Liang 2017* [link](https://arxiv.org/abs/1703.04730)
- **Influence Functions and Non-convex models**: Influence functions in Deep Learning are Fragile. *Basu et. al. 2020* [link](https://arxiv.org/abs/2006.14651)
- **Representer Points**: Representer Point Selection for Explaining Deep Neural Networks. *Yeh et. al. 2018* [link](https://arxiv.org/abs/1811.09720)
- **TracIn**: Estimating Training Data Influence by Tracing Gradient Descent. *Garima et al. 2020* [link](https://arxiv.org/abs/2002.08484)
- **Activation Maximization**: Visualizing higher layer Features of a Deep Network. *Erhan et al. 2009* [link](http://www.iro.umontreal.ca/~lisa/publications2/index.php/publications/show/247)
- **Feature Visualization**: Feature Visualization. *Olah et al. 2017* [link](https://distill.pub/2017/feature-visualization/)

#### Counterfactuals
- **Minimum Distance Counterfactuals**: Counterfactual Explanations without Opening the Black Box: Automated Decisions and the GDPR. *Wachter et al. 2017* [link](https://arxiv.org/abs/1711.00399)
- **Feasible and Least Cost Counterfactuals**: Actionable Recourse in Linear Classification. *Ustun et. al., 2019* [link](https://arxiv.org/pdf/1809.06514.pdf)
- **Causally Feasible Counterfactuals**: Preserving Causal Constraints in Counterfactual Explanations for Machine Learning Classifiers. *Mahajan et al. 2020* [link](https://arxiv.org/abs/1912.03277) and Model-Agnostic Counterfactual Explanations for Consequential Decisions. *Karimi et. al. 2020* [link](https://arxiv.org/abs/1905.11190)
