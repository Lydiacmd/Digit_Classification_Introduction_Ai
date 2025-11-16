# Classification Automatique de Chiffres Manuscrits

## 📝 Description
Projet de classification automatique de chiffres manuscrits à partir de l'image TP04.jpg. Le pipeline comprend le prétraitement de l'image, l'extraction des chiffres, leur mise à l'échelle, puis leur classification à l'aide de modèles de Machine Learning.

## 🔧 Méthodes utilisées
* **Prétraitement d'image** : niveaux de gris, inversion, binarisation, découpage, resize (28×28)
* **Descripteurs** : HOG (Histogram of Oriented Gradients)
* **Classificateurs** :
   * SVM (noyau linéaire)
   * MLP (réseau de neurones)

## 📊 Résultats
* Très bons résultats lorsque le modèle est entraîné sur les chiffres extraits du TP.
* Performances dépendantes de la qualité du prétraitement lorsqu'on applique un modèle entraîné sur MNIST.
