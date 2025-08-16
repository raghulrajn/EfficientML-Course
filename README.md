# TinyML and Efficient Deep Learning Computing

This course introduces efficient AI computing techniques that enable powerful deep learning applications on resource-constrained devices. Topics include model compression, pruning, quantization, neural architecture search, distributed training, data/model parallelism, gradient compression, and on-device fine-tuning. It also introduces application-specific acceleration techniques for large language models and diffusion models.
[Link to course](https://efficientml.ai/)

## Lab 1 - Pruning
- Implement and apply fine-grained pruning
- Implement and apply channel pruning
- Performance improvement (such as speedup) from pruning
- Understand the differences and tradeoffs between these pruning approaches  
## Lab 2 - Quantization
- Understand the basic concept of **quantization**
- Implement and apply **k-means quantization**
- Implement and apply **quantization-aware training** for k-means quantization
- Implement and apply **linear quantization**
- Implement and apply **integer-only inference** for linear quantization
- Get a basic understanding of performance improvement (such as speedup) from quantization

## Lab 3 - Neural Architecture Search

[Once for All](https://arxiv.org/abs/1908.09791) (OFA), a method that can greatly reduce the cost of specialize NN architectures for different devices. OFA trains a large **super network** that contains all **sub-networks** within the design space. If we directly extract the sub-networks from the super network, they can achieve similar-level of accuracy compared with training from scratch. As such, OFA supports direct deployment with **no retrain**.
- Understand the basic concepts of NAS OFA
- Implementing Efficiency & Accuracy predictor
- Understand and implement the Random search agent depending on the peak memory and MAC
- Understand and implement the Evolutionary agent depending on the peak memory and MAC
- Tuning the hyperparameters to optimize the performance under real world contraints such as peak activation.
