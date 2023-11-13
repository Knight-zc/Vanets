# 基于机器学习的事故预测 Machine Learning based Accident Prediction

## 项目简介 Project Introduction

该仓库包含使用Python编写的实验代码，旨在支持《车联网中机器学习辅助的紧急消息信任评估方案》论文的研究。主要任务包括对数据结构进行分析、构建机器学习模型，并最终将最优模型与声望机制相结合，以在VANETs中取得出色的性能表现。This project is the experimental code of the paper "Machine learning-assisted trust evaluation scheme for emergency messages in VANETs", which is written in Python, compares a series of machine learning models, and integrates the best model with proposed Reputation Mechanism to gain better performance in VANETs.

## 文件简介 File description

1. `uk_accident_pred.ipynb`: 导入、分析、预处理数据集。Import, analyze, and preprocess the collected data set.

2. `resampling.ipynb`: 基于原始数据集重新采样数据，以支撑后续模型训练。Resample data based on the original data set to support subsequent model training.

3. `model_train.ipynb`: 机器学习模型训练代码。Machine learning model training code.

4. `paper_experiment.ipynb`: 机器学习模型与声望机制结合验证代码。Verify code by combining machine learning model and reputation mechanism.

## 使用方法 Instructions

**环境设置：** 在运行代码之前，请确保已安装必要的Python环境和依赖项。

**Environment Setup:** Before running the code, make sure you have the necessary Python environment and dependencies installed.

```bash
pip install -r requirements.txt
```

---

**免责声明：** 该项目是为了研究和学术目的而创建的，不对任何使用此代码的后果负责。

**Disclaimer:** This project was created for research and academic purposes and we are not responsible for any consequences of using this code.