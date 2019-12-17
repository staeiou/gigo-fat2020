# Data and analysis code for "Garbage In, Garbage Out?" FAT* 2020 paper

This repository contains data and analysis code for [the paper](gigo_fat2020.pdf) "Garbage In, Garbage Out? Do Machine Learning Application Papers in Social Computing Report Where Human-Labeled Training Data Comes From?", which is to appear in the Proceedings of ACM FAT* 2020. 

The Jupyter notebook `data_analysis_viz.ipynb` loads `gigo_noscores_dataset_anon.csv`, which has the final labels for each of the papers, including metadata about where they were published. Annotation information scores are calculated, and results are calculated and plotted. The notebook then exports `gigo_final_dataset_anon.csv`, which contains the same columns as `gigo_noscores_dataset_anon.csv`, but also includes information scores for each paper and some imputed metadata categories about publication type. This notebook can be run on mybinder.org with the button below:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/staeiou/gigo-fat2020/master)

We have chosen to de-identify the papers presented in this publicly-released dataset, and so papers are only referred to with a unique id. If you are interested in obtaining the identifying information for research purposes, please contact Stuart Geiger. 
