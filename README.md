# Machine-Learning-Project-3

In this work two datasets are used, the Wisconsin Breast Cancer dataset and the Bupa Liver Disease dataset to predict if a person has a benign or malinant tumor and to predict if a person has a liver disease or not respectively. 

Datasets:

- https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)
- https://www.kaggle.com/uciml/indian-liver-patient-records

We are implementing a two layer neural network with an input layer that is equal to the number of features in each dataset. Throughout this work, a number of different references were helpful when implementing the neural network and choosing on different hidden layer nodes and the nodes of the input layer. 

The neural network implementation steps followed are as below:

1- Initialization of the network: determine the structure of the network including the number of layers, the number of nodes in each layer, the learning rate and the random weights for each layer

2- Forward pass of the network: Feeding the input through the different layers in the network and applying the appropriate activation function

3- Backward propagation: We move backwards through our network in order to update our weights as we learn about the differences between the predicted values and the output of the network

4- Update network: We then update the network as per what we learned from the backward pass

5- Test and Evaluate: We finally test how well our model is working by feeding in out test dataset


References:

- https://medium.com/coinmonks/neural-network-from-scratch-tumour-diagnosis-354abbcb2f3b
- https://towardsdatascience.com/math-neural-network-from-scratch-in-python-d6da9f29ce65
- https://machinelearningmastery.com/implement-backpropagation-algorithm-scratch-python/
