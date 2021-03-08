# FacialExpressionRecognization
deep learning  convolutional neural network  facial expression recognition  vgg

Facial expressions are the basic way for humans to express emotions, and they are indispensable non-verbal signals in human-to-human communication. In recent years, with the rapid development of computer technology, facial expression recognition has become a current hot research topic. Facial expression recognition algorithms can be roughly divided into two categories: expression recognition methods based on traditional learning and expression recognition methods based on deep learning. Among them, deep learning algorithms can autonomously learn the essential characteristics of data in an "end-to-end" manner, which has become the mainstream algorithm for current facial expression recognition research.
This article shows a face recognition algorithm based on the VGG19 network. First, the data is enhanced, such as cropping, flipping, etc., and then the pooling method and discarding strategy are used to effectively prevent the occurrence of over-fitting. Finally, the 10-fold cross-validation method is used to increase the amount of data during the test to improve the generalization of the model. Experimental results show that the recognition accuracy of the neural network on the FER2013 test data set is 73.21%.
