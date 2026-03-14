# 03 - Deep Learning 深度学习

## 📋 模块概述

深度学习是现代AI的核心技术。这个模块涵盖从基础神经网络到最新架构（Transformer、Diffusion Models）的完整学习路径。

## 📚 学习内容

### 神经网络基础
- 前馈神经网络（FFNN）
- 反向传播算法
- 激活函数（ReLU, Sigmoid, Softmax）
- 优化器（SGD, Adam, AdamW）

### 卷积神经网络（CNN）
- 卷积层与池化层
- 经典架构：LeNet, AlexNet, VGG, ResNet
- CNN在图像和文本中的应用

### 循环神经网络（RNN）
- RNN基础
- LSTM/GRU
- BiLSTM
- 梯度消失与梯度爆炸

### Transformer
- 自注意力机制
- 多头注意力
- 位置编码
- 编码器-解码器架构

**核心公式**：
```python
# 自注意力
Attention(Q, K, V) = softmax(QK^T / √d_k)V

# 多头注意力
MultiHead(Q,K,V) = Concat(head₁,...,headₕ)W^O
where headᵢ = Attention(QWᵢ^Q, KWᵢ^K, VWᵢ^V)
```

### 扩散模型（Diffusion Models）
- DDPM（去噪扩散概率模型）
- Stable Diffusion架构
- ControlNet
- LoRA微调

## 🎯 实战项目

### 项目列表
- [ ] 手写数字识别（MNIST）
- [ ] 图像分类（CIFAR-10）
- [ ] 文本情感分析
- [ ] 图像生成（Stable Diffusion微调）
- [ ] 对话系统（基于Transformer）

## 📝 核心概念速查

### 神经网络组件
| 组件 | 作用 | 常用选择 |
|------|------|----------|
| 激活函数 | 引入非线性 | ReLU（隐藏层）、Softmax（输出层） |
| 优化器 | 更新参数 | Adam、AdamW |
| 损失函数 | 衡量误差 | CrossEntropy（分类）、MSE（回归） |
| 正则化 | 防止过拟合 | Dropout、L2正则化 |

### 架构对比
| 架构 | 优势 | 适用场景 |
|------|------|----------|
| CNN | 局部特征提取 | 图像处理、文本分类 |
| RNN/LSTM | 序列建模 | 时间序列、NLP |
| Transformer | 并行计算、长距离依赖 | NLP、多模态 |
| Diffusion | 高质量生成 | 图像生成、视频生成 |

## 🔗 资源

### 框架
- [PyTorch](https://pytorch.org/)
- [TensorFlow](https://www.tensorflow.org/)
- [JAX](https://github.com/google/jax)

### 学习资源
- [Deep Learning Book (Goodfellow)](https://www.deeplearningbook.org/)
- [Stanford CS231n](http://cs231n.stanford.edu/)
- [Fast.ai](https://www.fast.ai/)

### 论文
- "ImageNet Classification with Deep CNNs" (AlexNet)
- "Deep Residual Learning" (ResNet)
- "Attention Is All You Need" (Transformer)
- "Denoising Diffusion Probabilistic Models" (DDPM)

---

**最后更新**：2026-03-14
