---
title: "Reproducible research"
layout: post
date:   2015-06-26 13:06:04
directory: research
---

{% newthought 'Although reproducibility of results' %} is a key part of the scientific method, there have been recent and high-profile examples of these standards not being met effectively. Computational biology researchers face many unique challenges to ensure reproducibility due to complexity of datasets and reliance upon third-party software packages, leading many journals to implement standards addressing the importance of reproducibility. <!--more--> Unfortunately, existing approaches have been limited to a single technology (e.g. Docker for 64-bit Linux) or programming language (e.g. sweave for R, iPython for Python).  

We present an approach that integrates established software engineering tools to produce complete reference computation environments for computational biology research, containing all software and configuration necessary to reproduce computational results in a language-independent manner. Our approach is the first to use a single recipe (specification) guaranteed to produce the same scientific research environment on a desktop computer or in a cloud computing service, while ensuring minimal additional workload for researchers.   Importantly, results presented with our framework are easily reproduced by reviewers and extended by readers, without the need to install/configure additional software and ensuring robustness against future changes in technology.

{% newthought 'The Tufte Jekyll theme' %} is an attempt to create a website design with the look and feel of Edward Tufte's books and handouts. Tufte’s style is known for its extensive use of sidenotes, tight integration of graphics with text, and well-set typography.<!--more--> The idea for this project is essentially cribbed wholesale from Tufte and R Markdown's Tufte Handout format{% sidenote 1  'See [code.google.com/p/tufte-latex](https://code.google.com/p/tufte-latex') and [rmarkdown.rstudio.com/tufte_handout_format](http://rmarkdown.rstudio.com/tufte_handout_format.html) %} This page is an adaptation of the [Tufte Handout PDF](http://rmarkdown.rstudio.com/examples/tufte-handout.pdf).