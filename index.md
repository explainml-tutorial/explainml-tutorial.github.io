---
title: Tutorial Overview
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: single
classes: wide
author_profile: false
speaker_row:
  - image_path: assets/images/hima.jpg
    alt: "Himabindu Lakkaraju"
    title: "Hima Lakkaraju"
    excerpt: "Harvard University"
    url: "https://himalakkaraju.github.io/"
    btn_label: "Homepage"
    btn_class: "btn--primary"
  - image_path: assets/images/julius.jpg
    alt: "Julius Adebayo"
    title: "Julius Adebayo"
    excerpt: "MIT"
    url: "https://juliusadebayo.com/"
    btn_label: "Homepage"
    btn_class: "btn--primary"
  - image_path: assets/images/sameer.png
    alt: "Sameer Singh"
    title: "Sameer Singh"
    excerpt: "UC Irvine"
    url: "http://sameersingh.org"
    btn_label: "Homepage"
    btn_class: "btn--primary"
venue_row:
  - image_path: assets/images/neurips.png
    alt: "NeurIPS 2020"
    title: "NeurIPS 2020"
    # excerpt: "Harvard University"
    url: "/neurips20"
    btn_label: "Materials"
    btn_class: "btn--primary"
  - image_path: assets/images/aaai.png
    alt: "AAAI 2021"
    title: "AAAI 2021"
    excerpt: "Coming Soon"
---

As machine learning is deployed in all aspects of society, it has become increasingly important to ensure stakeholders understand and trust these models. Decision makers must have a clear understanding of the model behavior so they can diagnose errors and potential biases in these models, and decide when and how to employ them. However, most accurate models that are deployed in practice are not interpretable, making it difficult for users to understand where the predictions are coming from, and thus, difficult to trust. Recent work on explanation techniques in machine learning offers an attractive solution: they provide intuitive explanations for “any” machine learning model by approximating complex machine learning models with simpler ones.

In this tutorial, we will discuss several post hoc explanation methods, and focus on their advantages and shortcomings. We will cover three families of techniques: (a) single instance gradient-based attribution methods (saliency maps), (b) model agnostic explanations via perturbations, such as LIME and SHAP, and (c) surrogate modeling for global interpretability, such as MUSE. For each of these approaches, we will provide their problem setup, prominent methods, example applications, and finally, discuss their vulnerabilities and shortcomings. We hope to provide a practical and insightful introduction to explainability in machine learning.

# Speakers

{% include feature_row id="speaker_row" %}


# Tutorials

{% include feature_row id="venue_row" %}

<!-- <h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Posts" }}</h3> -->

<!-- {% if paginator %}
  {% assign posts = paginator.posts %}
{% else %}
  {% assign posts = site.posts %}
{% endif %}

{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %} -->