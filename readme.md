# Description

Neural networks work on the principal of gradient descent by which weights are continously updated as the model trains on the data. In real life scenerios, as datasets grows large, training the data can be painfully complex. One of the methods to overcome this can be, continual learning, in which, the model tries to retain priorly learned informations while still learning the newly learned data. But the problem arises as normal gradient descent drastically modifies the weights of the priorly learned weights. Though implementation of L2 regularization helps, to some extent, but as we continue to train the model over new new datasets, the prior accuracies drops drastically. So we impelemented a technique called Elastic weight consolidation, that helps us to train the model, keeping the prior knowledge intact.

## comparison of L2 and EWC
![image](https://user-images.githubusercontent.com/76721146/156231212-004e070c-c305-441f-a325-f10b47050c0a.png)


## perfomance analysis over continous training on mnist dataset
![image](https://rylanschaeffer.github.io/content/research/elastic_weight_consolidation/ewc_mnist.png)
