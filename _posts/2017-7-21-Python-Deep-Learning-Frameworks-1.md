---
published: false
title: Python Deep Learning Frameworks (1)
categories: [Deep Learning, Nervana Neon, Python, PyTorch, TensorFlow]
---
![deep learning](/assets/images/deep_learning.jpeg?raw=true)

## Introduction
What I can say about **Deep Learning (DL)** that hasn't been said a thousand times already? It's powerful, it's state-of-the-art, and it's here to stay. But you already knew that. So instead of polluting the interwebs with yet another theoretical post about DL, I'm going to focus on the application side of things. Specifically, through a series of upcoming posts, I'll look at three of the most promising python DL frameworks (Intel Nervana's Neon, PyTorch, and TensorFlow) and assess them on a number of dimensions, including: 
1. How easy are they to setup?
2. How useful is the documentation?
3. How helpful and useful are the tutorials?
4. What is the learning curve like?
5. Are there performance differences between the frameworks, and if so what magnitude?

I'll wrap up the series with a full buildout in each framework of a deep reinforcment learning project. But more on that later.

Let's begin with a brief introduction to each framework.

## Intel Nervana's Neon (version 2.0.0)
![neon](/assets/images/nervana_neon.png?raw=true){: .center-image }

According to [Intel Nervana's website](http://neon.nervanasys.com/docs/latest/index.html):
>neon is Intel Nervana‘s reference deep learning framework committed to best performance on all hardware. Designed for ease-of-use and extensibility.
>
>Features include:
>- Support for commonly used models including convnets, RNNs, LSTMs, and autoencoders. You can find many pre-trained implementations of these in our model zoo
>- Tight integration with our state-of-the-art GPU kernel library
>- 3s/macrobatch (3072 images) on AlexNet on Titan X (Full run on 1 GPU ~ 32 hrs)
>- Basic automatic differentiation support
>- Framework for visualization
>- Swappable hardware backends: write code once and deploy on CPUs, GPUs, or Nervana hardware


## PyTorch (version 0.1.12)
![pytorch](/assets/images/pytorch.png?raw=true){: .center-image }

According to [PyTorch's website](http://pytorch.org/about/):
>PyTorch is a python package that provides two high-level features:  
>- Tensor computation (like numpy) with strong GPU acceleration  
>- Deep Neural Networks built on a tape-based autograd system
>
>You can reuse your favorite python packages such as numpy, scipy and Cython to extend PyTorch when needed.
>
>At a granular level, PyTorch is a library that consists of the following components:  
>- **torch**	a Tensor library like NumPy, with strong GPU support  
>- **torch.autograd**	a tape based automatic differentiation library that supports all differentiable Tensor operations in torch  
>- **torch.nn**	a neural networks library deeply integrated with autograd designed for maximum flexibility  
>- **torch.optim**	an optimization package to be used with torch.nn with standard optimization methods such as SGD, RMSProp, LBFGS, Adam etc.  
>- **torch.multiprocessing**	python multiprocessing with magical memory sharing of torch Tensors across processes; useful for data loading and hogwild training    
>- **torch.utils**	DataLoader, Trainer and other utility functions for convenience  
>- **torch.legacy(.nn/.optim)**	legacy code that has been ported over from torch for backward compatibility reasons

## TensorFlow (version 1.2)
![tensorflow](/assets/images/tensorflow.jpeg?raw=true){: .center-image }

According to the [TensorFlow's website](https://www.tensorflow.org/):
>TensorFlow is an open source software library for numerical computation using data flow graphs. Nodes in the graph represent mathematical operations, while the graph edges represent the multidimensional data arrays (tensors) communicated between them. The flexible architecture allows you to deploy computation to one or more CPUs or GPUs in a desktop, server, or mobile device with a single API. TensorFlow was originally developed by researchers and engineers working on the Google Brain Team within Google's Machine Intelligence research organization for the purposes of conducting machine learning and deep neural networks research, but the system is general enough to be applicable in a wide variety of other domains as well.

## Summary
Three of the most promising python DL frameworks were introduced. In no particular order, they are Intel Nervana's Neon, PyTorch, and TensorFlow.

## Next Time
Next time I'll walk you through the installation process of each framework so stay tuned.

## References
[What is Deep Learning?](https://www.oreilly.com/ideas/what-is-deep-learning)  
[ML vs DL vs AI](https://www.datanami.com/2017/05/10/machine-learning-deep-learning-ai-whats-difference/)  
[Deep Learning Book](http://www.deeplearningbook.org/)
