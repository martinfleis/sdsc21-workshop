# Capturing the Structure of Cities with Data Science workshop
SDSC 2021 Workshop

## Run online

Open in an interactive in-browser environment:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/martinfleis/sdsc21-workshop/HEAD?labpath=demo-notebook.ipynb)

## Run locally

If you want to run the notebook locally, it is recommended to create a new `conda` environment based on the `environment.yml` file.

```
conda env create -f environment.yml
```

Alternatively, ensure that all required dependencies are available in your environment in their latest versions (as of October 24, 2021).

```
- momepy
- pygeos
- osmnx
- clustergram
- bokeh
- scikit-learn
- geopy
- ipywidgets
```

## Annotation

Martin will walk you through the fundamentals of analysis of the structure of cities. You will learn what can be measured, how to do that in Python, and how to use those numbers to capture the patterns that make up cities. Using a real-life example, you will learn every step of the method, from data retrieval to detection of individual patterns.