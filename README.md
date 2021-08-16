# KnowledgeDistillation
 
Distilling knowledge from teacher CNN to student CNN.

![kd_figure2](https://user-images.githubusercontent.com/65751048/129522599-0a34fcbc-1a21-4a62-ba16-98f60f346da8.png)
 
## basic Knowledge Distillation
single teacher to student.

loss function using KL-Divergence or Categorical Crossentropy for soft targets.

The accuracy/loss of distilled student CNN will be closer to the Teacher CNN.

## ensemble Knowledge Distillation
multiple teachers and a single student.

will likely to be better than a single teacher. However the diversity of the multiple teachers will be ignored by the soft ensemble when it becomes the soft targets.

 
# Requirement
 
* Python 3.7.6
* tensorflow 2.1.0
 
# Installation
 
Requirementで列挙したライブラリなどのインストール方法を説明する
 
```bash
pip install --upgrade tensorflow
```
 
# Usage
 
DEMOの実行方法など、"hoge"の基本的な使い方を説明する
 
```bash
git clone https://github.com/hoge/~
cd examples
python demo.py
```
 
# Note

参考論文arxiv: https://arxiv.org/abs/1503.02531
 
# Author
 
作成情報を列挙する
 
* Ryotaro Hasegawa
* Rikkyo University
 
# License
