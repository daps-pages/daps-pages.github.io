---
title: LMR Turbo
subtitle: A lightweight implementation of the LMR framework
tags: [LMR, LMRt, DA]
---

A lightweight, packaged version of the [Last Millennium Reanalysia (LMR)](https://github.com/modons/LMR) paleoclimate data assimilation (PDA) framework,
inspired by LMR_lite.py originated by Professor Hakim (Univ. of Washington).
Ultimately, it aims to provide following features:

+ Greater flexibility
    + Easy installation
    + Easy importing and usage in Jupyter notebooks (or scripts)
    + No assumption of a fixed folder structure; just feed the correct files to functions
    + Easy setup for different priors, proxies, and Proxy System Models (PSMs) included in [PRYSM API](https://github.com/fzhu2e/prysm-api)
+ Faster speed
    + Easy parallel computing with multiprocessing and other techniques


### Applications

+ Reconstruction of the spatial-temporal field (tas, pr, z500, etc.) over Common Era
+ Post processing of the renalaysis result
+ Visualization of the renalaysis result

### Usage examples
+ [A quickstart](https://nbviewer.jupyter.org/github/fzhu2e/LMRt/blob/master/notebooks/01.lmrt_quickstart.ipynb)

### Publications
+ Feng Zhu, Julien Emile-Geay, Greg Hakim, Robert Tardif, & Andre Perkins.  (2019, May 22). LMR Turbo (LMRt): a lightweight implementation of the LMR framework (Version 0.5.1). Zenodo. <http://doi.org/10.5281/zenodo.3167723>

### Useful links

+ Github repo: <https://github.com/fzhu2e/LMRt>


