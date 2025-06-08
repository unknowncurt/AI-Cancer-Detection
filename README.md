# AI-Cancer-Detection
We (MAH) will be training an AI model to differentiate between healthy brains and one's with cancer through images of brain scans , and if that brain does have cancer, which type would it be.

Group project by Melodie, Amanda, and Hamza.
data set found from keggle - https://www.kaggle.com/datasets/indk214/brain-tumor-dataset-segmentation-and-classification


# JUNE 7 
# Hamza
-  Created Repository and a basic README.md file
- im coding on VS code since its easier for bigger projects but i will be adding everything to the notebook
- downloaded needed files
- created notebook https://colab.research.google.com/drive/1ta3NBt1ExlhfpxX9aSWSA42KGqO-Jpzs?usp=sharing
- created files and separated content (No tumor scans in a huge file, Glioma 
 Meningioma and Pituitary tumors each in their own file )

# JUNE 8 
# Hamza
- Images stored on colab dissapeared . this is why i dont like working with it . 
- im Using brew to install all required stuff
- uploaded images to drive using rclone and set directory up
- uploading neccasary libraries needed for CNN , etc...
- Synced the DATASET
- Mounted Drive in Colab
- i fixed the values and lowered them to match medical accuracy and not cause fake diagnosis
- VALUES TO BE CHANGED UNTIL GOOD ACCURACY IS REACHED.
- so train_datagen has a lot of tweaking and changes with each image to train the model to understand and diagnose all types of MRI scans thrown at its face.
 5712 images to be trained on belonging to 4 classes. 
 1311 images that we test on belonging to 4 classes.  
 * (if data is not sufficient we will utilize more data sets and fix the values and accuracy is reached)
- Built Keras ImageDataGenerators for training (augmentations) and testing (rescaling)
- Created train_generator and test_generator with  flow_from_directory for classification










Citations requested :

• Masoud Nickparvar, Kaggle Brain Tumor Dataset, 2020.
• SciDB Brain Tumor Dataset, SciDB, 2021.

TOTAL IMAGES TO BE TRAINED : 7023 images consisting of 4 classes: glioma - meningioma - no tumor and pituitary. (Around 300 images each)


















Citations requested :

• Masoud Nickparvar, Kaggle Brain Tumor Dataset, 2020.
• SciDB Brain Tumor Dataset, SciDB, 2021.

TOTAL IMAGES TO BE TRAINED AND TESTED : 7023 images consisting of 4 classes: glioma - meningioma - no tumor and pituitary. (Around 300 images each)

