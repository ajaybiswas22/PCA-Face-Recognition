# PCA-Face-Recognition
Practical Implementation of Principle Component Analysis to identify faces.

## CONTENTS OF THIS FILE

* Description
* Requirements
* Installation
* Directory Structure
* Usage
* Credits

### Description 

To recognize human faces, one needs to extract the relevant information in a face image, encode it as effectively as possible. Then it has to be compared with models stored in the database. In Principle Component Analysis (PCA), the variation in a collection of face images, independent of any judgment of features is captured. Hence, in PCA we are finding the direction where the variance is maximum.

PCA is an unsupervised dimentionality reduction algorithm. The goal is to preserve as much as necessary information and also maintain low number of variables..

### Requirements

1. Python 3
2. Numpy
3. Sci-kit Learn
4. Pandas
5. Matplotlib
6. Jupyter Notebook

### Installation

1. Python

Step 1: Visit and download Python from https://www.python.org/downloads/
Step 2: Install and add Python to path

2. Numpy

In command prompt
> pip install numpy

3. Sci-kit Learn

In command prompt
> pip install sklearn

4. Pandas

In command prompt
> pip install pandas

5. Matplotlib

In command prompt
> pip install matplotlib

6. Jupyter

In command prompt
>pip install jupyterlab

For conda users
>conda install -c conda-forge jupyterlab

To start Jupyter type 
>jupyter notebook

### Directory Structure
    .
    ├── src                     # Source files
    │   ├── s1
    │   │   ├── 1.pgm
    │   │   ├──  ...
    │   │   ├── 10.pgm
    │   ├── s2
    │   ├── ...
    │   ├── s40
    │   ├── pca_face_recognition.ipynb   # Jupyter Notebook
    │   ├── barbara.pgm   
    ├── LICENSE
    └── README.md


### Usage

Open src/pca_face_recognition.ipynb in Jupyter. After running, you will observe the performance of PCA in identifying faces through the classification accuracy curve.

### Credits

Ajay Biswas

