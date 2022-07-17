# TP Machine Learning avec Keras/Tensorflow

<img src='./figures/CC-BY-SA.jpeg' width=100 style="vertical-align:middle; float:left"> &emsp; jean-luc.charles@ensam.eu 

### Versions

| version | date | commentaire |
| --- | --- | --- | 
| v1.0 | 2019-07-02 | Version initiale / Réseau dense |
| v1.0 | 2019-07-02 | Consolidation des versions keras=2.2.4, tensorflow=1.13.1, numpy=16.1  |  
| v2.0 | 2022-07-17 | Tensorflow 2  |  

Ce TP est utilisé pour les séances d'Informatique des étudiants de 2me année du Bachelor de technologie de l'ENSAM de Talence.

Les activités présentées sont initialement inspirées du travail de Jason Brownlee : Handwritten Digit Recognition using Convolutional Neural Networks in Python with Keras publié en juin 2016 à l'adresse https://machinelearningmastery.com/handwritten-digit-recognition-using-convolutional-neural-networks-python-keras/

## Programmation/entraînement/évaluation d'un réseau de neurones dédié à la reconnaissance de chiffres manuscrits.

Cette activité propose la découverte de la programmation, de l'entraînement et de l'évaluation d'un réseau de neurones dédié à la reconnaissance de chiffres écrits à la main.

Les principaux points abordés dans ce TP sont :
- neurone artificiel,
- réseau de neurones,
- fonction d'activation,
- construction d'un réseau de neurones dense en Python avec tensorFlow/keras,
- téléchargement et visualisation des images MNIST (banque d'images de chiffres manuscrits),
- préparation des données (images) pour entraÎner le réseau de neurones,
- entraînement du réseau,
- courbes de précision et de perte du réseau,
- exploitation du réseau avec des chiffres manuscrits personnalisés.

# Cahiers IPython proposés

Deux *cahiers IPython* (aka *Jupyter notebook*) sont proposés :
- `TP_MNIS_Keras_dense.ipynb` : le cahier *à trous* pour travailler avec un simple réseau dense,
- `TP_MNIS_Keras_dense-soluce.ipynb` : le cahier complet avec toutes les réponses.

# Acquis d'apprentissage

À l'issue de cette activité, vous saurez :
- télécharger les images de la banque MNIST avec le module Python Keras.
- construire/évaluer avec le module tensorflow/keras un réseau de neurone dense dédié à la reconnaissance des images MNIST, 
- utiliser vos propres images de chiffres pour évaluer les réponse d'un réseau entraîné avec la banque d'images du MNIST.

## Autres ressources

- répertoire `figures` : contient les figures (ou les sources pour produire les figures) utilisées dans les cahiers IPython,
- répertoire `chiffres` : contient des images représentant des chiffres écrits à la main, hors banque MNIST.
- répertoire `util_python` : contient des programmes Python utiles...<br/>
		`activFunctions.py` : trace les figures de quelques fonctions d'activation couramment utilisées.

