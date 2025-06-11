# Skin Cancer Classification with CNN (HAM10000)

This project uses a Convolutional Neural Network (CNN) to classify dermatoscopic images from the HAM10000 dataset into skin cancer subtypes.

## Objective

To explore how deep learning can assist in the early detection and classification of skin lesions using dermatoscopic imaging data.

## Dataset

**HAM10000**: A dataset of 10,015 dermatoscopic images across 7 diagnostic categories.

Accessed using KaggleHub:

```python
import kagglehub
path = kagglehub.dataset_download("kmader/skin-cancer-mnist-ham10000")
```

## Workflow

1. **Data Preprocessing**: Resized images, normalized pixel values, and encoded class labels
2. **Exploratory Data Analysis (EDA)**: Class distribution analysis and sample image visualization
3. **Model Architecture**: CNN with convolutional, pooling, and dropout layers
4. **Training**: Conducted training with early stopping and validation split
5. **Evaluation**: Analyzed accuracy and loss curves, generated confusion matrix


## Status

Complete. Built as part of an applied machine learning course using Python and TensorFlow/Keras.

## Contact

**Isaac Oyediran**
- Email: isaacoyediran@gmail.com
- LinkedIn: [Profile Link]
