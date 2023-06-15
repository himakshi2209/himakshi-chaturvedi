# himakshi-chaturvedi
himakshi projects
Tools used
• Python
• Google collab
• Tensorflow
• Matplotlib
• Numpy
• Pandas
• Keras
 
 About the dataset
CIFAR-10 Photo Classification Dataset
CIFAR is an acronym that stands for the Canadian Institute For Advanced Research and the CIFAR-10 dataset was developed along with the CIFAR-100 dataset by researchers at the CIFAR institute.
The dataset is comprised of 60,000 32×32 pixel color photographs of objects from 10 classes, such as frogs, birds, cats, ships, etc. The class labels and their standard associated integer values are listed below.
• 0: airplane
• 1: automobile
• 2: bird
• 3: cat
• 4: deer
• 5: dog
• 6: frog
• 7: horse
• 8: ship
• 9: truck
These are very small images, much smaller than a typical photograph, and the dataset was intended for computer vision research.
CIFAR-10 is a well-understood dataset and widely used for benchmarking computer vision algorithms in the field of machine learning. The problem is “solved.” It is relatively straightforward to achieve 80% classification accuracy. Top performance on the problem is achieved by deep learning convolutional neural networks with a classification accuracy above 90% on the test dataset.

  Model Summary:
We have used sequential model and used 2D convolution with 3,3 kernel with 32 filters. MaxPooling method is used for downsizing the dimensions with relu activation function.We have used dropout rate of 0.3 and output layer with ‘softmax’ activation function.Model is again compiled with optimizer ‘adam’ with loss ‘sparse_categorical_crossentropy’.
 
 Components of Convolutional Neural Network (ConvNet or CNN)
The purpose of the convolution is to extract the features of the object on the image locally. It means the network will learn specific patterns within the picture and will be able to recognise it everywhere in the picture.
Convolution is an element-wise multiplication. The concept is easy to understand. The computer will scan a part of their image, usually with a dimension of 3×3 and multiplies it to a filter. The output of the element-wise multiplication is called a feature map. This step is repeated until all the image is scanned. Note that, after the convolution, the size of the image is reduced.
A Rectified Linear Unit (ReLU) transformation is applied after every convolution operation to ensure non-linearity. ReLU is the most popular activation function but there are other activation functions to choose from.
After the transformation, all values below zero are returned as zero while the other values are returned as they are.

 
