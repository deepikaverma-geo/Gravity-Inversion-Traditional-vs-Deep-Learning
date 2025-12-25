# Gravity Inversion: Traditional vs Deep Learning

This repository presents a comparative study of traditional gravity inversion
techniques and deep learning–based inversion using Convolutional Neural Networks (CNN).

## Scope of Study
- Forward gravity modelling using analytical (Harmonica) and numerical
  integration methods
- Validation of numerical integration against analytical solutions
- Gravity inversion using Gauss–Newton least squares
- Deep learning–based inversion using a CNN
- Performance comparison in terms of accuracy and convergence


## Workflow
1. Forward gravity modelling
2. Traditional inversion (Gauss–Newton / Least Squares)
3. CNN-based inversion
   
## Files in this Repository
- `01_forward_modeling.ipynb` – Forward gravity modelling and synthetic data generation
- `02_traditional_inversion_gauss_newton.ipynb` – Traditional gravity inversion using Gauss–Newton / least squares
- `03_cnn_based_inversion.ipynb` – Deep learning–based gravity inversion using CNN
- `gz_synthetic.npy` – Synthetic gravity anomaly dataset

## Results & Comparison
- Traditional inversion provides physically interpretable models but is
  sensitive to noise and initial assumptions.
- CNN-based inversion shows improved robustness and faster inference once
  trained, with competitive accuracy on synthetic datasets.

## Tools
- Python, NumPy, SciPy, Matplotlib
- Scikit-learn
- TensorFlow / PyTorch

## Background
Academic project completed during MSc Applied Geophysics at IIT Bombay,
focused on numerical modelling and machine learning applications in geophysics.
