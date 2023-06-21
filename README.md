# Malaria-cell-detection

- This notebook focuses on the analysis of the "Malaria Cell Images Dataset" obtained from Kaggle which can be found [here](https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria).
- The aim of this project is to develop a deep learning model to reliably distinguish the numerous photos of malaria-infected and uninfected cells in the dataset.

## Sections

- The notebook is divided into a number of sections, including an exploratory data analysis (EDA), model selection, data pre-processing, model construction, training, and validation, hyperparameter tweaking, model evaluation, presentation of results, and critical analysis and discussion.

## Models Used

- The models used in this notebook are as follows:
  - A CNN model with dropout layers, data augmentation, and batch normalization
  - A CNN model with dropout layers, data augmentation, batch normalization, and transfer learning (VGG16)
  - A CNN model with dropout layers, data augmentation, batch normalization, and transfer learning (EfficientNetB07)

## Disclaimer

- The python verion used in this notebook is 3.6.8 on a conda environment with GPU acceleration.
