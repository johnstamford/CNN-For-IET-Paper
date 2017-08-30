## Synopsis

This is the practical implementation of the paper title "Scene Detection using Convolutional Neural Networks" which was published at the 2nd IET International Conference on Technologies for Active and Assisted Living 

Citation:
Stamford. J, and Peach. B, (2016) “Scene Detection using Convolutional Neural Networks”,  2nd IET International Conference on Technologies for Active and Assisted Living

[Paper Availbale Here](http://johnstamford.com/wp-content/uploads/2016/11/StamfordPeach_SceneDetection.pdf)


## Use

The code is provided as Jupyter Notebook (ipynb) files.

The initial stages of the work used a convolutional process to extract the features from the images (which are saved in the Data folder as a CSV file) using the script written in CNN Processing-Modified.ipynb.

Next, the data is run through a neural network developed using SciKit-NeuralNetwork as shown in Full CNN.ipynb.

Additional work explores dimensionality reduction of the convoluted data using Locally Linear Embedding. The results can be seen in the paper.

## Requirements
To run this code you will need...
* NumPy
* Pandas
* Theano
* [SKNN](https://scikit-neuralnetwork.readthedocs.io/en/latest/#)

I recommend install Anaconda Python.

