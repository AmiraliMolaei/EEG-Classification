# EEG Classification with Convolutional Neural Networks (CNN)

## Overview
This repository contains the code and resources for performing EEG (Electroencephalogram) classification using Convolutional Neural Networks (CNNs). EEG classification is a common task in brain-computer interface (BCI) and neuroscience research. This project demonstrates how to preprocess EEG data, build a CNN-based feature extractor, and train a classifier for EEG signal classification.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Dataset](#dataset)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites
Before getting started, ensure you have the following dependencies installed:
- Python (3.6+)
- TensorFlow (2.x)
- NumPy
- Matplotlib (for data visualization)

You can install these dependencies using the following command:
```bash
pip install tensorflow numpy matplotlib
```

## Dataset
The dataset is from the BCI Competetion III, which can be found in the following link:

```bash
https://www.bbci.de/competition/download/competition_iii/tuebingen/
```
The dataset consists of EEG (Electroencephalogram) recordings organized into individual trials. Each trial is based on different subjects, and each trial includes data from 64 EEG channels, where each of them include sampls for 3000 timepoints.
