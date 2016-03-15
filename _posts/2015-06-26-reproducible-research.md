---
title: "Research reproducibility"
layout: post
date:   2015-06-26 13:06:04
directory: research
---

{% newthought 'Computational methods' %} should be among the most reproducible methods in the life sciences; the environment and protocol for a computational method can be specified to a much greater degree, and with much greater precision, than a typical laboratory method.<!--more-->  Unfortunately, many published computational results remain hard to reproduce, and methods are often not specified in sufficient detail to replicate or re-implement.  I have proposed  techniques for building *reference environments*{% sidenote 1  'Little bootstrapped open-source virtual environments for reproducing a single computational result.' %} enabling researchers to reproduce computational results precisely, with minimal effort, and implemented these for a range of results in computational biology{% sidenote 2  'Lots of published [examples here](http://uomsystemsbiology.github.io/research/reference-environments/#examples-of-reference-environments)' %}.  

[My current research in this theme](http://uomsystemsbiology.github.io/research/reference-environments) extends this approach and set of tools to work across all major languages (R/Python/Java/MATLAB/Fortran/C) and platforms in systems and computational biology.  The method produces reference environments across three different reproducibility platforms: as a virtual machine, as a container, and as a cloud environment, all from a single set of configuration scripts.  Reference environments integrate readily with other reproducible research technologies, and can contain any type of language or computation.  

{% newthought 'The reference environment approach' %} {% marginnote "How do reference environments relate to other types of 'reproducible research'?  [I discuss that here](http://uomsystemsbiology.github.io/research/reference-environments/#how-reference-environments-relate-to-other-reproducible-research-tools)" %} explicitly separates the core scientific findings of a piece of computational research from the software implementation in which they are embedded, and allows readers and reviewers to choose the most appropriate implementation type for their situation.  Reference environments {% marginnote "\"But why not just use <currently popular reproducibility tool/website>?\"  [I discuss that here](http://dx.doi.org/10.1093/bib/bbu043)" %} also have many applications in more general reproducibility; providing standard environments for testing or benchmarking, or in teaching to accelerate students' hands-on experience with tools and languages.   

### Featured publications

**Hurley, D. G.**, Budden, D. M., & Crampin, E. J. (2014). [Virtual Reference Environments: a simple way to make research reproducible](http://bib.oxfordjournals.org/content/early/2014/12/06/bib.bbu043.abstract). *Briefings in Bioinformatics*, bbu043. doi:10.1093/bib/bbu043

