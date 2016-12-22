+++
abstract  = "Understanding Protein Dynamics with L1-Regularized Reversible Hidden Markov Models."
abstract_short = "Understanding Protein Dynamics with L1-Regularized Reversible Hidden Markov Models."
authors = ["Robert T. McGibbon, Bharath Ramsundar, Mohammad M. Sultan, Gert Kiss, Vijay S. Pande"]
date = "2014-06-01"
image = ""
image_preview = ""
math = true
publication = "Proceedings of the 31st International Conference on Machine Learning, Beijing, China, 2014"
publication_short = ""
selected = false
title = "Understanding Protein Dynamics with L1-Regularized Reversible Hidden Markov Models"
url_code = ""
url_dataset = ""
url_pdf = "https://arxiv.org/pdf/1405.1444v1"
url_project = ""
url_slides = ""
url_video = ""

+++

We present a machine learning framework for modeling protein dynamics. Our approach uses L1-regularized, reversible
hidden Markov models to understand large protein datasets generated via molecular dynamics simulations. Our model is
motivated by three design principles: (1) the requirement of massive scalability; (2) the need to adhere to relevant physical law; and (3) the necessity of providing accessible interpretations, critical
for both cellular biology and rational drug design. We present an EM algorithm for learning and introduce a model
selection criteria based on the physical notion of convergence in relaxation timescales. We contrast our model with
standard methods in biophysics and demonstrate improved robustness. We implement our algorithm on GPUs and apply
the method to two large protein simulation datasets generated respectively on the NCSA Bluewaters supercomputer
and the Folding@Home distributed computing network. Our analysis identifies the conformational dynamics of the
ubiquitin protein critical to cellular signaling, and elucidates the stepwise activation mechanism of the c-Src
kinase protein.