# ECG-signal-Classification-for-early-detection-of-cardiovascular-diseases


![ECG Classification Process](https://github.com/thibaut-tebi/ECG-signal-Classification-for-early-detection-of-cardiovascular-diseases/assets/113062383/8b957f09-f0b8-44fb-b38e-d4c37b6690be)


## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Electrocardiogram (ECG) is an essential diagnostic tool that records heart activity by detecting electrical changes with each heartbeat. This project introduces an advanced method for classifying ECG signals utilizing robust classification techniques.

## Features

- Preprocessing using Discrete Wavelet Transform (DWT) to attenuate high-frequency noise.
- Feature extraction based on statistical parameters.
- Classification using Support Vector Machine (SVM), K-Nearest Neighbors (KNN), and Random Forest (RF).
- Achieved remarkable accuracy levels: SVM at 90%, KNN at 83%, and RF at 86%.

## Dataset

The ECG data used in this project was obtained from the PhysioNet's PTB-XL diagnostic ECG Database. It underwent preprocessing using Discrete Wavelet Transform (DWT) for noise reduction and feature extraction. You can find the code to the data here: https://physionet.org/content/ptbdb/1.0.0/

## Methodology

1. Data preprocessing using DWT for noise reduction and signal enhancement.
2. Feature extraction based on statistical parameters from the refined signal data.
3. Classification using SVM, KNN, and RF to categorize ECG signals into normal or abnormal categories.

## Results

The experimental results demonstrate the following accuracy levels:

- SVM: 90%
- KNN: 83%
- RF: 86%

Model Performance 
![image](https://github.com/thibaut-tebi/ECG-signal-Classification-for-early-detection-of-cardiovascular-diseases/assets/113062383/76823f42-0a7c-4ef1-85d8-addd57e4f6ab)

The Support Vector Machine classifier exhibited superior performance, highlighting its potential in ECG signal classification.

## Contributing

Provide guidelines for others who want to contribute to your project. Include instructions on how to set up a development environment, guidelines for code style, and the contribution process.

## License

This project is licensed under the [Your License Name](LICENSE) - replace with your project's license information.



