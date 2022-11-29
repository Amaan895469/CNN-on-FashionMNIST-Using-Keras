# CNN-on-FashionMNIST-Using-Keras
Implemented a CNN model using keras and tensorflow on fashion mnist. Achieved more than 93% accuracy.

We will implement a Convolutional Neural Network in Keras

Then we will apply our CNN to Fashion MNIST dataset
## Download the Fashion-MNIST dataset 


The MIST data set of handwritten digits
* is too easy (convolutional nets can achieve 99.7%) 
* is overused. 
* can not represent modern Computer Vision tasks

[Fashion-MNIST](https://github.com/zalandoresearch/fashion-mnist) consists of 60,000 training images and 10,000 test images. It is a MNIST-like fashion product database. The developers believe MNIST has been overused so they created this as a direct replacement for that dataset. Each image is in greyscale and associated with a label from 10 classes.

Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. 
Each example is a 28x28 grayscale image, associated with a label from 10 classes.a


Fashion-MNIST  serves as a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.

* Size: 30 MB

* Number of Records: 70,000 images in 10 classes

* Images are 28x28 NumPy arrays, with pixel values ranging between 0 and 255. 

* Labels are an array of integers, ranging from 0 to 9.

Label	Description
0.	T-shirt/top
1.	Trouser
2.	Pullover
3.	Dress
4.	Coat
5.	Sandal
6.	Shirt
7.	Sneaker
8.	Bag
9.	Ankle boot

On https://github.com/zalandoresearch/fashion-mnist there is a list of benchmarks and the related NN architectures.

