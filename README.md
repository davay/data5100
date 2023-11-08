# Data 5100 Project - Fall 2023 

## Goal

Apply transfer learning techniques to a public imagenet model such as ResNet34 using Chest Cancer CT Scan images so that the resulting model is able to accurately classify between 3 types of cancer: 'Adenocarcinoma', 'Large Cell Carcinoma', and 'Squamous Cell Carcinoma'.

## Running Locally

1. Create a new conda env

```
conda create -n data5100 python=3.11
conda activate data5100
```

2. Run classifier.ipynb

## Data Source & Preparation

Chest CT images retrieved from https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images/

Changelog: 
- Renamed subfolders within 'data/train' and 'data/valid' (e.g. from 'large.cell.carcinoma_left.hilum_T2_N2_M0_IIIa' -> 'large.cell.carcinoma')

## License

Code licensed under Creative Commons Attribution-NonCommercial 4.0 (CC BY-NC 4.0)

Chest CT images licensed under Open Data Commons Open Database License (ODbL) v1.0