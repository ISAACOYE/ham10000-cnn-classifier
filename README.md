# Skin Cancer Classification with CNN (HAM10000)

This project uses a Convolutional Neural Network (CNN) to classify dermatoscopic images from the HAM10000 dataset into skin cancer subtypes.

## Objective

To explore how deep learning can assist in the early detection and classification of skin lesions using dermatoscopic imaging data.

## Dataset

- **HAM10000**: A dataset of 10,015 dermatoscopic images across 7 diagnostic categories
- Accessed using KaggleHub:
  ```python
  import kagglehub
  path = kagglehub.dataset_download("kmader/skin-cancer-mnist-ham10000")
