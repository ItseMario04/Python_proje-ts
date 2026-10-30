# Dimensionality reduction, clustering and classification of text data

Machine learning (ML) models were trained using the [Materials and their Mechanical Properties](https://www.kaggle.com/datasets/purushottamnawale/materials) dataset obtained from the Autodesk Material Library. Following standard data cleaning and exploratory data analysis (EDA), a "clean" data table was obtained, which can be found in the [previous task]().

This file contains solutions to three tasks:

- Dimensionality Reduction and Data Visualization;
- Cluster analysis;
- Processing and classification of text data;

For the first task: "Use `sklearn.decomposition.PCA` to reduce the dimensionality of the data. Train one of the classification algorithms from Lab 1 on the resulting data and compare the classification results "before" and "after" applying PCA.
Draw conclusions regarding: how PCA affected classification performance; the extent to which the number of features was reduced; and whether the model training time changed.
For the same dataset, use `sklearn.manifold.TSNE` to reduce the dimensionality to 2D. Visualize the resulting data, using colors to represent the classes, and explain the outcome."

For the second task: "Do not use class labels (targets) during clustering.
Perform data clustering using the K-Means algorithm. Determine an appropriate number of clusters using the Elbow Method and/or the Silhouette Score. Visualize the resulting clusters in 2D using PCA or t-SNE. After clustering, compare the obtained clusters with the actual classes in the dataset. Draw a conclusion: does the identified cluster structure correspond to the actual classes?
If the dataset contains a large number of classes, you may simplify the analysis by retaining only 2–3 classes, provided you justify your choice.
Important: a cluster and a class are not the same thing. K-Means is not necessarily expected to perfectly reproduce the original classes of the dataset. You must analyze and explain the results obtained."

For the third task: "Load a text dataset containing class labels. Perform text preprocessing (e.g., removing stop words and punctuation). Use WordCloud to visualize the most characteristic words or phrases for each class and explain the results. Vectorize the texts—for instance, using `sklearn.feature_extraction.text.TfidfVectorizer`.
Train a text classification model and evaluate its performance using appropriate metrics."
