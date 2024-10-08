# Comparing ML model performance in predicting the absorption profile properties
Built machine learning models to predict absorption profile properties such as human plasma protein binding rate (PPBR), bioavailability (BIO) and parallel artificial membrane permeability assay (PAMPA) and compared their performance.

## Description
This project created multuiple models based on ADME data, focusing on Absoroption, utilizing the tdc.single_pred library to import and define SMILES strings and labels for two papers in particular linked below. We generated molecular descriptors from these strings to create features for SVM and Random Forest models. While training we used gridsearch to find the ideal parameters. Feature importance was ranked afterwards for the PPBR and BIO paper. Graph embeddings were created using torch_geometric and a Graph Neural Network (GNN) was trained on the datasets from both papers. Finally we compared performance across models and extend the findings of the following original papers:
- [Journal of Pharmaceutical Sciences](https://journals.sagepub.com/doi/full/10.1177/24725552211017520)
- [Science Direct](https://www.sciencedirect.com/science/article/abs/pii/S0731708508001738?via%3Dihub)

## Installation
We used pip to install all relevant packages. If you are not using Google Colab please install [pip](https://pip.pypa.io/en/stable/installation/).

## Usage
1. Open them in Google Colab or Jupyter Notebook.
1. Each notebook contains the code to install all packages and requirements and contains sections clearly titled with the aspect thats being covered. Additionally each notebook itself contains all the relevant code for that section though there might be some overlap between notebooks due to different authors creating their respective models. Please run all the cells in the notebook to observe.

## Authors
- Faisal Baig
- Suraksha Vinod
- Tamarin Tandra
- Boyu Cheng

\* All authors contributed equally to the project.
