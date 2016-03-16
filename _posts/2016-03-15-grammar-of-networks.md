---
title: "A general language for networks"
layout: post
date:   2016-03-15 13:06:04
directory: research
---

{% newthought 'Network models have great potential' %} to uncover complex interactions and pathways not visible by other methods, but network modelling is still an ad hoc activity, with no general theory to relate different approaches, nor principles for determining what a network tells us about the biology that created it.<!--more-->  Progress in data-driven 'network biology' has been hampered by the lack of a general language for integrating different network methods from different domains of knowledge.  

To overcome these obstacles, I am developing a _grammar of network methods_, an empirical grammar of data manipulation extended into graph theory.   The grammar is influenced by the statistical graphics work of Wilkinson{% sidenote 1  'See [The Grammar of Graphics](http://dx.doi.org/10.1007/0-387-28695-0)' %} and Wickham{% sidenote 2  'See [A Layered Grammar of Graphics](http://dx.doi.org/10.1198/jcgs.2009.07098) and [Tidy Data](http://dx.doi.org/10.18637/jss.v059.i10)'  %}, and allows us to describe the structure of different network methods (like the syntax in a human grammar) and relate them directly back to the biological data used to create the network, in order to uncover biological meaning (semantics).   Using simple graph elements and a declarative syntax, the grammar is able to describe existing network modelling in biology using a common set of concepts, focused particularly on network inference from genomic, proteomic and metabolomic data.   

{% newthought 'The grammar of network methods' %} is a new research direction stemming from work started during my PhD, where I integrated diverse mathematical and statistical methods of reverse-engineering transcriptomic networks{% sidenote 3  '[The initial computational framework](http://dx.doi.org/10.1093/nar/gkr902) was written in MATLAB' %}, and applied these methods to generate and validate experimental hypotheses in transformed cell lines{% sidenote 4  'Applications in [melanoma prognosis](http://dx.doi.org/10.1371/journal.pone.0034247) and [endothelial cell biology](http://dx.doi.org/10.1093/nar/gkr902)' %}.  The grammar develops this work by describing these existing analysis methods using a common language, and showing clearly their similarities and differences.  

Specifically, my current research implements the grammar in two programming languages common in systems and computational biology (R and Python), and uses it to answer two major open questions in computational biology: the unification of 'knowledge-based' and 'data-driven' network methods, and the effect of ensemble network methods (the 'wisdom of crowds' effect).  

{% newthought 'Completing this work' %} will transform network modelling in biology, from an ad hoc activity where different methods exist in isolation from one another, into a principled, evidence-driven activity with heuristics for which methods are fruitful on which data for which outcomes.     

### Featured publications

**Hurley, D. G.**, Cursons, J., Wang, Y. K., Budden, D. M., Print, C. G., & Crampin, E. J. (2014). [NAIL, a software toolset for inferring, analyzing and visualizing regulatory networks](http://bioinformatics.oxfordjournals.org/content/31/2/277.abstract). *Bioinformatics*, 31(2), 277–278. doi:10.1093/bioinformatics/btu612

**Hurley, D.**, Araki, H., Tamada, Y., Dunmore, B., Sanders, D., Humphreys, S., … Print, C. G. (2012). [Gene network inference and visualization tools for biologists: application to new human transcriptome datasets](http://nar.oxfordjournals.org/lookup/doi/10.1093/nar/gkr902). *Nucleic Acids Research*, 40(6), 2377–2398. doi:10.1093/nar/gkr902

