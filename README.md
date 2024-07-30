# Deep Learning-Based Prediction of Atrial Fibrillation from Polar Transformed Time-Frequency Electrocardiogram
![ecg_animation1](https://github.com/user-attachments/assets/51da70fb-1ea6-4493-a2c6-15437a0f3e23)
![Iris](https://github.com/user-attachments/assets/c5d1d58c-5881-4bd7-82fe-3db81b9f32fa)
[This gif shows not a process of visualizaiton! :)]

This project provides a novel visualization of single-lead electrocardiograms (ECG) in the time-frequency domain.

## Context
1. Module Installation
2. ECG Data Reading
3. Preprocessing ECG Data: PT Algorithm (Optional)
4. ECG Visualization
5. Saving Polar Images
6. GUI

## Environment
The code is executed with the following versions on Python 3.11.3:
- wfdb: 4.1.2
- matplotlib: 3.7.3
- pandas: 2.1.0
- numpy: 1.25.2
- scipy: 1.11.1

## Source: Classification of Atrial Fibrillation Using PhysioNet 2017 Challenge Dataset

### Introduction
This project utilizes the PhysioNet/Computing in Cardiology Challenge 2017 dataset, which contains ECG recordings labeled as Normal, Atrial Fibrillation (AF), Other Rhythm, or Too Noisy. The goal is to develop an algorithm that accurately classifies these recordings.

### The dataset includes:
- Over 10,000 short, single-lead ECG recordings.
- Four labels: Normal, AF, Other Rhythm, Too Noisy.

More details can be found on the [PhysioNet Challenge 2017 page](https://physionet.org/content/challenge-2017/1.0.0/).

## Acknowledgements

1. This project utilizes code from [Pramod07Ch](https://github.com/Pramod07Ch). Their contributions have been invaluable. You can find the original repository [here](https://github.com/Pramod07Ch/Pan-Tompkins-algorithm-python).

2. cartesian_to_polar.py is contributed by Dongwoo Lee from Yonsei University (hepsdata@yonsei.ac.kr). This project uses his code for image saving.

3. We used the image files generated from this script to perform classification tasks using the CNN model from [WingMaster22](https://github.com/WingMaster22). Their contributions have been invaluable. You can find the original repository [here](https://github.com/WingMaster22/polar-spectrogram-model).

## How to Use
1. Prepare the CiCC 2017 dataset in the same directory as Polar Spectrogram Project.ipynb.
2. Follow the steps in Polar Spectrogram Project.ipynb.

## Contact
If you have any questions about this project, please email me at kanghb777@yonsei.ac.kr.
