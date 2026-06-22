# Unsupervised Traffic Flow Clustering (Accident Analysis)

This repository contains an unsupervised learning project focused on identifying traffic accident patterns using clustering techniques.

The analysis is implemented in a Jupyter Notebook and applies K-Means clustering, PCA for dimensionality reduction, and exploratory visualisation to understand underlying structures in the data.

## Files in This Repository

- **unsupervised-traffic-flow-clustering-accident-prediction.ipynb**  
  Jupyter Notebook containing the full unsupervised learning workflow, including:
  - data preprocessing and scaling  
  - K-Means clustering  
  - elbow method for optimal cluster selection  
  - PCA-based visualisation  
  - cluster interpretation by day of week  

- **filtered_data.zip**  
  ZIP archive containing the dataset required to run the notebook.

## How to Run the Notebook

1. Download or clone this repository.
2. Extract **filtered_data.zip**.
3. Inside the ZIP, locate the CSV dataset.
4. Place the extracted CSV file in the same directory as `unsupervised-traffic-flow-clustering-accident-prediction.ipynb`.
5. Open the notebook in Jupyter Notebook or JupyterLab.
6. Run the cells from top to bottom.

> The notebook will not run correctly unless the CSV file is extracted and placed in the same folder as the notebook.

## Requirements

This notebook was tested using:

- Python 3.11.9
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

> Running the notebook on newer Python versions (e.g. 3.14) may cause dependency issues with certain libraries.

## Project Context

This notebook represents an unsupervised learning component of a larger group project.  
For this repository, it is presented as a standalone analysis focusing on clustering and pattern identification.

## Output

The notebook produces:
- cluster assignments for accident records  
- elbow method plots  
- PCA visualisations  
- cluster-level summaries and interpretations  

These outputs are intended for exploratory analysis and insight generation.
