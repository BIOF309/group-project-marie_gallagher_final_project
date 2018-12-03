# Quickly Detecting Anomalies in Web site traffic

---

***Final Project, FAES BIOF 309 Introduction to Python, Fall 2018***

**Marie Gallagher, mgallagher@mail.nih.gov**

## Overview

The purpose of this project is to provide a faster way to visualize
data than (repeatedly) importing data into Excel and creating a 
chart.  This will save me time!

The most reliable way to see this working is to download or clone the
[BIF309/group-project-marie_gallagher_final_project GitHub repository](https://github.com/BIOF309/group-project-marie_gallagher_final_project) 
and open 
[./notebooks/01_plot_unique_ips.ipynb](./notebooks/01_plot_unique_ips.ipynb) 
(still under development) in Jupyter Notebook or Jupyter Lab.

*How do you make Colaboratory find the data files???* 

I don't think this is easy to do. You would have to host the files and pass each url to `read_csv()` or include the files in google drive in connection with your notebook.  

Google Colaboratory: [http://colab.research.google.com/github/BIOF309/group-project-marie_gallagher_final_project/blob/master](http://colab.research.google.com/github/BIOF309/group-project-marie_gallagher_final_project/blob/master)

*How do you make Binder import pandas???* 

This is easy. Just include pandas in your `requirements.txt` file. I will add it for you.

Binder: [https://mybinder.org/v2/gh/BIOF309/group-project-marie_gallagher_final_project/master](https://mybinder.org/v2/gh/BIOF309/group-project-marie_gallagher_final_project/master)

Notebook specific links:
- Google Colab [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BIOF309/group-project-marie_gallagher_final_project/blob/master/notebooks/01_plot_unique_ips.ipynb)
- Jupyter Lab [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/BIOF309/group-project-marie_gallagher_final_project/master?urlpath=lab/tree/notebooks/01_plot_unique_ips.ipynb)
- Jupyter Notebook [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/BIOF309/group-project-marie_gallagher_final_project/master?filepath=notebooks/01_plot_unique_ips.ipynb)

## Gory details

Development environment: Anaconda Distribution, JetBrains PyCharm and Jupyter Notebooks on Windows 10

Project Organization
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── THE END
