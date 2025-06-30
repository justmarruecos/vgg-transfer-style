# 🎨 Transfert de Style avec VGG19 - Deep Learning

Ce projet montre comment utiliser le **réseau VGG19 pré-entraîné** pour réaliser un **transfert de style artistique** sur une image.

---

## 📚 Objectif pédagogique

Ce notebook a été réalisé dans le cadre d’un cours de Deep Learning afin de comprendre le fonctionnement des **réseaux convolutifs (CNN)**, des **couches de convolution**, et comment on peut utiliser des réseaux pré-entraînés pour des applications créatives comme le style transfer.

---

## 🧠 Modèle utilisé

Le modèle utilisé est :
- `VGG19` de Keras, pré-entraîné sur ImageNet.
- On extrait les couches nécessaires pour capter :
  - Le **contenu** de l’image source
  - Le **style** de l’image artistique

---

## 🛠️ Technologies & Librairies

- Python 3.x
- TensorFlow / Keras
- NumPy
- Matplotlib
- PIL (Python Imaging Library)

---

## 📂 Contenu du Notebook

- Chargement et prétraitement des images
- Construction du modèle avec VGG19
- Calcul des pertes de contenu et de style
- Optimisation du rendu final
- Affichage des résultats

---
