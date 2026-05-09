# Programming and Scripting Project

This repository contains my project for the Programming and Scripting module.

The project investigates Fisher's Iris dataset using Python. The Iris dataset contains measurements of three different Iris flower species. The aim of this project is to load the dataset, summarise it, create visualisations, and explain what the results show.

## Repository Contents

- `analysis.ipynb`  
  The main Jupyter notebook containing the Python code and analysis.

- `data/`  
  Contains the Iris dataset files.

- `output/`  
  Contains the generated text summary file.

- `images/`  
  Contains the saved histogram and scatter plot images.

- `README.md`  
  Explains the project, the dataset, and the analysis.

## Dataset

The Iris dataset is a well-known dataset introduced by Ronald Fisher. It contains 150 rows and 5 columns.

The four measurement columns are:

- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

The final column is:

- Species

There are three Iris species in the dataset:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

Each species has 50 rows, which means the dataset is evenly balanced.

## Project Plan

My project plan was:

1. Create the GitHub repository and organise the folder structure.
2. Add the Iris dataset files.
3. Create a Jupyter notebook called `analysis.ipynb`.
4. Load the dataset using pandas.
5. Check the structure of the dataset.
6. Create a summary text file.
7. Create and save histograms for each measurement.
8. Create and save scatter plots for each pair of measurements.
9. Add extra analysis comparing the average measurements by species.
10. Write up the project clearly in the README.

## Analysis Summary

The dataset loaded correctly and contains 150 rows and 5 columns.

There are no missing values in the dataset. Each of the three species appears 50 times.

The histograms show how the values are spread out for each measurement. The petal measurements seem to split into clearer groups than the sepal measurements.

The scatter plots show that petal length and petal width give the clearest separation between the species. Setosa is especially easy to separate from the other two species.

The average measurement comparison also shows that Setosa has much smaller petal measurements, while Virginica generally has the largest petal measurements.

## How to Run the Notebook

To run this project:

1. Open the repository in VS Code.
2. Open `analysis.ipynb`.
3. Select the correct Python kernel.
4. Run the notebook from top to bottom.

The notebook creates:

- a summary text file in the `text/` folder,
- histogram images in the `images/` folder,
- scatter plot images in the `images/` folder.

## References

- UCI Machine Learning Repository. *Iris Dataset*.  
  https://archive.ics.uci.edu/dataset/53/iris

- Python Software Foundation. *Python Documentation*.  
  https://docs.python.org/3/

- pandas. *pandas Documentation*.  
  https://pandas.pydata.org/docs/

- Matplotlib. *Matplotlib Documentation*.  
  https://matplotlib.org/stable/index.html

- W3Schools. *Python File Handling*.  
  https://www.w3schools.com/python/python_file_handling.asp