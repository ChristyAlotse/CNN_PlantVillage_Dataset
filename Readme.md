# 🌿 Classification de Maladies des Plantes par Réseaux de Neurones Convolutifs (CNN)

Ce projet vise à classifier différentes maladies des plantes en utilisant un réseau de neurones convolutifs (CNN) **construit from scratch**, sans recours à des modèles pré-entraînés. Il s'agit d'une application complète de l'apprentissage profond, couvrant **la préparation des données**, **la modélisation**, **l'entraînement**, et **l'évaluation des performances** après **optimisation des hyperparamètres**.

---

## 🎯 Objectifs du Projet

- Implémenter un pipeline de classification d'images en deep learning.
- Construire un **CNN personnalisé** sans transfert learning.
- Expérimenter plusieurs stratégies d’optimisation (dropout, data augmentation, scheduler, etc.).
- Évaluer la robustesse du modèle via des métriques classiques de classification.

---

## 🛠️ Technologies et Librairies

- Python 3.8+
- TensorFlow / Keras
- NumPy, Pandas, Matplotlib, cv2
- Scikit-learn
- 

---

## 📁 Structure du Projet


---

## 🚀 Lancer le Projet

### 1. Cloner le dépôt

```bash
git clone https://github.com/votre-utilisateur/plant-disease-cnn.git
cd plant-disease-cnn
```

### 2. Créer un environnement virtuel

```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows
```

### 3. Exécutez chaque cellule du fichier jupyter


---

## 📊 Résultats

Le modèle CNN a atteint une **précision de 57%** sur l’ensemble de test après optimisation.  
Parmi les techniques utilisées :

- **Normalisation des images**
- **Data augmentation**
- **Dropout régulier**
- **EarlyStopping et ReduceLROnPlateau**

---

## 🔭 Perspectives Futures

Afin d'améliorer significativement les performances du modèle, plusieurs pistes sont envisagées :

- **Utilisation de modèles pré-entraînés** comme ResNet, EfficientNet ou MobileNet via le transfert learning.
- **Enrichissement du dataset** avec plus de classes et d'exemples par classe.
- **Déploiement web** avec une interface Streamlit ou Flask.
- **Intégration d’une API de prédiction** pour des applications mobiles ou IoT.

---

## 📞 Contact

Pour toute question, ouvrez une issue ou contactez-moi à `alotsechristy@gmail.com`.
---

