# FederatedLearningSecurity


## Motivation
This repository provides code to investigate the security issues of federated learning systems under the scope of various attack methods and countermeasures. We simulate the attacks using the federated learning framework, Flower. The code can be used to reproduce results and conclusions from the papers listed below, all simulated via the Flower framework.  

## Experiments
In our experiments we use the Cifar-10 and Mnist datasets. The machine learning model that we use is a convolutional neural network with a similar architecture as LeNet5. We enhance the security of our federated learning system using differential privacy, via the framework, Opacus. We ran expreriments under the scope of various attack methods, countermeasures and configurations with respect to federated learning hyperparameters.

## Quick start
In order to run the code, all you have to do is simply download and run the notebooks. The notebooks are self-explanatory and the code is modular, so it's very easy to reproduce the results and even integrate and test your own machine learning models and datasets.

## References
[1]: [Manipulating the Byzantine: Optimizing Model Poisoning Attacks and Defenses for Federated Learning](https://www.ndss-symposium.org/wp-content/uploads/ndss2021_6C-3_24498_paper.pdf)

[2]: [Data Poisoning Attacks Against Federated Learning Systems](https://arxiv.org/pdf/2007.08432.pdf)

[3]: [Inverting Gradients - How easy is it to break privacy in federated learning?](https://arxiv.org/pdf/2003.14053.pdf)

[4]: [Membership Inference Attacks Against Machine Learning Models](https://arxiv.org/pdf/1610.05820.pdf)
