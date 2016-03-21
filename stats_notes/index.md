---
layout: page
title: Useful Stats Refs
permalink: /stats_notes/
published: true
main_nav: true
---
I've remarked to a few people that I have a folder containing something along the lines of "useful papers relating to statistics that I wish someone had sent me years ago," and some people have expressed interest in seeing this. I thought I'd compile them here in case anyone finds them a useful reference. I most certainly do not claim this to be any sort of exhaustive compilation, and there's also probably a lot of overlap between sources, so reader beware. However, there is a lot here that isn't really covered in astrophysics education but really should be in any data-driven astronomer's toolbox. 

I'll try to keep this updated as I find interesting references. 

##Basic Reading and Tutorials

[Data Analysis Recipes: Fitting a Model to Data. Hogg, Bovy, & Lang 2010.](http://arxiv.org/abs/1008.4686) What it says on the tin, how to fit a model to data correctly. A great tutorial, I found this informative and easy to follow. I think starting here would be useful for someone who hasn't had much formal statistics, in particular formal Bayesian statistics. Even includes things like practice exercises at the end of sections. Required reading, in my opinion.

[The Do's and Dont's of Reduced Chi Squared. Andrae, Schulze-Hartung, & Melchior 2010.](http://arxiv.org/abs/1012.3754)
A quick description of reduced $$\chi^2$$ fitting, which is ubiquitous in many areas of astronomy. My personal inclination is that
someone starting out should focus first on learning Bayesian methods, but understanding current methods in the field is still useful.

[Error Estimation in Astronomy: A Guide. Andrae 2010](http://arxiv.org/abs/1009.2755). A practical guide to calculating uncertainties. Echoing my previous
statement, I think in general hierarchical Bayesian approaches will make more sense in cases where one is starting analysis from scratch, but
error bars are still a ubiquitous feature of astronomy. 

[Some Aspects of Measurement Error in Linear Regression of Astronomical Data. Kelly 2007.](http://arxiv.org/abs/0705.2774) A nice Bayesian approach to fitting data with uncertainties on all quantities, non-detections, and selection effects. Includes an explicit algorithm, although probably a somewhat outdated one given current approaches to Bayesian analysis.

[Frequentism and Bayesianism, a Python-based primer. VanderPlas 2014](http://arxiv.org/abs/1411.5018). A nice comparison of Frequentist and Bayesian approaches to problems with coding examples. I would probably check out [Jake VanderPlas' blog series first](http://jakevdp.github.io/blog/2014/03/11/frequentism-and-bayesianism-a-practical-intro/),
it's basically the same material but featuring more explicit coding examples and interesting discussions in the comments. 

[emcee: The MCMC Hammer, Foreman-Mackey et al. 2012](http://arxiv.org/abs/1202.3665). A nice read on MCMC algorithms, including (arguably) the most
commonly used one in astronomy, emcee. It's one I've started using extremely frequently in my own research. See also [Daniel Foreman-Mackey's website for the emcee package.](http://dan.iel.fm/emcee/current/)

##Statistical Discussions

[American Statistical Association Statement on p-values, 2016](http://amstat.tandfonline.com/doi/abs/10.1080/00031305.2016.1154108). This statement represents the first time the ASA has ever released a statement regarding a specific analysis practice. The actual statement on p-values is required reading, but much of the meat of the statement comes from the supplementary papers written by the majority of the individual authors. 

[Bayesian Model Selection in Social Research, Raftery 1995](http://www.stat.washington.edu/raftery/Research/PDF/socmeth1995.pdf). Somewhat old, but still a good discussion of model selection in a Bayesian context. 

[Ch. 26: "How do we choose our default methods?" Andrew Gelman](http://www.stat.columbia.edu/~gelman/research/published/copss.pdf). Book chapter (I'm not familiar with the full source) giving some interesting discussion on the selection of default statistical methods in various contexts. 

##Examples of Applications in Astronomy

For those who like seeing practical examples:

[Dan Weisz's Bayesian approach to evaluating stellar mass functions. Weisz+ 2013.](http://arxiv.org/abs/1211.6105) I found this a useful reference for consideration of incomplete data (in the astronomical context) in Bayesian analysis. 







