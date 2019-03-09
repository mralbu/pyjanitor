---
title: 'pyjanitor: Clean APIs for cleaning data'
tags:
  - Python
  - data science
  - data engineering
  - application programming interfaces
authors:
  - name: Eli S. Goldberg
    orcid: 0000-0000-0000-0000
    affiliation: 1
  - name: Eric J. Ma
    orcid: 0000-0003-0872-7098
    affiliation: 1
  - name: Zachary Barry
    orcid: 0000-0000-0000-0000
    affiliation: 1
  - name: Sam Zuckerman
    orcid: 0000-0000-0000-0000
    affiliation: 2
  - name: Zachary Sailer
    orcid: 0000-0000-0000-0000
    affiliation: 3
affiliations:
 - name: Novartis Institutes for Biomedical Resaerch
   index: 1
 - name: Institution 2
   index: 2
 - name: Project Jupyter
   index: 3
date: 9 March 2019
bibliography: references.bib
---

# Summary

The `pandas` library has become the de facto library for data wrangling in the Python programming language. However, inconsistencies in the `pandas` application programming interface (API), while idiomatic due to historical use, prevent use of expressive, fluent programming idioms that enable self-documenting `pandas` code. Here, we introduce `pyjanitor`, an open source Python package that provides a fluent API layer on top of the pandas API, enabling data scientists and engineers to write readable, self-documenting and maintainable code.

`pyjanitor` started originally as a Python port of the R package. However, as the project evolved, we recognized the power of a fluent API through method chaining when doing data preparation work. As such, `pyjanitor` users can design easily

``Gala`` is an Astropy-affiliated Python package for galactic dynamics. Python
enables wrapping low-level languages (e.g., C) for speed without losing
flexibility or ease-of-use in the user-interface. The API for ``Gala`` was
designed to provide a class-based and user-friendly interface to fast (C or
Cython-optimized) implementations of common operations such as gravitational
potential and force evaluation, orbit integration, dynamical transformations,
and chaos indicators for nonlinear dynamics. ``Gala`` also relies heavily on and
interfaces well with the implementations of physical units and astronomical
coordinate systems in the ``Astropy`` package [@astropy] (``astropy.units`` and
``astropy.coordinates``).

``Gala`` was designed to be used by both astronomical researchers and by
students in courses on gravitational dynamics or astronomy. It has already been
used in a number of scientific publications [@Pearson:2017] and has also been
used in graduate courses on Galactic dynamics to, e.g., provide interactive
visualizations of textbook material [@Binney:2008]. The combination of speed,
design, and support for Astropy functionality in ``Gala`` will enable exciting
scientific explorations of forthcoming data releases from the *Gaia* mission
[@gaia] by students and experts alike. The source code for ``Gala`` has been
archived to Zenodo with the linked DOI: [@zenodo]

# Mathematics

Single dollars ($) are required for inline mathematics e.g. $f(x) = e^{\pi/x}$

Double dollars make self-standing equations:

$$\Theta(x) = \left\{\begin{array}{l}
0\textrm{ if } x < 0\cr
1\textrm{ else}
\end{array}\right.$$


# Citations

Citations to entries in paper.bib should be in
[rMarkdown](http://rmarkdown.rstudio.com/authoring_bibliographies_and_citations.html)
format.

# Figures

Figures can be included like this: ![Example figure.](figure.png)

# Acknowledgements

We acknowledge contributions from Brigitta Sipocz, Syrtis Major, and Semyeong
Oh, and support from Kathryn Johnston during the genesis of this project.

# References