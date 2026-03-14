# 02 - Machine Learning 机器学习

## 📋 模块概述

机器学习是从数据中学习模式的技术。这个模块涵盖经典机器学习算法和核心概念。

## 📚 学习内容

### 梯度下降（Gradient Descent）
- 批量梯度下降（BGD）
- 随机梯度下降（SGD）
- 小批量梯度下降（Mini-batch GD）
- 动量法（Momentum）
- Adam优化器

**核心公式**：
```python
# 标准梯度下降
θ = θ - η∇L(θ)

# Adam优化器
m_t = β₁m_{t-1} + (1-β₁)∇L
v_t = β₂v_{t-1} + (1-β₂)(∇L)²
θ = θ - η·m_t/(√v_t + ε)
```

### 损失函数（Loss Functions）
- 均方误差（MSE）- 回归
- 交叉熵损失（Cross-Entropy）- 分类
- Hinge Loss - SVM
- 对比损失（Contrastive Loss）- 度量学习

**对比**：
| 损失函数 | 适用场景 | 特点 |
|---------|---------|------|
| MSE | 回归 | 对异常值敏感 |
| Cross-Entropy | 分类 | 配合softmax使用 |
| Hinge Loss | SVM | 最大间隔 |

### 正则化（Regularization）
- L1正则化（Lasso）- 稀疏性
- L2正则化（Ridge）- 防止过拟合
- Dropout
- Early Stopping
- Data Augmentation

**核心思想**：
```
L_total = L_data + λL_regularization
```

### 经典算法
- 线性回归 & 逻辑回归
- 决策树 & 随机森林
- 支持向量机（SVM）
- K近邻（KNN）
- 朴素贝叶斯

## 🎯 实战项目

### 项目列表
- [ ] 房价预测（线性回归）
- [ ] 垃圾邮件分类（朴素贝叶斯）
- [ ] 手写数字识别（KNN/SVM）
- [ ] 客户流失预测（随机森林）

## 📝 核心概念

### 过拟合 vs 欠拟合
```plaintext
欠拟合（Underfitting）：模型太简单，训练误差和测试误差都高
→ 解决方法：增加模型复杂度、添加特征

过拟合（Overfitting）：模型太复杂，训练误差低但测试误差高
→ 解决方法：正则化、Dropout、Early Stopping、更多数据
```

### 偏差-方差权衡（Bias-Variance Tradeoff）
```
Total Error = Bias² + Variance + Irreducible Error

高偏差 = 欠拟合
高方差 = 过拟合
```

## 🔗 资源

### 书籍
- 《机器学习》周志华（西瓜书）
- 《统计学习方法》李航
- 《Pattern Recognition and Machine Learning》Bishop

### 在线课程
- Andrew Ng Machine Learning (Coursera)
- Stanford CS229
- Fast.ai

### 工具库
- scikit-learn（经典ML）
- XGBoost（梯度提升）
- LightGBM（快速梯度提升）

---

**最后更新**：2026-03-14
