# MNIST 手写数字识别：MLP 与 CNN 对比实验

## 项目简介

本项目基于 **MNIST 手写数字数据集**，分别使用 **多层感知机（MLP）** 和 **卷积神经网络（CNN）** 进行图像分类，并完成超参数调优、消融实验与结果可视化。旨在对比两种模型的性能差异，并产出可直接用于论文的图表和实验数据。

- **数据集**：MNIST（60000 训练，10000 测试）
- **任务**：10 类手写数字识别
- **最佳模型**：CNN（测试准确率 98.60%）

---

## 运行环境说明

* Python Version: 3.6.4
* OS: Linux 4.14.105-19-0024
* Processor: x86_64
* PyTorch Version: 1.1.0
* NumPy Version: 1.16.3
* Matplotlib Version: 3.1.2
* Seaborn Version: 0.9.0
* Scikit-learn Version: 0.21.1

**一键安装依赖**  
```bash
pip install torch torchvision numpy matplotlib seaborn scikit-learn
