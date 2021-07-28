## You'll learn about:
- How to quickly learn PyTorch

## First step
1. official tutorial: https://pytorch.org/tutorials/
	- [Link to the YouTube Video](https://www.youtube.com/watch?v=TB-G1KqRb5o&t=2394s)
	- hand-code to understand the details 

2. Go through [this](https://towardsdatascience.com/understanding-pytorch-with-an-example-a-step-by-step-tutorial-81fc5f8c4e8e#3a3f) step-by-step guide to PyTorch by Daniel Godoy and hand-code to understand the details 

3. [NumPy to PyTorch](https://www.youtube.com/playlist?list=PLqnslRFeH2UrcDBWF5mfPGpqQDSta6VK4) 
	- PyTorch Tutorials - Complete Beginner Course by Python Engineer
	- DIY to learn it 

4. [PyTorch Fundamentals](https://pytorch.org/tutorials/beginner/basics/intro.html) 

	- Most machine learning workflows involve working with data, creating models, optimizing model parameters, and saving the trained models. This tutorial introduces you to a complete ML workflow implemented in PyTorch, with links to learn more about each of these concepts.

	- We will use the FashionMNIST dataset to train a neural network that predicts if an input image belongs to one of the following classes: T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, or Ankle boot.

	- This tutorial assumes a basic familiarity with Python and Deep Learning concepts.

5. [Deep Learning Blitz](https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html)

	- What is PyTorch?
		- PyTorch is a Python-based scientific computing package serving two broad purposes:
			- A replacement for NumPy to use the power of GPUs and other accelerators.
			- An automatic differentiation library that is useful to implement neural networks.
	- Goal of this tutorial:
		- Understand PyTorch’s Tensor library and neural networks at a high level.
		- Train a small neural network to classify images

6. [PyTorch with Examples](https://pytorch.org/tutorials/beginner/pytorch_with_examples.html)
	> **Note**: This is one of the older tutorials. You can view latest beginner content in [Learn the Basics](https://pytorch.org/tutorials/beginner/basics/intro.html).

	- This tutorial introduces the fundamental concepts of PyTorch through self-contained examples. 

	- At its core, PyTorch provides two main features: 
		- An n-dimensional Tensor, similar to numpy but can run on GPUs 
		- Automatic differentiation for building and training neural networks 

	- We will use a problem of fitting $y = sin(x)$ with a third order polynomial as our running example. The network will have four prameters, and will be trained with gradient descent to fit random data by minimizing the Euclidean distance between the network output and the true output. 

7. What is `torch.nn` really? [link](https://pytorch.org/tutorials/beginner/nn_tutorial.html)

8. [Visualizing models, data and training with tensorboard](https://pytorch.org/tutorials/intermediate/tensorboard_tutorial.html) 
	- In the [60 Minute Blit](https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html), we show you how to load in data, feed it through a model we define as a subclass of `nn.Module`, train this model on training data, and test it on test data. To see what is happening, we print out some statistics as the model is training to get a sense for whether training is progressing. However, we can do much better than that: PyTorch integrates with TensorBoard, a tool designed for visualizing the results of neural network training runs. This tutorial illustrates some of its functionality, using the [Fashion-MNIST dataset](https://github.com/zalandoresearch/fashion-mnist) which can be read into PyTorch using *torchvision.datasets*. 

	- In this tutorial, we will learn how to: 
		1. Read in data and with appropriate transforms (nearly identical to the prior tutorial). 
		2. Set up TensorBoard. 
		3. Write to TensorBoard. 
		4. Inspect a model architecture using TensorBoard. 
		5. Use TensorBoard to create interactive versions of the visualizations we created in last tutorial, with less code. 

	- Specifically, on point #5, we will see: 
		* A couple of ways to inspect our training data 
		* How to track our model's performance as it trains 
		* How to access our model's performance once it is trained
