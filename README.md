# Gravity Inversion: Traditional vs Deep Learning

This repository presents a comparative study of traditional gravity inversion
techniques and deep learning–based inversion using Convolutional Neural Networks (CNN).

The objective is to quantitatively compare physics-based gravity inversion
methods with data-driven deep learning approaches for subsurface density
estimation.

## Workflow
1. Forward gravity modelling
2. Traditional inversion (Gauss–Newton / Least Squares)
3. CNN-based inversion

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
