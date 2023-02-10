# FDA Drug adverse event reports

Multiple Sclerosis (MS) is a chronic disease that affects the central nervous system. Despite various treatments and drugs available to manage MS, the adverse effects of these drugs still pose a major challenge for patients. In this data science project, we aim to analyze the serious adverse effects of the top 5 Multiple Sclerosis drugs reported in the United States among patients aged 55 and above. Our objective is to identify which factors contribute to a patient experiencing serious adverse effects.

For this exercise we are going to code a prediction model for the serious adverse reactions of a set of drugs for patients with more than 55 years old and analyze the results of the model. We are focusing only on the data from one year (from 2021-11-04 ot 2022-11-04).

## Requirements

There is a `requirements.txt` available generated using `pipreqs` to install the required libraries to run the exercise without any problem.

## Notebooks

There are two notebooks in this project:

- *1 - Data Gathering*: Run it to generate the subsample of interest in this exercise using the FDA API. You may skip running this notebook and use the subsample in this repository.
- *2 - Analysis using ML*: The notebook used to analyze the dataset.
