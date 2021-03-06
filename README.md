# Convolutional-Neural-Network

Overview for files in the repository

## 0. Tuorial on Deep Learning Basics 
Basic concepts of deep learning are discussed here. <a href="https://github.com/iVibudh/Convolutional-Neural-Network/blob/main/0.%20tutorial_deep_learning_basics/deep_learning_basics.ipynb">Link to file ↩</a>

## 1. Learn and Practice CNNs  
High level conpepts of CNNs are discussed along with a CNN model to classify images of dogs and cats. <a href="https://github.com/iVibudh/Convolutional-Neural-Network/blob/main/1.%20Learn%20and%20Practice%20CNNs%20-%20Tensorflow/Learn%20and%20Practice%20CNNs%20-%20Binary%20Classification.ipynb">Link to file ↩</a>

Note: The training and test data is not available as the folder size was close to 200Mbs. Can be found in the private folder. <a href="https://drive.google.com/drive/folders/1M3TDNKI_PyZQ6ziLnKUWGD8-jhC6S7r6">Link to file (private folder) ↩</a>

## 2. Emotion AI: Facial Key-points Detection
Here, we are trying to build a deep learning model based on CNN and Residual Blocks to predict the **'Facial Key Points'**. Further we will try to predict the emotion associated with these images using these facial key points. <a href="https://github.com/iVibudh/Convolutional-Neural-Network/blob/main/2.%20KeyFacialPointsDetection/KeyFacialPointsDetection.ipynb">Link to file ↩</a>


## 3. Visualize Filters of a CNN model using Tensorflow  
In this project we are trying to visualize image features that maximally activate filters of a CNN on a pretrained **VGG16 architecture**.  

Visualize various filters from different layers will help us understand:
- what those filters are looking for in the input
- help in getting a deeper understanding of Convolutional networks
- helps in using the networks for various tasks - neural style transfer

Some key observations:
- **Early Block filters:** The early block filters are good at observing basic features or simple patterns such as colour, lines, etc. 
- **Later Block Filters:** These are looking at more complicated patters, i.e., these filters are maximally activated by more and more complex features.
- Some later block filters, you may observe that the images generated are very random. You might want to look at loss values here. It might be the case that these filters are not activated much and might not have a huge impact in making the decisions.
- For later block filters, you may observe that there are similar patters of various sizes, maybe it might be indicating patters of various sizes. 

Read more about 3 ways of visualizing deep convolutional network in this article: https://towardsdatascience.com/understanding-your-convolution-network-with-visualizations-a4883441533b


<a href="https://github.com/iVibudh/Convolutional-Neural-Network/blob/main/3.%20Visualizing%20Filters%20of%20a%20CNN%20using%20TensorFlow/Visualizing_Filters_of_a_CNN.ipynb">Link to file ↩</a>