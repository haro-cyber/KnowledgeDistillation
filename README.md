
# KnowledgeDistillation
Distilling knowledge from teacher CNN to student CNN.


![knowledge-distill](https://user-images.githubusercontent.com/65751048/125156794-50b62d00-e1a2-11eb-88c8-8398a863f600.png)

参考論文arxiv: https://arxiv.org/abs/1503.02531

## basic Knowledge Distillation
single teacher to student.

loss function using KL-Divergence or Categorical Crossentropy for soft targets.

## ensemble Knowledge Distillation
multiple teachers and a single student.

will likely to be better than a single teacher. but the diversity of the multiple teachers will be ignored by the soft ensemble when it become the soft targets.

