# DNN_MNIST
In this repository I have used Convolutional Neural Network in order to classify the digits and get the test accuracy of above 99%.

# Accuracy received over the test data --> 99.43%

Some Key Concepts in Convolutional Neural Networks and their definitions.

# 1.) Convolution -> It is a operation in which a matrix of size n*n is moved over an image of some size (every block containing a number,which is the pixel value lying between 0 and 1 after normalisation) and every value of the n*n matrix is multiplied with every corresponding value of the image matrix (falling below the n*n matrix) and the final result received is the sum of all those values.

# 2.)Kernels -> In the above definition the n*n matrix I discussed is given a special name which we call as Kernel.

# 3.)Epochs -> Epochs is a numeric value which corresponds to how many times our algorithm has seen the entire data.We will always need to show our data to our algorithm quite a number of times in order to get a good accuracy and convergence to take place.

# 4.)1*1 Convolution -> In the above definition 1. and 2. when we use the kernel of size 1*1 or you can say when the value of n=1 based on definition 1 and 2 in above context then we call it as 1*1 convolution.We get back the same image data matrix after applying 1*1 Convolution. Why? --> think about it its straight forward if you understood definition 1.

# 5.)3*3 Convolution -> In the above definition 1. and 2. when we use the kernel of size 3*3 or you can say when the value of n=3 based on definition 1 and 2 in above context then we call it as 3*3 convolution.We lose 2 pixels when we apply 3*3 Convolution.For example if 3*3 convolution is applied on an image of size 400*400 you will get an image data matrix of size 398*398.

# 6.)Feature Maps -> After applying convolutions we get an output which is also an image data matrix.If we visualise that matrix which is received after applying the convolution then that visualisation will be the visualisation of the features detected by our Convolution operations and that we call as feature maps.

# 7.) Activation Function -> Activation functions are the functions which when applied to some data produces non linearity in the data and they are important because in order to build complex model we do need non linearity in our data because complex function graphs cannot be made by only using the linear function we do need some non linearity as well.

# 8.) Receptive Field -> When we apply the convolution operation then we get a single number after performing n*n calculations wher n*n is the size of the kernel it means that that single number represents that particular n*n region of the image hence we call that n*n region as the receptive field of kernel.There are two types of receptive fields --> 1.) Local Receptive field and 2.)Global receptive field.

     
