# activity-recognition

# Goal
Classify an open dataset containing time-series using different techniques:
1. Features augmentation (FFT, PSD, Autocorrelation) combined with Random Forest
2. Wavelet decomposition into 2D scaleograms combined with a CNN

# Dataset 

Link to download dataset: https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The Human Activity Recognition Dataset (UCI-HAR) contains sensor measurements of people while they were doing different types of activities. There are in total more than 10.000 signals where each signal consists of nine components:
    xyz accelaration
    xyz gyroscope
    xyz total accelaration
    
This dataset contains measurements done by 30 people between the ages of 19 to 48. The measurements are done with a smartphone placed on the waist while doing one of the following six activities:
    walking,
    walking upstairs,
    walking downstairs,
    sitting,
    standing or
    laying.

The measurements are done at a constant rate of 50 Hz. After filtering out the noise, the signals are cut in fixed-width windows of 2.56 sec with an overlap of 1.28 sec. Each signal will therefore have 50 x 2.56 = 128 samples in total.

# Results

### Features augmentation (FFT, PSD, Autocorrelation) combined with Random Forest

### Wavelet decomposition into 2D scaleograms combined with a CNN
