# MNIST 手写数字识别：MLP 与 CNN 对比实验

## 项目简介

本项目基于 **MNIST 手写数字数据集**，分别使用 **多层感知机（MLP）** 和 **卷积神经网络（CNN）** 进行图像分类，并完成超参数调优、消融实验与结果可视化。旨在对比两种模型的性能差异，并产出可直接用于论文的图表和实验数据。

- **数据集**：MNIST（60000 训练，10000 测试）
- **任务**：10 类手写数字识别
- **最佳模型**：CNN（测试准确率 99.2%）

---

## 运行环境说明

| 工具 | 版本 / 说明 |
|------|-------------|
| Python | 3.8+ |
| PyTorch | 1.10+ |
| NumPy | 1.21+ |
| Matplotlib | 3.5+ |
| Seaborn | 0.11+ |
| Scikit-learn | 1.0+ |

**一键安装依赖**  
```bash
pip install torch torchvision numpy matplotlib seaborn scikit-learn
