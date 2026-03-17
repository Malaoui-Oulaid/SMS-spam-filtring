#  SMS Spam Classification (NLP Project)

##  Description
Ce projet consiste à construire un modèle de **classification de texte** pour détecter si un SMS est un **spam** ou un **message normal (ham)**.

Il s'agit d'un problème classique de **Natural Language Processing (NLP)** utilisant des techniques de **Machine Learning**.

---

##  Objectif
L'objectif est de :
- Nettoyer et préparer les données textuelles
- Transformer le texte en variables numériques
- Entraîner plusieurs modèles de classification
- Comparer leurs performances
- Identifier le meilleur modèle pour détecter les spams

---

##  Dataset
Le dataset contient des SMS étiquetés :
- `spam` : message indésirable
- `ham` : message normal

---

##  Pipeline du projet

### 1.  Chargement des données
- Lecture du dataset avec **pandas**

### 2.  Data Cleaning & Preprocessing
- Conversion en minuscules
- Suppression de la ponctuation
- Suppression des stopwords
- Stemming (avec NLTK)

### 3.  Analyse exploratoire (EDA)
- Distribution des classes
- Longueur des messages
- Visualisations avec seaborn & matplotlib

### 4.  Feature Engineering
- Transformation du texte avec :
  - `CountVectorizer` (Bag of Words)

### 5.  Modélisation
Plusieurs modèles ont été testés :
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- XGBoost

### 6.  Évaluation
- Accuracy
- Precision / Recall
- Comparaison des modèles

---

##  Technologies utilisées

- Python 🐍
- pandas
- numpy
- scikit-learn
- nltk
- matplotlib
- seaborn
- xgboost
- lightgbm
- catboost

---

##  Résultats
- Comparaison des performances des différents modèles
- Identification du modèle le plus performant pour la détection de spam

---

##  Améliorations possibles
- Utiliser TF-IDF au lieu de CountVectorizer
- Tester des modèles deep learning (LSTM, GRU)
- Optimisation des hyperparamètres (GridSearchCV)
- Déploiement du modèle (API ou web app)

---
