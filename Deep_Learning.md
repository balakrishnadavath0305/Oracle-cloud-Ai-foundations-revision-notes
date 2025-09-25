# **Deep Learning**

Subset of ML, that identifies complex patterns using ANN(Artificial Neural Networks). It contains multiple hidden layers where each layer identifies pattern further to its previous layers



**Why do we need DL?**

ML needs to specify features but DL automatically extracts features, increases the performance by performing the data parallelly 



**Deep Learning Algorithms**

***1)Images and videos:*** Convolutional Neural Networks(CNNs)

***2)Text and sequential data:*** Transformers, RNNs and LSTM

***3)Images, Text and Audio Generation:*** Transformers, Diffusion models, Generative Adversarial Networks(GAN)



**What is ANN?**
Inspired by Human Brain. Consists of Interconnected nodes called neurons. Each input has a weight associated with it which is multiplied and summed up for output, if the output meets the threshold then the neuron fires. Each output is passed as an input to the another layer 



**Building Blocks of ANN**

***1)Layers:*** Input, Hidden and Output where input and output layers are mandatory

***2)Neurons:*** computational unit from input and produces output

***3)weights:*** strength of connection b/w neurons

***4)Activation function:*** works on the weighted sum of inputs and produces output

***4)Bias:*** additional inputs



**How ANNs are trained?**

Using Backpropagation



**Deep Learning models**

***1)Sequential models:*** Input data is in the form of sequences. The goal is to find patterns and make predictions 



**Why RNNs?**

Handles sequential data, maintains a hidden state and feedback loops

**Types of RNN architecture:**

***1)one to one:*** similar to FNN and not suitable for sequential data

***2)one to many:*** (many outputs for single input) music generation

***3)many to one:*** sentiment analysis

***4)many to many***: machine translation



RNNs have vanishing gradient problem it doesn't maintain too much of information for long time so we use LSTMs

**What is LSTM?**

Long Short Term Memory captures long term dependencies in sequential data It collectively remembers or forgets the information over time and erases the vanishing gradient problem which is caused by RNNs for sequential data



***Workflow of LSTM:***

1)Input Processing

2)Previous memory

3)Gating mechanism

4)Updating of memory

5)Output generation





***Deep Learning models:***

1)Feed forward Neural Networks(FNNs)

2)Convolutional Neural Networks(CNNs)

3)Recurrent Neural Networks(RNNs)

4)Autoencoders

5)Transforms

6)Generative Adversial Networks

7)Long Short Term Memory(LSTMs)



***Convolutional Neural Networks(CNNSs)*** are better suited to process data i.e two dimensional data such as images and videos which is grid like data, earlier in ANNs such data is converted into 1 dimensional data which may loss some useful information, but here there is no loss of such information or features



**Layers of CNN**

***1)Input layer:*** takes input of an image with diff height width and colors

***2)Feature extraction layer:*** pattern identification with ReLu activation function and pooling layer

***3)Classification layer:*** Fully connected output layers where classification occurs



**Feature extraction layers include:**

***1)Convolutional layer:*** applies convolutional operations to the image using small filters known as kernals

***2)Activation layer:*** allows the network to learn more complex patterns

***3)Pooling layer:*** reduces the convolutional complexity and spatial dimensity.



**Limitation of CNN:**

Computation, Overfitting, Sensitivity , Interpretability

