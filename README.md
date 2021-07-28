# Scene-recognition-Deep-learning-
Classify the whole image to one of six classes: Buildings, Forest, Glacier, Mountain, Sea or Street. 
Build deep learning models that can recognize the category of the natural images (buildings, forest, glacier, mountain, sea and street). The goal is to build a model that can recognize the category of each image in the testing set with high accuracy.

Dataset
This dataset contains natural images of size 150x150 for 6 categories (buildings, forest, glacier, mountain, sea, and street). The training set contains 6 folders, around 2300 for each category. The testing set contains 3050 images.

you can download the dataset from: Google drive link (for Colab users)
[https://drive.google.com/drive/folders/1Jff904-zKuWeL45jbtb6Jsxg7-_ePkzk?usp=sharing]

Preprocessing
resize all images to 150x150
convert all images to RGB not BGR
apply data augmentation (zoom) to increase tha training data
Model Architecture
The model uses 8 conv layers, 3 average pooling, 1 flatten, 2 dropout and 3 fully connected layers.

How to use
You can train the model and save model weights from 'CNN_with_accuracy_89_453.ipynb' file, download test set folder too and run the 'test.py' file.

Tools
Python Jupter (Colab)
