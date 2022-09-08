# Project-Idea-BOB
Here is my project idea for automatic cheque verification.

# Problem Statement

• Nowadays signatures are mandatory in every banking sector even biometrics play a major role in most of the 
administrative areas. 

• This increases the chance of forgeries in this sector which causes some serious financial losses. 

• We use this prototype to verify the signatures with the previous signatures of the real person. 

• This system can be a great solution to the banking sectors to prevent the signature forgeries. 

• The system we use, only requires data feeding and doesn’t require any manpo

# User Segment 

• Banking sectors will be the main user of this product. 

• Any organization with signature verification as their protocol can be benefited by this method. 

• We focus mainly on reducing manpower on these kind of verification process as it is very difficult and 
takes much time. 

•It can be mounted in the system which makes this user friendly and can be accessed at any time they need. 

• The current signature will be uploaded to the cloud and it will be verified by machine which is trained by 
the previous datasets

# Pre-Requisite

• To have a basic computer knowledge to import the image in the portal or to enter captcha. 

• To be proficient in Azure or GC or AWS Cloud. 

• Having knowledge in Database Management System.

• To sort the error occurs on spot. Like errors in size and resolution of image etc., 

• To view and understand the output we achieve.

# Azure tools or resources

• Azure Ping

• Cloud Combine

• Azure Grid

# Key Differentiators & Adoption Plan

• In this project, the software uses deep learning algorithms to compare it with the real signature to identify 
even the minute variations. 

• We use extensions like Max pooling, Batch normalization and Conv 2D. 

• ConvNet , which is a class of deep and feed forward artificial neural networks that has been applied to analysing images. 

• TensorFlow is a library for Machine learning and artificial intelligence. 

• It can be used across a range of tasks but has a particular focus on training and inference of deep neural networks

# Project Idea 

• A standard database of signatures for every individual is needed for evaluating performance of the 
signature verification system and also for comparing the result obtained using other techniques on the 
same database. 

• We will be using transfer learning technique to build our model but before that we need to convert our 
images to certain fixed ratio. 

• Callbacks is a powerful tool by which we customize the behavior of Keras or TensorFlow model during 
training, evaluation or inference. 

• Now we need to read all the images from the folder. When we'll be reading the data from the folders, we 
also need to make sure that we need to do some Data Augmentation. 

• The Data Augmentation can be attained by using Image Data Generator library. The Image Data 
Generator what is does that it puts in the Data Augmentation techniques like vertical flipping, zooming, 
scaling, horizontal flipping, etc.

• In the test data, we shouldn’t perform data augmentation and scaling is the only thing that should be performed.
Then plotting of accuracy and losses must be done to measure the accuracy rate and precision of the system. 

• In the convolutional layer, extensions like Max pooling, Batch normalization and Conv 2D are used. Max Pooling
2D class is extracted from the library. 

• This operation is performed for taking 2D spatial data. It down samples the input along with its spatial dimensions
like height and width by considering the maximum value over an input window of size which is defined by the pool
size for each of the channel in the input. 

• The window is transferred by the strides along each dimension. Internal covariate shift is a major problem and it is
resolved by Batch normalization. 

• Internal Covariate Shift acts as the change in the dispense of network activations due to the varying of network
parameters during the training of the model.

• It assists by making the data flow among the intermediate layers of the neural network look, this means that we
can use some higher learning rates. The regularizing effect removes the dropout effect. 

• Conv2D parameter is the count of filters that the convolutional layers will evolve from. This is an integer value
and it settle the number of output filters used in the convolution layer.


