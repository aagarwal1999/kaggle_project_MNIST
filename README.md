# kaggle_project_MNIST

Hello, before you embark on reading this code, you must download the database I used from the website below
The reason for this is because the data-sets are too large to be pushed remotely to github. 

Here is the website URL: https://www.nist.gov/itl/iad/image-group/emnist-dataset 

Make sure you download the matlab files, not the binary files. 

Once that is done, extract the files into a folder called Data. After that, everything should work. 

# Summary

Over the past week or so, I have been working on creating a Neural Network for the Kaggle competition located here: https://www.kaggle.com/c/digit-recognizer. However, I have decided to expand the dataset into the emnist dataset including letters as well, just to see if anything will happen. 

This is meant as a beginner project. So far, here is what I have done

  1. Implemented a model in TensorFlow for both MNIST and EMNIST. Results: 92% performance on MNIST, 67% performance on Letters, and 54% performandce on both
  
  2. Implemented a neural network from scratch including sigmoid and relu activation functions and functionality for both mean-squared error and cross entropy loss functions. Results: 93% performance on MNIST and dismal (20%) performance on the rest. 
  
  3. Next step is to implemetn a convolutional neural network on the data ultimately hoping for 99% on MNIST and 90+% on Letters and Both. 
