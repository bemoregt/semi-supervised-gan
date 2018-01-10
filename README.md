## PyTorch implemenation of the Generative Adversarial Network for semi-supervised learning
This is an implementation of a simple [Generative Adversarial Network](https://arxiv.org/abs/1406.2661) for semi-supervised learning on [PyTorch](http://pytorch.org/). Originally I studied the subject by [Udacity Deep Learning Foundation Nanodegree](https://www.udacity.com/course/deep-learning-nanodegree-foundation--nd101), but [the original implementation on TensorFlow](https://github.com/udacity/deep-learning/tree/master/semi-supervised) was a bit wierd for me. PyTorch provides more clear way to implement such a network. I achieved the accuracy of 70% on the test data set after training for 80 epochs. This accuracy corresponds to that one achieved by the TensorFlow implementation.  
This implementation is only an entry point and definitely could and should be improved to get the much better accuracy. It is partially inspired by [this work](https://github.com/yunjey/mnist-svhn-transfer).  
In the repository you can find the data loader, model and solver separated in different Python files and a Jupyter notebook that contains all-in-one if you want to try things faster.  