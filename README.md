# Exploratory Data Analysis - King County Housing Data

This repository contains a EDA on the King County Housing Data Set.
## Introduction

The purpose of this EDA is to find insights into the King County House Market, by analyzing the data in regards to three hypotheses, which we either confirm or discard during this EDA. The insights gained throughout this process will be used at a later point to get insight into a specific stakeholder situation and make fitting and relevant recommendations in regard to their situation.


## Repository Content

As this repository come into existence due to an assignment of the Data Science Bootcamp from NeueFische, it also contains the following documents:

1. [Assignment](assignment.md)
2. [Workflow](workflow.md)
3. [column_names](column_names.md)

In addition to the jupyter notebook containing the full EDA incl. code, a presentation which highlights the hypotheses analysis and stakeholder recommendation is also included within this repository.

4. [basic EDA](EDA_basic.ipynb)
5. [Presentation](EDA_presentation.pdf)

Additionally, an advanced EDA approach has been incorporated, to see if different insights can be generated.
6. [advanced EDA](EDA_advanced.ipynb)

## Data

The data set used for this EDA was the official King County housing data set for the period 9.9.2014 to 01.10.2015, which can also be found on [Kaggle](https://www.kaggle.com/harlfoxem/housesalesprediction?select=kc_house_data.csv).


## Installation and Setup

If you want to replicate this notebook, you can use the following lines in bash to create your virtual environment.

```bash
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

If you are interested in the packages and libraries used, check out the [requirements](requirements.txt) file.

