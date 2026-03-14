# 数字图像处理学习笔记 📚

> 基于《Digital Image Processing》Fourth Edition (Gonzalez & Woods) 的系统学习笔记

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Book](https://img.shields.io/badge/book-Gonzalez%20%26%20Woods-green.svg)](https://www.imageprocessingplace.com/)

---

## 📖 项目简介

本仓库包含《数字图像处理》（第四版）全书12章的系统学习笔记，涵盖数字图像处理的核心理论、算法和应用。笔记采用结构化方式整理，配有大量公式、图示和实例，适合快速复习和系统学习。

**适用人群：**
- 计算机视觉/图像处理课程学生
- 准备相关考试的复习者
- 希望系统学习图像处理的开发者

---

## 📑 内容结构

全书笔记分为**6个轮次**，共**12章**内容：

| 轮次 | 章节 | 文件 | 主要内容 |
|------|------|------|----------|
| **第一轮** | 第 1-2 章 | [chapter1-2-notes.md](chapter1-2-notes.md) | 数字图像基础、图像采样与量化、像素关系 |
| **第二轮** | 第 3-4 章 | [chapter3-4-notes.md](chapter3-4-notes.md) | 灰度变换、空间滤波、频率域滤波 |
| **第三轮** | 第 5-6 章 | [chapter5-6-notes.md](chapter5-6-notes.md) | 图像复原与重建、彩色图像处理 |
| **第四轮** | 第 7-8 章 | [chapter7-8-notes.md](chapter7-8-notes.md) | 小波变换、多分辨率处理、图像压缩 |
| **第五轮** | 第 9-10 章 | [chapter9-10-notes.md](chapter9-10-notes.md) | 形态学图像处理、图像分割 |
| **第六轮** | 第 11-12 章 | [chapter11-12-notes.md](chapter11-12-notes.md) | 图像描述与表示、目标识别 |

---

## 🗂️ 章节详细目录

### 📘 第 1-2 章：数字图像基础
- 数字图像表示
- 采样与量化
- 像素之间的关系
- 图像文件格式

### 📗 第 3-4 章：核心处理方法
**第 3 章：空间域处理**
- 灰度变换（线性、对数、幂律）
- 直方图均衡化
- 空间滤波（平滑、锐化）

**第 4 章：频率域处理**
- 傅里叶变换
- 频率域滤波器（低通、高通、带阻）

### 📙 第 5-6 章：图像增强与复原
**第 5 章：图像复原**
- 噪声模型
- 空间/频率域去噪
- 维纳滤波
- 图像重建（CT 原理）

**第 6 章：彩色图像处理**
- RGB/CMYK/HSI 颜色模型
- 伪彩色处理
- 彩色变换与分割

### 📕 第 7-8 章：变换与压缩
**第 7 章：小波变换**
- 连续/离散小波变换
- Mallat 算法
- 小波包
- 多分辨率分析

**第 8 章：图像压缩**
- 无损压缩（Huffman、LZW、RLE）
- 有损压缩（JPEG、JPEG2000）
- 视频压缩基础

### 📔 第 9-10 章：形态学与分割
**第 9 章：形态学**
- 腐蚀、膨胀、开运算、闭运算
- 边界提取、细化
- 灰度形态学

**第 10 章：图像分割**
- 边缘检测（Sobel、Canny）
- 阈值分割（Otsu）
- 区域生长、分水岭算法

### 📓 第 11-12 章：描述与识别
**第 11 章：图像描述**
- 边界表示（链码、傅里叶描述子）
- 区域描述（四叉树、GLCM、矩不变量）

**第 12 章：目标识别**
- 最小距离分类器
- 贝叶斯分类器
- 支持向量机（SVM）
- 卷积神经网络（CNN）

---

## 🚀 使用指南

### 快速查阅
每份笔记都包含：
- **整体框架**：章节核心思想一览
- **知识地图**：思维导图式结构
- **公式汇总**：关键公式速查
- **概念速查表**：术语中英文对照

### 学习建议
1. **顺序学习**：按轮次1→6依次学习，构建完整知识体系
2. **专题突破**：根据需求直接跳转到相关章节
3. **公式复习**：考前重点查看各章节的"公式汇总"部分
4. **实践结合**：配合代码实践（推荐 OpenCV、scikit-image）

### 推荐学习路径

**路径 A：完整系统学习（6-8周）**
```
Week 1-2: 第1-4章（基础 + 空间/频率域处理）
Week 3-4: 第5-8章（复原 + 彩色 + 小波 + 压缩）
Week 5-6: 第9-12章（形态学 + 分割 + 描述 + 识别）
```

**路径 B：快速入门（2-3周）**
```
重点章节：3, 4, 6, 9, 10, 12
跳过：小波变换、压缩、图像描述细节
```

**路径 C：考试冲刺（1周）**
```
Day 1-2: 公式汇总 + 概念速查表
Day 3-5: 核心算法（Canny、Otsu、JPEG、CNN）
Day 6-7: 综合复习 + 知识地图梳理
```

---

## 🛠️ 实践资源

### 推荐工具
- **Python + OpenCV**：最流行的图像处理库
- **MATLAB**：教材配套，适合算法验证
- **scikit-image**：Python 科学图像处理
- **PIL/Pillow**：Python 基础图像操作

### 在线资源
- 📖 [教材官网](https://www.imageprocessingplace.com/) - Gonzalez & Woods 官方资源
- 💻 [OpenCV 文档](https://docs.opencv.org/) - 代码实现参考
- 🎓 [Coursera 图像处理课程](https://www.coursera.org/courses?query=image%20processing)

---

## 📊 笔记特色

### ✅ 结构化整理
- 每章分为多个小节，层次清晰
- 配有"整体框架"和"知识地图"
- 公式、概念、应用分类整理

### ✅ 可视化辅助
- ASCII 图示展示算法过程
- 表格对比不同方法特点
- 类比帮助理解抽象概念

### ✅ 考点突出
- 标注"最重要"、"核心"、"常考"
- 公式汇总方便考前复习
- 概念速查表中英文对照

---

## 📝 笔记示例

```markdown
### 5.8 维纳滤波（最重要！）

**核心思想：在去模糊和抑制噪声之间找平衡。**

公式：
$$\hat{F}(u,v) = \left[ \frac{1}{H(u,v)} \cdot \frac{|H(u,v)|^2}{|H(u,v)|^2 + K} \right] G(u,v)$$

其中 K = 噪声与信号功率比
- K 大 → 更注重抑制噪声
- K 小 → 更注重去模糊
```

---

## 🤝 贡献指南

欢迎提交 Issue 或 Pull Request：
- 🐛 错误修正
- 💡 内容补充
- 🎨 格式优化
- 🌐 翻译改进

---

## 📄 版权声明

- **教材版权**：《Digital Image Processing》属于 Gonzalez & Woods 及出版社
- **笔记内容**：本仓库笔记为个人学习整理，仅供学习交流使用
- **License**：本仓库采用 [MIT License](LICENSE)

---

## 🌟 Star History

如果这些笔记对你有帮助，欢迎 ⭐ Star 支持！

---

## 📮 联系方式

- **Issues**：[提交问题](https://github.com/mountionzeng/Digital-Image-Processing/issues)
- **Discussions**：[交流讨论](https://github.com/mountionzeng/Digital-Image-Processing/discussions)

---

<div align="center">

**Happy Learning! 📚✨**

Made with ❤️ by [mountionzeng](https://github.com/mountionzeng)

</div>
