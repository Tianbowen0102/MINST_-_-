# MNIST 手写数字识别：MLP 与 CNN 对比实验

## 项目简介

本项目基于 **MNIST 手写数字数据集**，分别使用 **多层感知机（MLP）** 和 **卷积神经网络（CNN）** 进行图像分类，并完成超参数调优、消融实验与结果可视化。旨在对比两种模型的性能差异，并产出可直接用于论文的图表和实验数据。

- **数据集**：MNIST（60000 训练，10000 测试）
- **任务**：10 类手写数字识别
- **最佳模型**：CNN（测试准确率 98.60%）

---

## 运行环境说明
| 工具 | 版本/说明 |
|------|-----------|
|Python| 3.6.4|
| OS: Linux|4.14.105-19-0024|
|Processor| x86_64|
|PyTorch | 1.1.0|
| NumPy | 1.16.3|
|Matplotlib | 3.1.2|
|Seaborn | 0.9.0|
|Scikit-learn | 0.21.1 |
---
## 项目HTML链接(可用htmlpreview.github.io打开)
  #### https://raw.githubusercontent.com/Tianbowen0102/MINST_-_-/refs/heads/main/MINST_%E6%89%8B%E5%86%99%E6%95%B0%E5%AD%97%E8%AF%86%E5%88%AB_%E5%AE%8C%E6%95%B4%E9%A1%B9%E7%9B%AE.html
---
## 和鲸社区项目链接
  #### https://www.heywhale.com/mw/project/69c79f3e1b11dd7cda7c6a0b
---
## 项目截图
* 训练曲线对比
  #### https://cdn.kesci.com/upload/rt/4E364D37E9F44757A40E5F2EA9AAFE80/tclznk1pfj.png
* 混淆矩阵（测试集）
  #### https://cdn.kesci.com/upload/rt/4827A859479B42A38223BB497FA229A4/tcm32f55ai.png
* 错误样本分析
  #### https://cdn.kesci.com/upload/rt/D1FA079B7546435B8B439559C34093C8/tcm33mn2y8.png
**一键安装依赖**  
```bash
pip install torch torchvision numpy matplotlib seaborn scikit-learn
