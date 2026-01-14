# Simple_knn_on_digits

Ce dépôt présente une étude complète de classification de chiffres manuscrits à partir du dataset Digits de scikit-learn, en utilisant l’algorithme K-Nearest Neighbors (KNN), avec et sans réduction de dimension par PCA.

L’objectif est de comparer les performances, la complexité et le temps d’inférence des deux approches.

## Contenu du dépôt

Le dépôt contient deux notebooks Jupyter :

### knn_on_digits.ipynb
Classification des chiffres manuscrits avec KNN.

Ce notebook comprend :

- analyse exploratoire du dataset (format, visualisation, répartition des classes)
- séparation claire des données en entraînement / test / validation
- recherche du meilleur hyperparamètre k
- évaluation des performances (accuracy, matrice de confusion)
- analyse du sur-apprentissage

### knn_pca_on_digits.ipynb
Classification des chiffres manuscrits avec PCA + KNN.

Ce notebook inclut :

- application de la PCA pour la réduction de dimension
- étude de la variance expliquée/cumulée 
- choix du nombre de composantes
- reconstruction des images après PCA
- classification avec KNN sur les données projetées
- comparaison des performances avec et sans PCA
- matrices de confusion
- comparaison du temps d’inférence et de l’accuracy
