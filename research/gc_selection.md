---
layout: page
title: Bayesian Modelling of Globular Cluster Systems in Wide-Field Imaging
permalink: /research/gc_selection
published: true
main_nav: false
---
<img src="{{ site.baseurl }}/assets/n5907_image.png" style="width: 70%" title="Subaru/SuprimeCam image of NGC 5907. Every
faint, small source is a potential globular cluster, but also a potential contaminant.">


Basic questions of interest about globular cluster systems include how many globular clusters there are, what are the relative fractions
of different types of globular clusters, and how are they distributed around their host galaxies. Ideally, these questions
could be answered trivially by taking an image of the galaxy, selecting those sources which are globular clusters,
and performing our measurements on that subsample. Unfortunately, typical datasets are much messier than this.
In a globular cluster dataset, we are dealing with a sample that is both **incomplete** (globular clusters may exist below the detection
threshold of our imaging data) and **contaminated** (globular clusters in images are easily confused both with foreground
stars in the Milky Way and distant galaxies far behind the galaxy of interest). Current approaches to globular cluster selection have use somewhat
ad-hoc selection rules to attempt a selection with minimal contamination, but unquantified
selection errors muddle inferences from such a method.

I am developing a fully Bayesian framework for modelling the globular cluster populations of nearby galaxies.
My method simultaneously models all sources in the image as a mixture model composed
of both contaminants and genuine globular clusters, each with their own distributions. I model
the contaminants using kernel density estimates trained on control images taken far
away from galaxies, then use parametric models for the distribution of globular clusters mixed in with these contaminants.
This allows me to easily fold
in all measured data from sources in our imaging; while most methods just select globular clusters based
on their measured colors, I can easily fold in information about their spatial and luminosity
distributions into the selection methodology.

The advantages of these methods are two-fold: first, I get a better sample of likely globular clusters.
Rather than simply selecting a sample using ad-hoc criteria, I calculate a probability
for every source in the image of how likely it is to be a globular cluster. Any studies requiring a
clean sample of clusters will have a clear quantification of their contamination, and follow-up
spectroscopic studies with different telescopes will be able to better optimize their target selection.
Second, the parameters of the distributions used to model the globular clusters are themselves very interesting
astrophysical quantities. Bayesian methods give us full PDFs for quantities like the total
number of globular clusters or the relative fractions of red and blue globular clusters, completely folding in any
uncertainties introduced by the selection process. The estimates of such parameters with
reliable uncertainties attached will offer a useful discriminant between competing models
of globular cluster formation which currently exist in the literature.

<img src="{{ site.baseurl }}/assets/gc_selection.png" style="width: 200%" title="Selection of globular cluster Candidates from Contaminants">


