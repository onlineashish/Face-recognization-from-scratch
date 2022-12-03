open google colab.
run the code.

Explanation to train the model:

1.-Flattern the images of the training set (from matrices to vectors)
2.-Calculate the mean of all the images.
3.-Then normalize the training set i.e. for each of the image, subtract the mean calculated.
4.-Then calculate the covariance i.e. multiply all images by themselves.
5.-Extract eigenvectors from the covariance thus calculated.
6.-Calculate eigenfaces: eigenvectors x normalized pictures.
7.-Choose the most significant eigenfaces.
8.-Calculate weights: chosen eigenfaces x normalized pictures.

To test your image into this code --> query = your image of shape(112,92) 
Run the code to find the best matching image from the model.