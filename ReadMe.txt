Build and train a neural networks to classify Devanagari Handwritten Characters.

Training Data: Each row corresponds to an image of size 32*32, with first column as output (46 classes)(So, 1st column for Output and then 1024 columns for image,
So, Total Columns = 1025)

Test Data: Output has been marked as -1 to keep it private

Implementation of MLP using backpropagation algorithm to train the network.

There are two variants of that: -
	
	one is trained using Batch Gradient Descent Algorithm
	
	other is trained using Stochaistic Gradient Algorithm

It uses adaptive learning rate (l_rate = l_rate0/epoch^1/2).

Preprocessing of the data is also done.

The code is written in python and it uses real-life dataset for recognition of the characters.

This part of code also includes GUI.

Results: -

Graph is plotted between average error values at each epoch and the sum of errors for each epoch vs the epoch

Accuracy for the test sample is also calculated along with the scores of the output for each fold

The values of error obtained, the learning rate for each epoch and the epoch number are outputted to the csv file

The values of error obtained, the learning rate for each epoch and the epoch number are shown on the GUI too

For convenience, the number of epoch had been initialised to 10, but they need to be increased to at least 100

By: -

Divyesh Saglani
BT16CSE004
CSE 3rd Year
IIIT Nagpur