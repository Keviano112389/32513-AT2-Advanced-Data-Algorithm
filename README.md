# 32513-AT2-Advanced-Data-Algorithm
Advanced Data Algorithm Assignment 2

Implement a Machine Learning Model and Test the Training Algorithm on Data
Introduction
The goal of this assignment is to develop your hands-on skills in performing learning from data, as well as further understanding of the practical technical details of the learning procedure.

You will implement a simple machine learning algorithm from scratch, for example, the ID3 decision tree building algorithm or the perceptron training algorithm or an ensemble method. You can also implement another algorithm of your interest to solve the supervised learning problem. The algorithm needs to be tested using a simple but practical dataset and under an appropriate learning framework as instructed in the course. The task also includes a report of your reflection on the development, the testing scheme and the results.

Alternatively, unsupervised learning algorithms can also be considered, but you must specify the testing scheme and the criteria clearly in the report (see below) if you choose to implement an unsupervised learning algorithm.

Specification
Implementation from scratch: The implementation should include detailed computational steps of an algorithm. We do NOT consider straightforward usage of the off-the-shelf toolboxes as implementing the algorithm details. For example, if you choose to build a decision tree, the implementation of the tree-building algorithm should address the construction of the tree structure, the computation of splitting data (a subset of the training dataset) at a tree node to create the children nodes -- in ID3, this is to compute the information gain and the entropy and decide the split accordingly. However, it is allowed to use basic auxiliary tools such as the libraries to perform matrix or linear algebra operations, to facilitate loading and parsing the data files, etc.

Practical dataset: The dataset contains sufficient samples to represent practical relationships between the attributes and the target to be predicted. Typical examples include the Iris flower dataset, the image dataset of hand-written digits, or other examples that have been used in the tutorial demos. Manually crafted toy datasets are not recommended.

Learning framework and test scheme: A proper training and validation scheme must be set up for the test of the implementation. More sophisticated evaluation schemes are also welcomed. For formal and detailed information of the learning framework, refer to the related sections in course materials.
