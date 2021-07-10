# KnowledgeDistillation
Distilling knowledge from teacher CNN to student CNN.


## basic Knowledge Distillation
single teacher to student.

loss function using KL-Divergence or Categorical Crossentropy for soft targets.

## ensemble Knowledge Distillation
multiple teachers and a single student.

will likely to be better than a single teacher. but the diversity of the multiple teachers will be ignored by the soft ensemble when it become the soft targets.
