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

## Multinomial

For situations where more than two outcomes occur. If $y_{ij}=1$ or $y_{ij}=0$ then the vector $\vec{y_i}=(y_{i1},y_{i2},...y_{yc})$ represents the result of a multinomial trail with $\sum y_{ij}=1$. For example, $(0,0,1,0)$ denotes an outcome in category 3. If $n_i=\sum y_{ij}$ is the count of trials having outcome in category $j$ then the counts $(n_1, n_2, ...n_c)$ is multinomial with mass function.

$$p(n_1,n_2,...,n_{c-1}) = \frac{n!}{n_1!n_2!...n_c!} \pi_1^{n_1} \pi_2^{n_2} ... \pi_c^{n_c}$$

The expected value is $E[n_j]= n\pi_j$, the variance is $Var(n_j)=n \pi_j(1-\pi_j)$ and the covariance is $cov(n_j,n_k)=-n\pi_j\pi_k$.

## Poisson

The response counts are not always associated with a fixed number of trials. The Poisson distribution is used for events that occur randomly over time or space.

$$p(y)=\frac{\mu^y}{y!}\exp{-\mu} \quad y=0,1...$$

The expectation and the variance equal one another. $E[Y] = Var(Y) = \mu$ which implies higher mean counts have high variance.

# References

<http://rangerway.com/way/latex-note-and-jekyll/>
<http://www.personal.ceu.hu/tex/cookbook.html>
<http://gohugo.io/tutorials/mathjax/>
<http://docs.mathjax.org/en/latest/tex.html>
