# Quickly Detecting Anomalies in Web site traffic

---

***Final Project, FAES BIOF 309 Introduction to Python, Fall 2018***

**Marie Gallagher, mgallagher@mail.nih.gov**

## Overview

The purpose of this project is to provide a faster way to visualize
data than (repeatedly) importing data into Excel and creating a 
chart.  This will save me time!

The most reliable way to see this working is to download or clone the
[BIOF309/group-project-marie_gallagher_final_project GitHub repository](https://github.com/BIOF309/group-project-marie_gallagher_final_project) 
and open 
[./notebooks/01_plot_unique_ips.ipynb](./notebooks/01_plot_unique_ips.ipynb) 
in Jupyter Notebook or Jupyter Lab.

Alternate repository: [MarieGallagher/group-project-marie_gallagher_final_project GitHub repository](https://github.com/MarieGallagher/group-project-marie_gallagher_final_project) 

*How do you make Colaboratory find the data files???* 

I don't think this is easy to do. You would have to host the files and pass each url to `read_csv()` or include the files in google drive in connection with your notebook.  (Thanks, Martin!  --Marie)

*How do you make Binder import pandas???* 

This is easy. Just include pandas in your `requirements.txt` file. I will add it for you. (Thanks again, Martin!  --Marie)

Notebook specific links in BIOF309/group-project-marie_gallagher_final_project:
- Google Colab [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BIOF309/group-project-marie_gallagher_final_project/blob/master/notebooks/01_plot_unique_ips.ipynb)
- Jupyter Lab [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/BIOF309/group-project-marie_gallagher_final_project/master?urlpath=lab/tree/notebooks/01_plot_unique_ips.ipynb)
- Jupyter Notebook [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/BIOF309/group-project-marie_gallagher_final_project/master?filepath=notebooks/01_plot_unique_ips.ipynb)

Notebook specific links in alternate MarieGallagher/group-project-marie_gallagher_final_project:
- Google Colab [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MarieGallagher/group-project-marie_gallagher_final_project/blob/master/notebooks/01_plot_unique_ips.ipynb)
- Jupyter Lab [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MarieGallagher/group-project-marie_gallagher_final_project/master?urlpath=lab/tree/notebooks/01_plot_unique_ips.ipynb)
- Jupyter Notebook [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MarieGallagher/group-project-marie_gallagher_final_project/master?filepath=notebooks/01_plot_unique_ips.ipynb)

## Gory details

Development environment: Anaconda Distribution, JetBrains PyCharm and Jupyter Lab/Notebooks on Windows 10

Project Organization
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    │
    ├── docs               <- To do: Add instructions for how to run the notebook.
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │   │                     the creator's initials, and a short `-` delimited description, e.g.
    │   │                     `1.0-jqp-initial-data-exploration`.
    │   └── data
    │       └── raw        <- The original, immutable data dump.
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment
    │
    └── THE END
