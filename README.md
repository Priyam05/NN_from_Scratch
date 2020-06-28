# NN_from_Scratch
Here, we implement backpropagation code, and training Neural Networks. The goals of this assignment are as follows:

- understand **Neural Networks** and how they are arranged in layered
  architectures
- understand and be able to implement (vectorized) **backpropagation**
- implement various **update rules** used to optimize Neural Networks
- implement **batch normalization** for training deep networks
- implement **dropout** to regularize networks
- effectively **cross-validate** and find the best hyperparameters for Neural
  Network architecture



## Important Files

**FullyConnectedNets.ipynb** : Here, we use modular layer design, and use those layers to implement fully-connected networks of arbitrary depth. To optimize these models we implement several popular update rules.

**Batch Normalization**
We implement batch normalization from scratch, and use it to train deep fully-connected networks.

![BatchNorm](/Images/BN1.PNG)

![BatchNorm](/Images/BN2.PNG)

*Computation graph with Batch Normalization*
![BatchNorm](/Images/BN_bp.PNG)

**Dropout**
We implement Dropout and explore its effects on model generalization.
![BatchNorm](/Images/Dropout.PNG)
