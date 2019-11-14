# EIP4
Convolution: 
        For extracting the features like edge detection or any features in an image, we apply some operation and it's output is sent to next layer as input.
Filters/Kernels:
        filter (or) kernels are the matrices of 3*3. generally kernel are used for feature extraction in covolution. By applying filter to first layer we get second layer this layer can see it's local neighbour pixels. example, if my kernel has 9 parameters, it looks for 9 values of the image and perform multiplication to give output.
        here kernel size is consider as 3, as 3*3+3*3=18 weights where  5*5 kernel has 25 weights
Epoch: 
        n epochs means proccess the model/algorithm for n times (or) to pass the algorithm for n times, over the total dataset.
1*1 Convolution: 
        1*1 convolution means, it's just a filter/matrix with 1*1 size
3*3 Convolution: 
        it;s a fliter/matrix with 3*3 size. where 1*1 covolution didn't had any local/neigbour pixels, we use 3*3 filter. that's why we use kernel 3*3.
Feature Maps: 
        it is filter's output which was applied to previous layer. which looks for the same feature (or) it's a weight matrix.
Activation Function:
        to get the output of neural network. some activation functions are Rectified linear unit and tanh, sigmoid. here differentiability is important
Receptive Field: 
        Area of image which would influence the output. (or) neighbour pixels which could be seen. lrf means how many local neighbour pixels which could be seen where grf means how many pixels are seen in original image and it must be nearer to size of object.