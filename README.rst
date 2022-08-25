# Prediction of Crossover Recombination using Methylation Data

This is a Python3 implementation to predict recombination rates in rice using the count of methylated cytosines per 100 kb as the input feature. It uses the "Extra Trees" machine learning model to develop the predictions. Data for two rice varieties "IR64" and "Azucena" are provided. Model is trained with the data from one variety to predict recombination by chromosome using the information from the other variety. 

## Usage
The main algorithm and other utilities are implemented in the `nocd` package that can be installed as
```bash
python setup.py install
```
A Jupyter notebook [interactive.ipynb](interactive.ipynb) contains the code for training the model and analyzing the results.

Experiments in the paper have been performed using an older TensorFlow version of the code that can be found 
[here](https://figshare.com/s/30894e4172505d5dc070).

## Requirements
```
numpy=1.16.4
pytorch=1.2.0
scipy=1.3.1
```

