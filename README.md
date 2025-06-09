# AI-Cancer-Detection
We (MAH) will be training an AI model to differentiate between healthy brains and one's with cancer through images of brain scans, and if that brain does have cancer, which type would it be.

Group project by Melodie, Amanda, and Hamza.
Data set found from Kaggle - https://www.kaggle.com/datasets/indk214/brain-tumor-dataset-segmentation-and-classification


# JUNE 7 
# Hamza
- Created Repository and a basic README.md file
- I'm coding on VS code since its easier for bigger projects but i will be adding everything to the notebook
- Downloaded needed files
- Created notebook https://colab.research.google.com/drive/1ta3NBt1ExlhfpxX9aSWSA42KGqO-Jpzs?usp=sharing
- Created files and separated content (No tumor scans in a huge file, Glioma, Meningioma, and Pituitary tumors each in their own file)

# JUNE 8 
# Hamza
- Images stored on colab dissapeared. This is why I don't like working with it. 
- I'm Using brew to install all required stuff
- Uploaded images to drive using rclone and set directory up
- Uploading necessary libraries needed for CNN , etc...
- Synced the DATASET
- Mounted Drive in Colab
- I fixed the values and lowered them to match medical accuracy and not cause wrong diagnosis
- VALUES TO BE CHANGED UNTIL GOOD ACCURACY IS REACHED.
- So train_datagen has a lot of tweaking and changes with each image to train the model to understand and diagnose all types of MRI scans thrown at its face.
 5712 images to be trained on belonging to 4 classes. 
 1311 images that we test on belonging to 4 classes.  
- (If data is not sufficient, we will utilize more data sets and fix the values until accuracy is reached)
- Built Keras ImageDataGenerators for training (augmentations) and testing (rescaling)
- Created train_generator and test_generator with flow_from_directory for classification

# JUNE 9
# GROUP WORK
- Faced issue with the directory not being accessible to everyone 
- Amanda downloaded API from Kaggle and adjusted it
- Work split three way into readjusting written code onto new file
- Ran the first training session and reached accuracy 0.81 at 3 epochs
- Increased epochs to 5
- Accuracy increased to 0.86

Citations requested:

• Masoud Nickparvar, Kaggle Brain Tumor Dataset, 2020.
• SciDB Brain Tumor Dataset, SciDB, 2021.

TOTAL IMAGES TO BE TRAINED : 7023 images consisting of 4 classes: glioma - meningioma - no tumor and pituitary. (Around 300 images each)



