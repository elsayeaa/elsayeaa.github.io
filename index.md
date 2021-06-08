---
layout: default
title: Summer 2021 DREU Project Site
---

* TOC
{:toc}

## About Me
Hello everyone! I am Ahmed Elsayed. I am an international student from Egypt. I am a rising junior at Whitman College. My majors are Computer Science and Mathematics in addition to a Creative Writing minor. I plan to graduate by May 2023. After graduation, I plan to continue my studies at a graduate school program. I have not yet decided on a research area: I am still enjoying the pursuit of exploration. However, I know that I want to channel my education into accessibility and fairness in the tech world. In our current times, I believe that Technology immensly contributes to the issues of equity, accessibility, and equality, and I am confident that my research interests will be around this field.  
## About My Mentor
I am working with Prof. Sanmi Koyejo. Prof. Koyejo is an Assistant Professor at Department of Computer Science at the University of Illinois at Urbana-Champaign. His main research interests lies in developing the principles and practice of trustworthy in machine learning. You can find more about Prof. Sanmi's research area and interets through this [link](https://sanmi.cs.illinois.edu/bio.html) 
In addition, I am working with Olawale Salaudeen, a 2nd-year Ph.D. student in the department of computer science at the University of Illinois at Urbana-Champaign. You can find more about Wale through this [link](https://olawalesalaudeen.com/) 
## About My Project

### Description
Most machine learning algorithms implicitly assume that the data distribution available at train time is identical as the data distribution at test time. However, in practice, this assumption is often violated. In many practical applications, the context of interest is non-stationary, either due to natural dynamics or unobserved exogenous influences. When this violation occurs, the empirical risk achieved by a learned model on the train data distribution can no longer be expected on the test data distribution, i.e., the model does not generalize. This limitation motivates the causal transfer learning literature, which aims to exploit the distribution invariance of the data generating process of the expected data distributions. In other words, causal transfer learning proposes only using causal parents of an outcome variable to predict said outcome variable, since this relationship is not sensitive to common distribution dynamics (covariate and label shifts). However, there exists applications where this paradigm is costly. Consider medical diagnostics where symptoms which are effects, not causes, are the primary predictors of a disease or condition. This motivates our work on how to wisely use non-causal information during zero-shot transfer, while maintaining close to the same generalization of causal transfer learning.

### Goals
1. Develop a zero-shot transfer learning algorithm that uses anticausal information,
2. develop an algorithm to identify conditions when a model uses anticausal information transfers as well as or better than strictly using causal information, and 
3. empirically compare this method to causal transfer and other zero-shot transfer algorithms on settings with known/partially known causal graphs and unknown causal graphs.


### Progress
You can follow my blog posts at the end of this page to learn more about my weekly little accomplishments and frustrations. 



[My Final Report](files/finalreport.pdf)

## My Blog

[My Blog](blog.html)
