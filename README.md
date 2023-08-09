# Alternate Loss Functions

All machine learning algorithms use a loss, cost, utility, or reward function to encode the learning objective and oversee the learning process. This function that supervises learning is a frequently unrecognized hyperparameter that determines how incorrect outputs are penalized and can be tuned to improve performance. Our [paper](https://arxiv.org/pdf/2303.09935.pdf) shows that the training speed and final accuracy of neural networks can significantly depend on the loss function used to train neural networks. In particular derivative values can be significantly different with different loss functions leading to significantly different performance after gradient descent-based Backpropagation (BP) training. This paper explores the effect on the performance of new loss functions that are more "liberal" or "strict" compared to the popular Cross-entropy loss in penalizing incorrect outputs. Eight new loss functions are proposed and a comparison of performance with different loss functions is presented. The new loss functions presented in this paper are shown to outperform Cross-entropy loss on computer vision and NLP benchmarks.

Paper URL: https://arxiv.org/pdf/2303.09935.pdf

Loss functions are implemented in the given Notebooks.
