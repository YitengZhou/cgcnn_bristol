# Crystal Graph Convolutional Neural Networks

![Logo](dissertation/image/model.jpg)

This project details the development and optimisation of the CGCNN model, predicts various thermodynamic, mechanical, and electrochemical properties of inorganic materials, and evaluates mCGCNN models’ performances. 

## Members

- [Yiteng Zhou](https://github.com/YitengZhou) (ku19857@bristol.ac.uk)

## Datasets

### [Energy dataset](dissertation/datasets/energy) - formation, absolute, fermi, bandgap

### [Elastic dataset](dissertation/datasets/elastic) - bulk, shear modulus, Poisson ratio, elastic anisotropy

### [Dielectric dataset](dissertation/datasets/dielectric) - dielectric constant, electro-optic coefficient, ferroelectricity

### [Piezoelectric dataset](dissertation/datasets/piezoelectric) - piezoelectric modulus

## Implement Code

### [Fetch data from database](dissertation/code)

### [Main and predict](dissertation/code)

### [CGCNN model](dissertation/code/cgcnn)

## [Pre-train mCGCNN models](dissertation/pre-train_mCGCNN)

Eleven mCGCNN models could predict:

- formation energy - mCGCNN-formation

- absolute energy - mCGCNN-absolute

- Fermi energy - mCGCNN-fermi

- band gap - mCGCNN-bandgap

- bulk modulus - mCGCNN-bulk

- shear modulus - mCGCNN-shear

- Poisson ratio - mCGCNN-poisson

- elastic anisotropy - mCGCNN-anisotropy

- dielectric constant - mCGCNN-dielectric

- electro-optic coefficient - mCGCNN-eoc

- ferroelectricity - mCGCNN-ferro
