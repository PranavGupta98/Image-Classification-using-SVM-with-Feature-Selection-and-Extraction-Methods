# Image-Classification-using-SVM-with-Feature-Selection-and-Extraction-Methods
Research Project conducted as part of CSC2515 at the University of Toronto. Convulutional Neural Networks are state-of-the-art NN model for image classification, this research investigates whether reducing the number of features can help simpler machine learning methods achieve similar accuracy as CNNs, while reducing the training time and computational power required.

This research investigates image classification performance on the CIFAR-10 dataset. Specifically, the performance of Convolutional Neural Networks was compared to Support Vector Machines enhanced through various feature extraction and feature selection methods. Performance is defined by both classification accuracy and training time. It was discovered that the feature extraction method; autoencoders, can increase performance of a simple SVM classifier, however they require a significant increase in training time and computational power. Simpler feature selection methods such as ReliefF and RFE were able to significantly reduce training time, with only a small reduction in accuracy (<1%). Lastly, a new feature selection method named Saliency Subset was investigated. This method was unable to increase accuracy or significantly decrease training time for our classification task, however it showed promising results in object detection. 
