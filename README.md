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
* Numpy 1.18.1
* Matplotlib 3.1.3
* Sklearn 0.22.1
* Tensorflow 2.1.0
 
# Installation
 
If using Google Colaboratory, then no needs of installations.
 
```bash
pip install numpy
pip install matplotlib
pip install scikit-learn
pip install tensorflow
```
 
# Usage
 
Run at JupyterLab, Google Colaboratory, etc.
Needs to run from the first row.
 
# Note

参考論文arxiv: https://arxiv.org/abs/1503.02531
参考コード：瀧雅人准教授
 
# Author
 
* Ryotaro Hasegawa
* Rikkyo University
 
# License
