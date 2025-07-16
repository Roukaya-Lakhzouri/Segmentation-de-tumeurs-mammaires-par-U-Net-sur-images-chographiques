# Segmentation-de-tumeurs-mammaires-par-U-Net-sur-images-chographiques
Ce projet a pour objectif de segmenter les images échographiques du sein pour identifier automatiquement les zones cancéreuses. Il utilise un modèle de deep learning basé sur l'architecture **U-Net**, spécialement conçue pour la **segmentation sémantique** d’images médicales.

---

## 📌 Objectif

- Détecter les régions cancéreuses dans des images échographiques du sein.
- Générer une **image binaire** en sortie où :
  - les **zones cancéreuses** sont en **blanc**
  - les **zones saines** sont en **noir**

---

## 🧠 Modèle utilisé : U-Net

- U-Net est une architecture de réseau de neurones convolutionnels conçue pour la **segmentation pixel par pixel**.
- Initialement développée pour l’imagerie biomédicale, elle est reconnue pour sa capacité à produire des résultats précis même avec un jeu de données limité.

**Caractéristiques du modèle :**
- Structure en U : chemin contractant (encodeur) + chemin expansif (décodeur)
- Segmentation sémantique binaire
- Résultats visuels faciles à interpréter par les professionnels de santé

---

## 📁 Contenu du projet

- 📓 [`Breast_cancer_Image_Segmentation_UNET`](https://colab.research.google.com/drive/1w84ilROPSIVFHxhhV7WII4YCajN5WylN#scrollTo=10ea04cc-70ad-4312-b00d-993e8a19b6b2) : Fichier Google Colab contenant tout le code (prétraitement, architecture U-Net, entraînement, prédiction, visualisation).
- 📄 Dataset utilisé : images échographiques du sein annotées (lien ou description à ajouter)
- 📸 Résultats : affichage des masques prédits comparés aux masques réels

---

## 🧪 Méthodologie

1. **Prétraitement des données** : redimensionnement, normalisation
2. **Construction du modèle U-Net** : en TensorFlow / Keras
3. **Entraînement** : sur un jeu de données annoté (masques binaires)
4. **Évaluation** : métriques comme Dice coefficient, IoU (Intersection over Union)
5. **Visualisation** : affichage des résultats prédits vs vérité terrain


## 🎯 Objectifs pédagogiques

- Appliquer des techniques de vision par ordinateur en santé
- Comprendre l’architecture U-Net et son fonctionnement
- Manipuler des données d’imagerie médicale
- Interpréter des résultats de segmentation

---

## 🧑‍💻 Réalisé avec

- Python, TensorFlow, Keras
- NumPy, OpenCV, Matplotlib
- Google Colab
