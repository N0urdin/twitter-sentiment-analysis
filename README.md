# 🐦 Analyse des Sentiments sur Twitter

Projet NLP pour détecter automatiquement le sentiment (positif/négatif) de tweets, à partir d’un dataset Kaggle.

## 🧠 Objectifs
- Prétraiter des tweets (nettoyage, vectorisation TF-IDF)
- Entraîner des modèles supervisés pour classifier les sentiments
- Évaluer les performances avec F1-score et matrice de confusion

## 🔧 Outils utilisés
- Python, Pandas, NLTK, Scikit-learn
- Modèles : Logistic Regression, Naive Bayes

## 📁 Structure
```
📂 Analyse des Sentiments sur Twitter
├── Analyse des Sentiments sur Twitter.ipynb
├── README.md
```

## 🔪 Exemple d’évaluation
- Accuracy : 85.2%
- F1-score : 0.84

## Jeu de données

Le dataset utilisé pour ce projet est **[Sentiment140](https://www.kaggle.com/datasets/kazanova/sentiment140)**, disponible publiquement sur Kaggle.

> **Remarque :** En raison de la taille du fichier (plus de 25 Mo), il n’est pas inclus directement dans ce dépôt GitHub. Vous pouvez le télécharger depuis la page Kaggle ci-dessus et le placer dans le dossier approprié (`/input/` par exemple) pour reproduire les résultats.


