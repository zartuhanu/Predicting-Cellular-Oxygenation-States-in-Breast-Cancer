Hypoxia, low oxygen availability, is a key feature of tumor biology, driving cancer cells toward more aggressive, treatment-resistant behavior. Being able to identify whether a cell is in hypoxic or normoxic conditions is therefore essential for understanding cancer progression.

In this project, we aimed to predict whether breast cancer cells are in hypoxic or normoxic conditions using single-cell RNA sequencing data. We worked with two cell lines (MCF7 and HCC1806) and two sequencing technologies (DropSeq and SmartSeq).

Our workflow began with data exploration and preprocessing, where we examined the structure of each dataset and prepared the gene-expression matrices for analysis. We then applied unsupervised learning techniques, including PCA and clustering, to uncover natural groupings and understand variability across cell lines and oxygen conditions.

After exploring the data structure, we moved to supervised learning, training multiple classification models, including logistic regression, SVM, random forest, KNN, decision trees, and Naive Bayes, to identify patterns that distinguish hypoxia from normoxia. Each model was trained and evaluated separately for every dataset to compare performance across technologies and cell lines.

IMPORTANT NOTE: Because the datasets we used were restricted and not permitted for external sharing, all raw data files and identifiable cell-level outputs have been removed. However, the interpretations of our findings, as well as the results from both the supervised and unsupervised learning analyses, were retained, since they do not reveal any sensitive or proprietary information about the original datasets.
