```md
# University Capstone Project

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Experimental-orange)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-red)
![Status](https://img.shields.io/badge/Status-Capstone%20Project-lightgrey)

## Overview

This repository contains the prototype/proof-of-concept implementation of **Carbon Emissions Tracker** as a university capstone project focused on **data preprocessing, machine learning model training and evaluation, and a lightweight web application** for demonstration purposes.
The project aims to employ machine learning models to predict future carbon emissions and LLMs to generate actionable insights that can be used to reduce emissions **while** ensuring operational efficacy.

The project follows a standard applied machine learning workflow:
1. Raw emissions data preprocessing 
2. Model training and evaluation  
3. Integration and demonstration via a Streamlit web app  

The goal is educational and exploratory rather than production deployment.

---

## What the Project Does

- Processes raw datasets into model-ready formats
- Trains and evaluates machine learning models
- Demonstrates the full pipeline through a Streamlit-based web application

### Project Structure

```

.
├── Dataset stuff.ipynb     # Raw data preprocessing and feature engineering
├── ML Stuff.ipynb          # Model training, evaluation, and experimentation
├── web_app/                # Streamlit web application
└── README.md

````

### Components

#### Dataset Stuff
- Handles cleaning, transformation, and preprocessing of raw data
- Produces structured datasets suitable for machine learning models

#### ML Stuff
- Focuses on training and evaluating machine learning models
- Includes experimentation with model choices, parameters, and metrics

#### Web App
- Built using Streamlit
- Provides a simple interface to visualize results and interact with the trained models
- Intended for demonstration, not large-scale deployment

---

## Why This Project Is Useful

- Demonstrates an end-to-end machine learning pipeline
- Separates data preparation from model logic
- Shows how experimental notebooks can be integrated into a usable application
- Suitable as a learning reference or portfolio project

---

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab
- pip or conda

### Installation

Clone the repository:
```bash
git clone https://github.com/entilious/University-Capstone-Project.git
cd University-Capstone-Project
````

Install required dependencies (example):

```bash
pip install numpy pandas scikit-learn streamlit matplotlib
```

> Dependency requirements may vary depending on the models and preprocessing steps used in the notebooks.

---

## Usage

### Data Preprocessing

Run the preprocessing notebook:

```text
Dataset stuff.ipynb
```

This prepares raw data for model training.

### Model Training and Evaluation

Run the training and evaluation notebook:

```text
ML Stuff.ipynb
```

This notebook trains models and evaluates their performance.

### Running the Web Application

From the project root:

```bash
cd web_app
streamlit run app.py
```

The Streamlit app provides an interactive interface to explore the results.
---

## Notes

* This project is experimental and not production-ready
* Models and preprocessing pipelines are exploratory
* The web app is intended for demonstration purposes only

```
```
