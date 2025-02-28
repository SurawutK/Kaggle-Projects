# Research Paper Classification

## Description

In the world of academic research, the categorization and classification of literature play a vital role in literary work. To ensure that the scholarly pieces are discoverable, accessible, and essentially relevant to their audience, the classification of literature requires to be proposed with precision and robustness. With databases like Scopus housing millions of articles, achieving high effectiveness and accuracy via human interpretation is much more challenging and labour-intensive. One of the promising solutions is multi-label text classification.

This project aims to multi-label classify multi-content text on the limited Scopus dataset into 18 subject areas of engineering: civil, environmental, biomedical, petroleum, metallurgical, mechanical, electrical, computer, optical, nano, chemical, materials, agricultural, education, industrial, safety, "mathematics and statistics", and material science.

The provided data comprises the papers' abstracts, titles, and labels.

## Evaluation

The evaluation matrix for public and private ranking is macro f1-score, which is described as follows:
F1macro=1N∑i=1NF1i
Where N is the number of classes.
For each class, treat it as the positive class and group all the other classes as the negative class. Calculate the F1-score for this binary classification.
F1i=2×Precisioni×RecalliPrecisioni+Recalli
Precision - The ratio of correctly predicted positive observations to the total predicted positives.
Precisioni=TPiTPi+FPi
Recall (or Sensitivity or True Positive Rate) - The ratio of correctly predicted positive observations to all the actual positives.
Recalli=TPiTPi+FNi
