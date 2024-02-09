Predictive Analysis of Oxygen Levels in Epithelial Cell Lines
This project aims to leverage machine learning techniques to gain insights into the behavior of epithelial cell lines under different oxygen levels.
By analyzing single-cell RNA sequencing data, we seek to develop predictive models that can accurately classify cells into hypoxia and normoxia categories.
The findings from this study can contribute to our understanding of cellular responses to environmental conditions and may have implications in cancer research
and treatment strategies.

Project Overview
In this project, we conducted predictive analysis of oxygen levels in epithelial cell lines, specifically MCF7 and HCC1806 cancer cell lines. 
The data used in this study was obtained from four different experiments on these cell lines, which were isolated from patients with metastatic adenocarcinoma.
Each cell line was sequenced using two different single-cell RNA sequencing techniques: SMARTseq and DROPseq. 
The objective of this study is to understand the behavior of cells under certain environmental conditions, particularly in predicting different levels of oxygen 
the cells are exposed to. The oxygen levels considered include hypoxia (low oxygen) and normoxia (normal oxygen). 
To achieve this, various machine learning methods will be applied to the data.

Dataset
The dataset used in this project includes data obtained from single-cell RNA sequencing experiments on MCF7 and HCC1806 cell lines. 
The data comprises the associated metadata of each cell line, Filtered and Normalized versions of both MCF7 and HCC1806 data in each cell sequencing technique. 
The data also includes information on oxygen levels (hypoxia or normoxia) and experimental conditions.

Machine Learning Techniques
Data Preprocessing: Data cleaning, normalization, and feature engineering techniques will be applied to prepare the data for analysis.
Unsupervised Learning: Methods such as Principal Component Analysis (PCA), t-distributed Stochastic Neighbor Embedding (t-SNE), Isometric Mapping (IsoMap), 
and clustering algorithms will be used to explore the structure of the data and identify patterns.
Supervised Learning: Various supervised learning algorithms, including multinomial naive Bayes, decision trees, random forests, Support Vector Machine (SVM), 
logistic regression, and neural networks, will be employed to build predictive models for oxygen levels in epithelial cell lines.

Model Performance
The performance of each machine learning model will be evaluated based on metrics such as accuracy, precision, recall, and F1-score.
The neural network classifier will be optimized to achieve the highest accuracy in predicting oxygen levels.

