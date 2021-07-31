# Facial Recognition
Faces are high dimensionality data consisting of a number of pixels. 
Data in high dimensionality is difficult to process and cannot be visualized using simple techniques like scatterplots for 2-dimensional data.

# Principal Component Analysis :
Principal Component Analysis (PCA) is a machine learning algorithm that is widely used in exploratory data analysis and for making predictive models. It is commonly used for dimensionality reduction by projecting each data point onto only the first few principal components to obtain lower-dimensional data while preserving as much of the data’s variation as possible.

# Dataset :
The dataset used in this example is a preprocessed excerpt of the “Labeled Faces in the Wild”, aka LFW:
http://vis-www.cs.umass.edu/lfw/lfw-funneled.tgz

# Viola-Jones Face Detection Technique, popularly known as Haar Cascades :
It is an Object Detection Algorithm used to identify faces in an image or a real time video. The algorithm uses edge or line detection features proposed by Viola and Jones.

# Result :
The Principal Component Analysis algorithm was used to reduce the dimensions of the data we had; images having a number of pixel values.
Then we used SVM for classification by finding the best estimator by hyperparameter tuning. We were able to classify the portraits and got an accuracy score of 0.89.


