# 多模态情感分析

## 运行环境

代码运行在 Python 环境下，部分重要依赖包的版本如下:

- torch==1.12.0+cu113
- torchvision==0.13.0+cu113
- wandb==0.12.21
- transformers==4.20.1

可以直接运行：

```python
pip install transformers
pip install wandb
```

## 仓库代码结构
```python
|-- picture.ipynb  # 训练图片使用的 notebook
|-- text.ipynb  # 训练文本使用的 notebook
|-- test_with_label.txt  # 预测的测试集标签
|-- test_without_label.txt  # 提供的无标签测试集文件
|-- train.txt  # 提供的有标签训练集文件
|-- requirements.txt # 相关依赖
|-- 第五次实验报告.pdf  # 本次实验的实验报告
```

## 如何运行代码
1. 在 jypyter-notebook 或者 vscode 等编辑器下打开 ipynb 文件并运行内部代码块即可。




## 参考文章

[PyTorch +ResNet34实现 图像分类 - 腾讯云开发者社区-腾讯云 (tencent.com)](https://cloud.tencent.com/developer/article/1967349)

