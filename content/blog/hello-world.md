---
title: "Bayesian Analysis - Idea and Sampling Methods"
output: 
  html_document:
    toc: true
    toc_float:
      toc_collapsed: true
    toc_depth: 4
    theme: united
date: "2024-05-17"
---


## What is Bayesian Analysis?

The paradigm of Bayesian analysis can be summarized as: For each possible explanation of the sample, count all the ways the sample could happen, explanations with more ways to produce the sample are more plausible.

In Bayesian statistics, plausibility of the explanations is called posterior:

$\underbrace {f(\theta|data)}_{posterior}$

$ =\underbrace {f(data|\theta)}_{likelihood}\underbrace{f(\theta)}_{prior}/\underbrace{f(data)}_{marginal\\likelihood}$

Here, $\theta$ represents the a possible explanation for the data. Specifically, it is the set of parameters that define the underlying data-generating process. 