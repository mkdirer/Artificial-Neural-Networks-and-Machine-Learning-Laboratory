### Question 1
Which metric allows achieving the best results for regression purposes?
- a. Dice coefficient
- **b. Mean absolute error**
- c. Weighted error
- d. Such a metric does not exist

### Question 2
In the absence of padding, the output size after convolution is smaller than the input size.
- Select one answer:
  - **True**
  - False

### Question 3
When does the phenomenon of overfitting occur in a neural network?
- a. When the neurons in the network return numbers larger than those permissible by the training set
- b. When the network stops functioning due to processing too many training records
- c. When the connections between neurons have a value of 0
- **d. When the network returns correct results on the training set but incorrect results on the test set**

### Question 4
Overfitting occurs when a model fits the training data too closely, which may lead to poor performance on new data.
- Select one answer:
  - **True**
  - False

### Question 5
Which preprocessing technique can be applied to datasets?
- a. Automatic use of a graphical filter
- b. Data cannot be modified before the training process
- **c. Removal of irrelevant words from text strings**
- d. All answers are correct
- **e. Normalization of input data**

### Question 6
Can GNN be used for node classification tasks in a graph?
- a. Only in specific types of graphs.
- **b. Yes, GNN can be used for node classification in a graph.**
- c. Yes, GNN can be used for classification of certain nodes in a graph.
- d. Only in graphs with a specific number of nodes.
- e. No, GNN cannot be used for node classification in a graph.

### Question 7
LSTM is a type of recurrent layer in a neural network in Keras.
- Select one answer:
  - **True**
  - False

### Question 8
What is the task of the decoder layer in an autoencoder?
- a. Dimensionality reduction of input data
- b. Anomaly detection in input data
- c. Transforming input data into a different space
- **d. Generating output data**

### Question 9
Underfitting does not always lead to poor results on test data.
- Select one answer:
  - True
  - **False**

### Question 10
What are the potential future applications of GNN?
- **a. Improving recommendation systems**
- b. Automatic graph generation
- **c. Analysis and prediction of trends in social networks**
- **d. All of the above**

### Question 11
What is GRU and how does it differ from LSTM?
- a. A type of neural network that has more connections between neurons than LSTM.
- **b. A type of recurrent network that is more flexible and easier to use than LSTM.**
- c. A type of neural network that is more effective in image processing than LSTM.
- d. A type of recurrent network that has fewer connections between neurons than LSTM.

### Question 12
What is the cost function in neural networks?
- a. A cost function is a process in which a neural network tries to minimize the difference between predictions and actual values.
- **b. A cost function is a mathematical function that assigns a numerical value to each weight vector in a network model.**
- c. A cost function is an optimization method that minimizes the prediction error of the model.
- d. A cost function is a metric that measures how well the model fits the training data.

### Question 13
Underfitting occurs when the model is not sufficiently fitted to the training data, leading to poor results on new data.
- Select one answer:
  - **True**
  - False

### Question 14
LSTM can effectively handle sequence modeling problems and is a suitable choice when you want to analyze long sequences of data.
- Select one answer:
  - **True**
  - False

### Question 15
The Conv1D layer is not used in time series data analysis and helps in feature extraction from such data.
- Select one answer:
  - True
  - **False**

### Question 16
Which algorithm is the basis for the most effective neural network architectures?
- a. Pitts Algorithm
- b. Kohonen Algorithm
- **c. Backpropagation Algorithm**
- d. Adam
- e. There is no such algorithm

### Question 17
Increasing the stride value leads to a reduction in the output size after convolution.
- Select one answer:
  - **True**
  - False

### Question 18
How does the convolutional layer in a CNN work?
- a. All of the above
- **b. Performs a convolution operation between the input data and a set of filters.**
- c. Combines results from several neurons into one.
- d. Passes input data through an activation function.
- e. Computes the result for every possible combination of inputs.

### Question 19
What are the applications of the cost function in neural networks?
- **a. The cost function helps in the learning process of a neural network by minimizing prediction error.**
- b. The cost function is used to select the best model among various options.
- **c. The cost function is used to optimize weights in the network model.**
- d. None of the above
- **e. All of the above**

### Question 20
What is the task of convolutional layers?
- a. Significantly reducing the size of processed data
- b. Increasing the range of possible network responses
- c. Enabling work with images
- d. Summarizing relevant information
- **e. Extracting relevant information from input data**





### Topics:

#### General:
- **Neural Network Structure, Training Process, Weight Updates**
- **Optimizers** (what they are, why they are used, examples)
- **Loss Functions** (what they are, why they are used, examples)
- **Activation Functions** (what they are, why they are used, examples)
- **Basic Metrics**
- **Overfitting, Underfitting**
- **Types of Layers and Their Operation** (layers used in classes, names from the Keras library)
- **Gradient in Neural Networks**
- **Applications**

#### CNN:
- **Structure of a CNN, Key Parameters of the Conv2D Layer**
- **Basics of Autoencoders**
- **Differences Between CNN and RNN**
- **Applications**

#### RNN:
- **Structure of an RNN**
- **Structure of an LSTM Network**
- **Structure of a GRU Network**
- **Differences Between RNN, LSTM, GRU**
- **Vanishing Gradient Problem**

#### GNN:
- **Main Components, Applications**
- **Basics of GNN**
- **Message Passing**



#### Gradients:
- **CNN**: 
  - [Exploding Gradients in Neural Networks](https://machinelearningmastery.com/exploding-gradients-in-neural-networks/)
  - [The Vanishing Gradient Problem](https://towardsdatascience.com/the-vanishing-gradient-problem-69bf08b15484)
  - [A Comprehensive Guide to Convolutional Neural Networks: The ELI5 Way](https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53)

- **RNN, GRU, LSTM**: 
  - [An Introduction to Recurrent Neural Networks and the Math that Powers Them](https://machinelearningmastery.com/an-introduction-to-recurrent-neural-networks-and-the-math-that-powers-them/)
  - [Understanding GRU Networks](https://towardsdatascience.com/understanding-gru-networks-2ef37df6c9be)
  - [Understanding LSTMs](https://colah.github.io/posts/2015-08-Understanding-LSTMs/)
  - [RNN vs GRU vs LSTM](https://medium.com/analytics-vidhya/rnn-vs-gru-vs-Istm-863b0b7b1573)

- **GNN**: 
  - [A Gentle Introduction to Graph Neural Network Basics: DeepWalk and GraphSAGE](https://towardsdatascience.com/a-gentle-introduction-to-graph-neural-network-basics-deepwalk-and-graphsage-db5d540d50b3)
  - [Introduction to Graph Neural Networks](https://distill.pub/2021/gnn-intro/)

