# AI-Cancer-Detection Project Using CNN
# Authors : Amanda Loeung, Hamza Harb, Melodie Cornelly 
# Instructors : Dr. Christelle Scharff , Dr. Kaleema, Stephanie Sicilian


Data set used from Kaggle - https://www.kaggle.com/datasets/indk214/brain-tumor-dataset-segmentation-and-classification

## Project Objective

This project aims to assist medical professionals in detecting brain tumors from MRI scans using deep learning. It explores the effectiveness of CNNs in medical image classification and serves as a reference for future diagnostic tools.


## Project Structure 
 **Data Download**: From Kaggle using `kagglehub`
- **Data Preprocessing**: Rescaling, rotation, zoom, and brightness adjustment
- **Model Architecture**: CNN (or EfficientNet if applied), trained on 224x224 MRI images
- **Training**: Augmented data, validation split, early stopping, and checkpointing
- **Evaluation**: Accuracy score, confusion matrix, classification report
- **Prediction**: Model can predict on new/unseen brain MRI scans

## Tools Used 
- Python 3
- TensorFlow / Keras
- NumPy, Matplotlib
- KaggleHub
- Jupyter Notebook


## Data Augmentation Techniques 
To improve generalization we applied the following : 
- `rotation_range=10` – minor rotations
- `width/height_shift=0.05` – shift tumor regions
- `zoom_range=0.15` – vary tumor sizes
- `brightness_range=[0.8, 1.2]` – simulate scanning variations
- `horizontal_flip=False` – preserved anatomical orientation
- `validation_split=0.2` - helps monitor how well the model generalizes to unseen data

## Model Performance

- **Total Images**: 7,023 (5,712 training / 1,311 testing)
- **Tumor Classes**: 4 (e.g., Glioma, Meningioma, Pituitary, No Tumor)
- **Epochs Trained**: 5
- 
| Metric     | Value   |
|------------|---------|
| Accuracy   | 84.0%   |

## Acknowledgements

- [Kaggle Dataset by indk214](https://www.kaggle.com/datasets/indk214/brain-tumor-dataset-segmentation-and-classification)
- TensorFlow & Keras for deep learning tools


## Collaborators

This project is a collaboration between:
- [@unknowncurt](https://github.com/unknowncurt)
- [@AmLo](https://github.com/amlo026)
- [@Melodiehc](https://github.com/melodiehc)

Instructors :
-   @scharffc
-   @kaleema
-   @stephsicilian
