---
layout: default
title: Artificial Neural Network
description: Short Note for Easy Understanding of Artificial Neural Network.
---

ANN is a computation model that mimics the human brain and is composed of an ***input layer, one or more hidden layers, and an output layer***. 
The input layer accepts ***input information***, the hidden layer ***performs calculations to find features and patterns*** and the output layer ***displays the output***. 
Each node (or ***neuron***) connects to the nodes of the next layer and has an associated ***weight*** and ***bias***. If the output of any node is above the specified ***threshold*** value after applying ***activation function*** that node is ***activated or fired***, sending data to the next layer of the network.  
Neural networks reflect the behavior of the human brain, allowing computer programs to recognize patterns and relationships between vast amounts of data.


*: Diagramatic representation of NN*

### Disadvantages:
- ***No Assurance of proper network structure:*** There is no particular structure of ANN. The network structure has to be accomplished through experience, trial and error.
- ***Unrecognized behavior of the network:*** When ANN does not provide insight about why and how the solution is reached. This condition is also known as ***Black Box***.


Neural networks rely on training data to learn and improve their accuracy.
Each individual node is a linear regression model, composed of input data, weights, a bias (or threshold), and an output. The formula is:



*: Formula for Linear regression for each node*

*: Activation function f(x)*

These weights determine the importance of any given variable, with larger ones contributing more significantly to the output.

The output is passed through an ***activation function***. If that output exceeds a given threshold, it “fires” (or activates) the node, passing data to the next layer in the network. This results in the output of one node becoming the input of the next node. This process of passing data from one layer to the next layer defines this neural network as a ***feedforward network***.

[Go to Home Page](https://nivirocks.github.io/)

### References:
- [What are Neural Networks? by IBM Cloud Learn Hub](https://www.ibm.com/in-en/cloud/learn/neural-networks)
- 
