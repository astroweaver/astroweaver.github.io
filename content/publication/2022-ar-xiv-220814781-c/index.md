---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Machine Learning Approach to Predict Missing Flux Densities in Multi-band
  Galaxy Surveys
subtitle: ''
summary: ''
authors:
- Nima Chartab
- Bahram Mobasher
- Asantha Cooray
- Shoubaneh Hemmati
- Zahra Sattari
- Henry C. Ferguson
- David B. Sanders
- John R. Weaver
- Daniel Stern
- Henry J. McCracken
- Daniel C. Masters
- Sune Toft
- Peter L. Capak
- Iary Davidzon
- Mark Dickinson
- Jason Rhodes
- Andrea Moneti
- Olivier Ilbert
- Lukas Zalesky
- Conor McPartland
- Istvan Szapudi
- Anton M. Koekemoer
- Harry I. Teplitz
- Mauro Giavalisco
tags:
- '"Astrophysics - Astrophysics of Galaxies"'
categories: []
date: '2022-08-01'
lastmod: 2022-10-27T17:09:10-04:00
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
publishDate: '2022-10-27T21:09:24.144003Z'
publication_types:
- '2'
abstract: We present a new method based on information theory to find the optimal
  number of bands required to measure the physical properties of galaxies with a desired
  accuracy. As a proof of concept, using the recently updated COSMOS catalog (COSMOS2020),
  we identify the most relevant wavebands for measuring the physical properties of
  galaxies in a Hawaii Two-0 (H20)- and UVISTA-like survey for a sample of $i<25$
  AB mag galaxies. We find that with available $i$-band fluxes, $r$, $u$, IRAC/$ch2$
  and $z$ bands provide most of the information regarding the redshift with importance
  decreasing from $r$-band to $z$-band. We also find that for the same sample, IRAC/$ch2$,
  $Y$, $r$ and $u$ bands are the most relevant bands in stellar mass measurements
  with decreasing order of importance. Investigating the inter- correlation between
  the bands, we train a model to predict UVISTA observations in near-IR from H20-like
  observations. We find that magnitudes in $YJH$ bands can be simulated/predicted
  with an accuracy of $1σ$ mag scatter $łesssim 0.2$ for galaxies brighter than 24
  AB mag in near-IR bands. One should note that these conclusions depend on the selection
  criteria of the sample. For any new sample of galaxies with a different selection,
  these results should be remeasured. Our results suggest that in the presence of
  a limited number of bands, a machine learning model trained over the population
  of observed galaxies with extensive spectral coverage outperforms template- fitting.
  Such a machine learning model maximally comprises the information acquired over
  available extensive surveys and breaks degeneracies in the parameter space of template-fitting
  inevitable in the presence of a few bands.
publication: '*arXiv e-prints*'
---
