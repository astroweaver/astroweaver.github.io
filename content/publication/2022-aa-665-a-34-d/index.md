---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'COSMOS2020: Manifold learning to estimate physical parameters in large galaxy
  surveys'
subtitle: ''
summary: ''
authors:
- I. Davidzon
- K. Jegatheesan
- O. Ilbert
- S. de la Torre
- S.~K. Leslie
- C. Laigle
- S. Hemmati
- D.~C. Masters
- D. Blanquez-Sese
- O.~B. Kauffmann
- G.~E. Magdis
- K. Małek
- H.~J. McCracken
- B. Mobasher
- A. Moneti
- D.~B. Sanders
- M. Shuntov
- S. Toft
- J.~R. Weaver
tags:
- '"galaxies: fundamental parameters"'
- '"galaxies: star formation"'
- '"galaxies: stellar content"'
- '"methods: observational"'
- '"astronomical databases: miscellaneous"'
- '"Astrophysics - Astrophysics of Galaxies"'
- '"Astrophysics - Instrumentation and Methods for Astrophysics"'
categories: []
date: '2022-09-01'
lastmod: 2022-10-27T17:09:09-04:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-10-27T21:09:23.428134Z'
publication_types:
- '2'
abstract: We present a novel method for estimating galaxy physical properties from
  spectral energy distributions (SEDs) as an alternative to template fitting techniques
  and based on self-organizing maps (SOMs) to learn the high-dimensional manifold
  of a photometric galaxy catalog. The method has previously been tested with hydrodynamical
  simulations in Davidzon et al. (2019, MNRAS, 489, 4817), however, here it is applied
  to real data for the first time. It is crucial for its implementation to build the
  SOM with a high-quality panchromatic data set, thus we selected ``COSMOS2020'' galaxy
  catalog for this purpose. After the training and calibration steps with COSMOS2020,
  other galaxies can be processed through SOMs to obtain an estimate of their stellar
  mass and star formation rate (SFR). Both quantities resulted in a good agreement
  with independent measurements derived from more extended photometric baseline and,
  in addition, their combination (i.e., the SFR vs. stellar mass diagram) shows a
  main sequence of star-forming galaxies that is consistent with the findings of previous
  studies. We discuss the advantages of this method compared to traditional SED fitting,
  highlighting the impact of replacing the usual synthetic templates with a collection
  of empirical SEDs built by the SOM in a ``data-driven'' way. Such an approach also
  allows, even for extremely large data sets, for an efficient visual inspection to
  identify photometric errors or peculiar galaxy types. While also considering the
  computational speed of this new estimator, we argue that it will play a valuable
  role in the analysis of oncoming large-area surveys such as Euclid of the Legacy
  Survey of Space and Time at the Vera C. Rubin Telescope.
publication: '*åp*'
doi: 10.1051/0004-6361/202243249
---
