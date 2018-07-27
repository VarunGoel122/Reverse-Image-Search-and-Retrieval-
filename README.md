# Reverse Image Search and Retrieval 
Re-trained VGG16 Model on Caltech Image dataset with around 9,000 images for training, using Keras, for searching and retrieving images similar to the given query image. 

Download the dataset from
(http://www.vision.caltech.edu/Image_Datasets/Caltech101/)

Used libraries: -
1. Keras
2. PCA
3. SciPy
4. Tqdm
5. Matplotlib

Tensorflow backend is used. 

Steps involved: -
1. Imported VGG16 and modified it to extract features from images.
2. PCA is used to reduce the number of required features per image.
3. Euclidean Distance is used to define the relation between images. Each pair of images with small Euclidean distance are considered to be similar.
4. Tqdm is a library to visualize a loop in the form of a progressive bar.
5. Query image and the resulting related images are shown using Matplotlib.
