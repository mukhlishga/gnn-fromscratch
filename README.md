# gnn-fromscratch
Graph Neural Network (GNN) model made from scratch in python (pytorch based)

This is a project of GNN model developed from scratch in python (pytorch based). I also added the equivalent model built in pytorch geometric framework. The GNN model consists of 2 GCN hidden layers. The model implements ADAM optimizer (gradient momentum, RMS prop) and the gradient is calculated automatically using pytorch autograd. The data is scaled first with mean and standard deviation normalization. The model architecture is depicted in the following image. 

![alt text](https://github.com/mukhlishga/gnn-fromscratch/blob/main/gnn.PNG?raw=true)
