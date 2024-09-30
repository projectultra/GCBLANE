# GCBLANE: A Graph-Enhanced Convolutional BiLSTM Attention Network for Improved Transcription Factor Binding Site Prediction

### Authors

- Jonas Chris Ferrao
- Dickson Dias
- Sweta Morajkar

## Overview

GCBLANE is a model designed for predicting transcription factor binding sites (TFBS). It integrates convolutional, recurrent, and attention layers with a graph neural network to enhance prediction accuracy.


## Model Architecture
Here is the model architecture diagram:

<img src="./Model/GCBLANE.png" alt="Model Architecture" width="50%" height="auto" style="background-color: white; padding:10px" />

## Features

- Combines various neural network architectures for improved TFBS prediction.
- Functions as a DNA sequence embedder for dimensionality reduction.
- Achieves state-of-the-art performance on ENCODE ChIP-seq datasets.

## Dependencies
[Google Colab](https://colab.research.google.com/) was used to train the model. The following dependencies are required:
- Python 3.10.12
- tensorflow==2.17.0
- keras==3.4.1
- numpy==1.26.4
- pandas==2.1.4

## Evaluation

Evaluate the model's performance using the following metrics:

- Average AUC on 690 datasets: 0.943
- Average AUC on 165 datasets: 0.9495

## Datasets

The model is trained and evaluated on datasets from the Encyclopedia of DNA Elements (ENCODE) chromatin immunoprecipitation sequencing (ChIP-seq) experiments.

Obtained from: https://csbioinformatics.njust.edu.cn/msdensenet/datasets.html