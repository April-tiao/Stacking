# Stacking

本项目展示了在信用卡评估预测数据集上，使用多个机器学习模型（如 XGBoost 和 Random Forest）进行调参与集成（Stacking）的过程。最终目标是通过模型融合提升预测准确率。

## 📂 项目结构

- `stacking_model.ipynb`: 主 notebook，包含数据加载、模型构建、调参与模型融合的完整流程
- `.gitignore`: 忽略临时输出文件夹如 `catboost_info/` 和 `论文/`

## 🔧 使用的主要库

- `xgboost`
- `scikit-learn`
- `pandas`
- `matplotlib`, `seaborn`

## 📈 数据来源

使用的是 scikit-learn 内置的乳腺癌数据集 (`load_breast_cancer`)

## 🚀 快速开始

```bash
# 克隆项目
git clone git@github.com:April-tiao/stacking.git
cd stacking

# 启动 Jupyter Notebook
jupyter notebook stacking_model.ipynb