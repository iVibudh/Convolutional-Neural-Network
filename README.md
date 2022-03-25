# Convolutional-Neural-Network

Overview for files in the repository

#### 0. Tuorial on Deep Learning Basics 
Basic concepts of deep learning are discussed here. <a href="https://github.com/iVibudh/Convolutional-Neural-Network/blob/main/CNN_series/Introduction%20CNNs.ipynb">Link to file ↩</a>

#### 1. Learn and Practice CNNs  
High level conpepts of CNNs and discussed along with a CNN model to classify images of dogs and cats. <a href="https://github.com/iVibudh/Convolutional-Neural-Network/blob/main/CNN_series/Introduction%20CNNs.ipynb">Link to file ↩</a>

Note: The training and test data is not available. Can be found in the private folder. <a href="https://github.com/iVibudh/Convolutional-Neural-Network/blob/main/CNN_series/Introduction%20CNNs.ipynb">Link to file ↩</a>

#### 2. Emotion AI: Facial Key-points Detection
Here, I have duilt a deep neural networks to detect facial key points in images. <a href="https://github.com/iVibudh/Convolutional-Neural-Network/blob/main/CNN_series/Introduction%20CNNs.ipynb">Link to file ↩</a>



#### 3. Visualize Filters of a CNN model using Tensorflow  
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

<a href="https://github.com/iVibudh/Convolutional-Neural-Network/blob/main/CNN_series/Introduction%20CNNs.ipynb">Link to file ↩</a>
