---
layout: article
title: Distributions for categorical data analysis
meta: Summary on fundamental distributions used in categorical data analysis
category: probability
tag: prob
---

## Binomial

For fixed number (n) of binary (success/failure) identical (same probability) independent (Bernoulli) trials. If \\(y_1, ..., y_n\\) are the responses each having probability $\pi$ of success then the total number of successes \\(Y = \sum_{i=1}^{n_1} Y_i\\) has a binomial mass function \\(Bin(n,\pi)\\).

$$p(y) = {n\choose k} \pi^y (1-\pi)^{n-y}= \frac{n!}{y!(n-y)!}\pi^y (1-\pi)^{n-y} \quad y=0,..n$$

For each trial, $y_i$ the expected value and variance are \\(E[Y_i]=\pi\\), \\(Var(Y_i)=\pi(1-\pi)\\). The total number of successes have expected value \\(\mu = E[Y] = n\pi\\) and \\(\sigma^2=Var(Y) = n\pi(1-\pi)\\). The distribution converges to Normal as \\(n\\) increases for fixed \\(\pi\\).

$$

$$


# References

<http://rangerway.com/way/latex-note-and-jekyll/>
<http://www.personal.ceu.hu/tex/cookbook.html>
<http://gohugo.io/tutorials/mathjax/>
<http://docs.mathjax.org/en/latest/tex.html>
