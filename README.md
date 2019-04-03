# TensorflowProject

This project applies neuronal networks to notMNIST dataset. This dataset includes 500k examples of 10 different classes: images of different type font letters from ‘A’ to ‘J’ and their corresponding
labels indicating the class(an integer number between 0 and 9.). Each sample corresponds
to a 28x28 (784) pixels(Each pixel has 255 gray levels ). The dataset has been
preprocessed:

- the Images are converted to matrices of 28x28 integer numbers (attributes),
normalized into [-1,1]: (pixel_value -127)/127.

- Corrupted images have been removed.

- Dataset is randomized and three sets have been randomly created: 200k examples for training; development and testing sets with 10k samples each.

However, the implementation has used just 10k examples for training and 1k for development and testing.

The problem to resolve is classify images into their correct labels using a deep neural
network and optimize the network as much as possible in terms of accuracy.


