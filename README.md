# classification-articles-presse  

Classification automatique d’articles de presse en différentes thématiques (Économie, Science, Sport) en utilisant le Machine Learning et le NLP.   

### Introduction  
L’objectif de ce projet est de développer un système de classification supervisée capable de catégoriser automatiquement des articles de presse. Ce projet illustre l’application des techniques de traitement automatique du langage naturel (NLP) et d’apprentissage supervisé pour organiser efficacement du contenu textuel.  

###  Méthodologie  
Le pipeline de traitement mis en place se décompose en plusieurs étapes:  

- **Prétraitement du texte** : tokenisation, lemmatisation, suppression des stopwords, normalisation  
- **Vectorisation des données** : représentation des articles via **TF-IDF**  
- **Modélisation supervisée** : comparaison de plusieurs modèles (régression logistique, forêts aléatoires)  
- **Évaluation** : précision, rappel, f1-score, matrices de confusion  

###  Résultats et réalisations  
- Les modèles supervisés distinguent efficacement les thématiques principales (Économie, Science, Sport).  
- La régression logistique a montré de bonnes performances avec une généralisation stable.  
- Les forêts aléatoires ont apporté une meilleure robustesse sur les classes déséquilibrées.  

### Pistes d’amélioration  
- Utilisation de modèles de NLP avancés (Word2Vec, BERT, Transformers).  
- Augmentation du jeu de données pour améliorer la généralisation.  
- Développement d’une interface interactive (Streamlit, Flask).  

### Environnement technique  
- **Langage** : Python  
- **Librairies** : scikit-learn, pandas, NumPy, NLTK/SpaCy, matplotlib, seaborn  
- **Notebook** : Jupyter Notebook  
