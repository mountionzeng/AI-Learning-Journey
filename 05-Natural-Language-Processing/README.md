# 05 - Natural Language Processing 自然语言处理

## 📋 模块概述

NLP是让AI理解和生成人类语言的核心技术。这个模块记录了从文本预处理到大型语言模型的完整学习路径。

## 📚 学习内容（CS 584 课程）

### Module 1-5: 基础理论
- N-gram语言模型
- 词嵌入（Word2Vec, GloVe）
- 语义向量空间

### Module 6: 神经网络与序列标注
- RNN/LSTM/GRU
- BiLSTM-CRF
- 命名实体识别（NER）
- 词性标注（POS Tagging）

**核心公式**：
```
序列标注 = BiLSTM（学特征）+ CRF（建模依赖）+ BIO标注
```

### Module 7: 深度学习架构
- CNN在NLP中的应用
- 注意力机制（Attention）
- **Transformer架构**
  - 多头自注意力
  - 位置编码
  - 编码器-解码器
- 预训练模型
  - BERT（双向编码器）
  - GPT（单向生成）

**核心公式**：
```
Attention(Q, K, V) = softmax(QK^T / √d_k)V
```

### Module 8: 统计机器翻译
- SMT核心：t* = argmax P(s|t)·P(t)
- 上下文向量
- 注意力机制在翻译中的应用

### Module 9-10: 高级主题
- 问答系统
- 对话系统
- 信息抽取

## 🎯 实战项目

### AI社交产品
**目标**：基于LLM的智能社交应用

**核心功能**：
- 智能对话
- 情感分析
- 内容推荐
- 个性化生成

**技术栈**：
- GPT/Claude API
- Transformer
- RAG（检索增强生成）

**状态**：规划中

## 📝 学习笔记

### 完整课程笔记
- [Module 6: 神经网络与序列标注](./notes/module-06-neural-networks.md)
- [Module 7: 深度学习架构](./notes/module-07-deep-learning.md)
- [Module 8: 统计机器翻译](./notes/module-08-machine-translation.md)

### 核心概念速查
- **RNN vs LSTM vs GRU**：处理序列的不同方式
- **BERT vs GPT**：双向理解 vs 单向生成
- **Attention**：让模型关注重要信息
- **Transformer**：现代NLP的基石

## 🎓 课程进度

- [x] Module 1-5: 基础理论
- [x] Module 6: 神经网络与序列标注
- [ ] Module 7: 深度学习架构（进行中）
- [ ] Module 8: 统计机器翻译（今晚学习）
- [ ] Module 9-10: 高级主题

## 🔗 资源

### 工具库
- [Hugging Face Transformers](https://huggingface.co/docs/transformers)
- [spaCy](https://spacy.io/)
- [NLTK](https://www.nltk.org/)

### 预训练模型
- BERT-base
- GPT-2/GPT-3
- RoBERTa
- BERT-Chinese

### 论文
- "Attention Is All You Need" (Transformer)
- "BERT: Pre-training of Deep Bidirectional Transformers"
- "Language Models are Few-Shot Learners" (GPT-3)

---

**最后更新**：2026-03-14  
**当前进度**：Module 7-8
