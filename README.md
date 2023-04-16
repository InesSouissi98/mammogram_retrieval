# Mammogram retrieval

Mammography is a common screening tool for breast cancer detection. However, the interpretation of mammograms can be subjective and prone to errors. In this project, we will develop a content-based mammogram retrieval system that uses similarity metrics to automatically retrieve similar images from a database. This system can assist radiologists in detecting breast cancer and making accurate diagnoses.

Collecting and pre-processing two datasets of mammograms: a dataset for general cases (need biopsy + no need biopsy);  a dataset for specific cases (probably benign + highly malignant). <br>
Using deep learning technique such as VGG-16 pre-trained model to extract features from mammograms. 

Implementing similarity metrics to measure the similarity between the query image and the images in the dataset such as Euclidian, Minkowski, Dice, Cosine, Correlation, Canberra, Chebyshev and Hamming.
Setting 5 as number of retrieved mammograms.

**Tools :** <br >
Programming language: Python. <br >
Data processing libraries: Pandas and NumPy. <br >
Similarity metrics: Euclidian, Minkowski, Dice, Cosine, Correlation, Canberra, Chebyshev and Hamming. <br >
Deep learning model: VGG16
