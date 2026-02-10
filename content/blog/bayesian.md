+++
title = 'Bayesian Analysis'
date = 2025-05-06
draft = false
relPermalinkOverride = '/docs/bayesian.html'
tags = ['R', "Data Analytic", "Bayesian"]
+++

<style type="text/css">

body, td {
   font-size: 18px;
}
code.r{
  font-size: 12px;
}
pre {
  font-size: 12px
}
</style>


## What is Bayesian Analysis?

The paradigm of Bayesian analysis can be summarized as: For each
possible explanation of the sample, count all the ways the sample could
happen, explanations with more ways to produce the sample are more
plausible.

In Bayesian statistics, plausibility of the explanations is called
posterior:

$\underbrace {f(\theta|data)}_{posterior} =\underbrace {f(data|\theta)}_{likelihood}\underbrace{f(\theta)}_{prior}/\underbrace{f(data)}_{marginal\\likelihood}$

