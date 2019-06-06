# 神经网络语言模型中的Softmax专题
---
#### 1. 由二分类说起
逻辑回归
sigmoid

#### 2. 神经网络语言模型和交叉熵

#### 3. softmax

- Hierarchical Softmax
- sampled softmax [On Using Very Large Target Vocabulary for Neural Machine Translation](https://arxiv.org/pdf/1412.2007.pdf)
- Tied Softmax
- Differentiated Softmax [Strategies for Training Large Vocabulary Neural Language Models](http://arxiv.org/abs/1512.04906)
- CNN Softmax
- Adaptive Softmax -- [Efficient softmax approximation for GPUs](https://arxiv.org/abs/1609.04309) -- [code](https://github.com/facebookresearch/adaptive-softmax)
- SVD Softmax -- [SVD-Softmax: Fast Softmax Approximation on Large Vocabulary Neural Networks](https://papers.nips.cc/paper/7130-svd-softmax-fast-softmax-approximation-on-large-vocabulary-neural-networks) -- [code](https://github.com/koichiro11/svd-softmax)
- LSH Softmax [LSH Softmax: Sub-Linear Learning and Inference of the Softmax Layer in Deep Architectures](https://openreview.net/forum?id=SJ3dBGZ0Z)
- Noise Contrastive Estimation
- Importance Sampling
- Adaptive Importance Sampling
- Target Sampling 
- Negative Sampling
- Self-Normalisation

    分层 softmax（hierarchical softmax）
    噪声对比估计（noise contrastive estimation）
    差分 softmax（differentiated softmax）
    CNN-Softmax
    自适应 softmax（adaptive softmax）

    hierarchical softmax
    adaptive softmax
    svd softmax
    lsh softmax
    log softmax
    Sigsoftmax
    gated softmax

#### 参考

[softmax](https://talbaumel.github.io/blog/softmax/)

[HierarchicalSoftmax](https://github.com/RobGrimm/HierarchicalSoftmax)

[hs-semantic-tree](https://github.com/lateral/hs-semantic-tree)

[Hierarchical Softmax as output activation function in Neural Network](https://becominghuman.ai/hierarchical-softmax-as-output-activation-function-in-neural-network-1d19089c4f49)

[词嵌入系列博客Part1：基于语言建模的词嵌入模型](https://www.jiqizhixin.com/articles/2016-10-23-2)

[词嵌入系列博客Part2：比较语言建模中近似 softmax 的几种方法](https://www.jiqizhixin.com/articles/2016-10-26)