
# TP1 — Initiation au NLP

Salut ! Je suis **Sara OUADAY**, étudiante en Master TEE.

Ce projet correspond à mon premier TP d'initiation au **NLP (Natural Language Processing)**. L'objectif est de découvrir les techniques de prétraitement du texte permettant à une machine d'analyser et de traiter le langage humain.

## Ce que j'ai réalisé

- **Préparation :** installation et découverte de NLTK, spaCy et scikit-learn.
- **Nettoyage du texte :** conversion en minuscules et suppression de la ponctuation.
- **Tokenisation et stopwords :** découpage du texte en mots et suppression des mots vides.
- **Lemmatisation :** réduction des mots à leur forme de base (par exemple, « adore » devient « adorer »).
- **Représentation du texte :** découverte du Bag of Words et du TF-IDF pour transformer les textes en données numériques.

## Outils utilisés

- Python
- Jupyter Notebook
- NLTK
- spaCy
- scikit-learn

## Fichier principal

- `TP1_NLP.ipynb` : notebook contenant le code, les résultats et les réponses aux questions du TP.

## Installation et exécution

### 1. Installer les bibliothèques

```bash
pip install nltk spacy scikit-learn
```

### 2. Télécharger le modèle français de spaCy

```bash
python -m spacy download fr_core_news_sm
```

### 3. Lancer Jupyter Notebook

```bash
jupyter notebook
```

Ouvrir ensuite le fichier `TP1_NLP.ipynb` pour consulter et exécuter les cellules du notebook.
