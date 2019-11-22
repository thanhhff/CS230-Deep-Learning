Quiz Week 3
The basics of ConvNets

1. What do you think applying this filter to a grayscale image will do?

⎡⎣⎢⎢⎢01101331−1−3−3−10−1−10⎤⎦⎥⎥⎥

	Detect vertical edges

2. Suppose your input is a 300 by 300 color (RGB) image, and you are not using a convolutional network. If the first hidden layer has 100 neurons, each one fully connected to the input, how many parameters does this hidden layer have (including the bias parameters)?

	27,000,100

3. Suppose your input is a 300 by 300 color (RGB) image, and you use a convolutional layer with 100 filters that are each 5x5. How many parameters does this hidden layer have (including the bias parameters)?

	2600

4. You have an input volume that is 63x63x16, and convolve it with 32 filters that are each 7x7, using a stride of 2 and no padding. What is the output volume?

	29x29x32

5. You have an input volume that is 15x15x8, and pad it using “pad=2.” What is the dimension of the resulting volume (after padding)?

	19x19x8

6. You have an input volume that is 63x63x16, and convolve it with 32 filters that are each 7x7, and stride of 1. You want to use a “same” convolution. What is the padding?

	3

7. You have an input volume that is 32x32x16, and apply max pooling with a stride of 2 and a filter size of 2. What is the output volume?

	16x16x16

8. Because pooling layers do not have parameters, they do not affect the backpropagation (derivatives) calculation.

	False

9. In lecture we talked about “parameter sharing” as a benefit of using convolutional networks. Which of the following statements about parameter sharing in ConvNets are true? (Check all that apply.)

	It reduces the total number of parameters, thus reducing overfitting.
	It allows a feature detector to be used in multiple locations throughout the whole input image/input volume.

10. In lecture we talked about “sparsity of connections” as a benefit of using convolutional layers. What does this mean?

	Each activation in the next layer depends on only a small number of activations from the previous layer.


