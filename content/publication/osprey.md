+++
abstract = "Osprey: Hyperparameter Optimization for Machine Learning"
abstract_short = ""
authors = ["Robert T. McGibbon", "Carlos X. Hernández","Matthew P. Harrigan", "Steven Kearnes", "Mohammad M. Sultan",
"Stanislaw Jastrzebski","Brooke E. Husic", "Vijay S. Pande"]
date = "2016-09-07"
image = ""
image_preview = ""
math = true
publication = "Journal of Open Source Software"
publication_short = ""
selected = false
title = "Osprey: Hyperparameter Optimization for Machine Learning"
url_code = ""
url_dataset = ""
url_pdf = "https://github.com/openjournals/joss-papers/blob/master/joss.00034/10.21105.joss.00034.pdf"
url_project = ""
url_slides = ""
url_video = ""

+++

Osprey is a tool for hyperparameter optimization of machine learning algorithms in Python. Hyperparameter optimization
can often be an onerous process for researchers, due to time-consuming experimental replicates, non-convex objective
 functions, and constant tension between exploration of global parameter space and local optimization (Jones, Schonlau,
  and Welch 1998). We've designed Osprey to provide scientists with a practical, easy-to-use way of finding optimal
  model parameters. The software works seamlessly with scikit-learn estimators (Pedregosa et al. 2011) and supports
  many different search strategies for choosing the next set of parameters with which to evaluate a given model,
  including gaussian processes (GPy 2012), tree-structured Parzen estimators (Yamins, Tax, and Bergstra 2013),
  as well as random and grid search. As hyperparameter optimization is an embarrassingly parallel problem, Osprey
  can easily scale to hundreds of concurrent processes by executing a simple command-line program multiple times.
  This makes it easy to exploit large resources available in high-performance computing environments.

Osprey is actively maintained by researchers at Stanford University and other institutions around the world. While
originally developed to analyze computational protein dynamics (McGibbon, Harrigan, et al. 2016), it is applicable to
any scikit-learn-compatible pipeline. The source code for Osprey is hosted on GitHub and has been archived to Zenodo
(McGibbon, Hernández, et al. 2016). Full documentation can be found at http://msmbuilder.org/osprey.

