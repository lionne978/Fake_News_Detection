# 📰 Détecteur de Fake News  
**Projet académique | UNCHK | Février - Mai 2024**

## 📚 Contexte
Dans ce projet académique, l'objectif était de développer un détecteur de fausses informations en utilisant des techniques de traitement du langage naturel (NLP) et de Machine Learning. Une interface simple a également été développée pour permettre aux utilisateurs de tester eux-mêmes le modèle.

## 📂 Données
- **Origine** : Données collectées par scraping à partir de plusieurs sites d’actualités.
- **Étiquetage** : Articles classés en deux catégories :
  - `Vrai`
  - `Faux`

## 🛠️ Outils et Technologies
- **Python** (via **Jupyter Notebook**)
- **Bibliothèques principales** :
  - `requests`, `BeautifulSoup` pour le scraping
  - `pandas`, `numpy` pour la manipulation des données
  - `nltk`, `re` pour le traitement du texte
  - `scikit-learn` pour la modélisation Machine Learning
  - `Flask` pour la création de l'interface web

## 🧹 Processus
- **Scraping** : récupération automatique des articles à partir de sites d'actualités.
- **Prétraitement** :
  - Nettoyage des textes
  - Tokenisation
  - Vectorisation avec TF-IDF
- **Modélisation** :
  - Entraînement de modèles de Machine Learning pour classifier les articles.
  - Évaluation sur un jeu de test.
- **Développement** :
  - Création d'une interface utilisateur avec Flask pour tester le modèle en saisissant un texte.

## 📈 Résultats
Le modèle est capable de détecter efficacement les fake news sur de nouveaux textes grâce à un processus rigoureux de préparation et d'entraînement.


