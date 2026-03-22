# 🎯 Plan de Formation Autodidacte — ML · Data Science · Data Analyst

> **Profil** : Développeur informatique, licence info ~10 ans, maths partiellement oubliés  
> **Disponibilité** : 3 à 6h / semaine  
> **Objectif** : Acquérir des compétences solides et progressives dans les 3 domaines  
> **Format de suivi** : Étape par étape, validation avant passage à la suivante  

---

## 📊 Estimation des durées globales

| Niveau | Heures totales estimées | Durée à 3h/sem | Durée à 6h/sem |
|--------|------------------------|----------------|----------------|
| **Notions** (comprendre de quoi on parle) | ~50h | ~4 mois | ~2 mois |
| **Débutant** (premiers projets fonctionnels) | ~150h supplémentaires | +1 an | +6 mois |
| **Intermédiaire** (projets réels, autonomie) | ~300h supplémentaires | +2 ans | +1 an |
| **Expert** (maîtrise avancée, production) | ~500h supplémentaires | +3 ans | +18 mois |

> ⚠️ Ces durées sont des estimations moyennes. Elles varient selon ta régularité et ton engagement sur les projets pratiques.

---

## 🗺️ Vue d'ensemble des phases

```
PHASE 0 — Socle commun (maths + Python)          ← On commence ici
PHASE 1 — Data Analyst
PHASE 2 — Data Science
PHASE 3 — Machine Learning
PHASE 4 — Projets intégrateurs & Portfolio
```

> Les phases 1, 2 et 3 sont progressives et interdépendantes.  
> La Phase 0 est **obligatoire** et commune aux 3 domaines.

---

## 🔷 PHASE 0 — Socle commun fondamental

**Durée estimée : ~60h (4 à 5 mois à 3h/sem)**  
**Objectif : Avoir les bases solides en maths et Python pour aborder les 3 domaines**

### Étape 0.1 — Remise à niveau Mathématiques (≈25h)
- Algèbre linéaire : vecteurs, matrices, produit matriciel, transposition
- Statistiques descriptives : moyenne, médiane, écart-type, variance, distribution
- Probabilités : loi des grands nombres, loi normale, loi de Bayes
- Calcul différentiel (bases) : dérivées, gradient, notion d'optimisation

### Étape 0.2 — Python pour la Data (≈25h)
- Rappels Python : structures de données, fonctions, classes, fichiers
- NumPy : tableaux, opérations vectorisées
- Pandas : DataFrames, manipulation, nettoyage, filtres, agrégations
- Matplotlib / Seaborn : visualisations de base

### Étape 0.3 — Environnement de travail (≈10h)
- Jupyter Notebook / JupyterLab
- Git & GitHub (versionner ses notebooks)
- Conda / virtualenv (gestion d'environnements)

---

## 🔶 PHASE 1 — Data Analyst

**Durée estimée : ~80h (6 à 7 mois supplémentaires à 3h/sem)**  
**Prérequis : Phase 0 validée**

### Étape 1.1 — Analyse exploratoire des données (EDA) (≈20h)
- Comprendre et nettoyer un jeu de données
- Identifier les valeurs manquantes, outliers
- Visualisations avancées (distributions, corrélations, heatmaps)

### Étape 1.2 — SQL pour l'analyse (≈20h)
- SELECT, WHERE, GROUP BY, HAVING, JOIN
- Sous-requêtes, fenêtres (window functions)
- Pratique sur des bases réelles (ex: SQLite, PostgreSQL)

### Étape 1.3 — Statistiques appliquées à l'analyse (≈20h)
- Tests statistiques : t-test, chi², ANOVA
- Corrélation vs causalité
- Introduction aux intervalles de confiance et p-values

### Étape 1.4 — Visualisation & Reporting (≈20h)
- Tableaux de bord avec Plotly / Dash ou Power BI (au choix)
- Raconter une histoire avec des données (data storytelling)
- Projet fil rouge : analyser un dataset réel et produire un rapport complet

---

## 🟠 PHASE 2 — Data Science

**Durée estimée : ~100h (8 à 9 mois supplémentaires à 3h/sem)**  
**Prérequis : Phase 1 validée**

### Étape 2.1 — Feature Engineering (≈20h)
- Encodage des variables catégorielles
- Normalisation / standardisation
- Création de nouvelles features, sélection de features

### Étape 2.2 — Introduction au Machine Learning (≈30h)
- Concepts : supervisé / non supervisé, overfitting, underfitting
- Scikit-learn : pipeline, train/test split, cross-validation
- Premiers modèles : régression linéaire, régression logistique, k-NN

### Étape 2.3 — Évaluation des modèles (≈20h)
- Métriques : accuracy, precision, recall, F1, ROC-AUC, RMSE
- Matrice de confusion
- Comparaison et sélection de modèles

### Étape 2.4 — Projet Data Science complet (≈30h)
- Collecte → nettoyage → exploration → modélisation → évaluation → présentation
- Projet fil rouge sur Kaggle ou dataset réel

---

## 🔴 PHASE 3 — Machine Learning avancé

**Durée estimée : ~150h (1 an supplémentaire à 3h/sem)**  
**Prérequis : Phase 2 validée**

### Étape 3.1 — Algorithmes supervisés avancés (≈30h)
- Arbres de décision, Random Forest, Gradient Boosting (XGBoost, LightGBM)
- SVM (Support Vector Machines)
- Hyperparameter tuning (GridSearch, RandomSearch, Optuna)

### Étape 3.2 — Apprentissage non supervisé (≈25h)
- Clustering : K-Means, DBSCAN, hierarchique
- Réduction de dimensionnalité : PCA, t-SNE, UMAP

### Étape 3.3 — Deep Learning (introduction) (≈40h)
- Réseaux de neurones : perceptron, rétropropagation, fonctions d'activation
- Frameworks : TensorFlow / Keras ou PyTorch
- CNN (images), RNN / LSTM (séquences)

### Étape 3.4 — MLOps & mise en production (≈30h)
- Sauvegarder et charger des modèles (joblib, pickle, ONNX)
- Créer une API de prédiction (FastAPI)
- Introduction à MLflow pour le tracking d'expériences

### Étape 3.5 — Projet ML complet de bout en bout (≈25h)
- De la donnée brute au modèle déployé
- Documenter, versionner, présenter

---

## 🟢 PHASE 4 — Projets intégrateurs & Portfolio

**Durée estimée : ~80h (6 mois supplémentaires à 3h/sem)**  
**Prérequis : Phases 1, 2 et 3 validées**

### Étape 4.1 — Construire son portfolio GitHub (≈20h)
- 3 projets minimum bien documentés (README, notebooks propres)
- Un projet par domaine (analyse, science, ML)

### Étape 4.2 — Kaggle & compétitions (≈30h)
- Participer à des compétitions pour affronter des cas réels
- Lire et analyser des notebooks publics de top participants

### Étape 4.3 — Veille technologique & spécialisation (≈30h)
- Choisir une spécialisation (NLP, vision, séries temporelles…)
- Suivre les tendances : papers, blogs, podcasts

---

## 📌 Ressources recommandées (gratuites en priorité)

| Domaine | Ressource | Lien |
|---------|-----------|------|
| Maths | 3Blue1Brown (YouTube) | youtube.com/3blue1brown |
| Maths | Khan Academy | khanacademy.org |
| Python/Data | Kaggle Learn | kaggle.com/learn |
| ML | fast.ai | fast.ai |
| ML | Andrew Ng — ML Specialization (Coursera) | coursera.org |
| SQL | SQLZoo / Mode Analytics | sqlzoo.net |
| Pratique | Kaggle Datasets & Competitions | kaggle.com |

---

## 🔖 Suivi de progression

| Phase | Étape | Statut | Date validation |
|-------|-------|--------|-----------------|
| Phase 0 | 0.1 Maths | 🔲 À faire | — |
| Phase 0 | 0.2 Python Data | 🔲 À faire | — |
| Phase 0 | 0.3 Environnement | 🔲 À faire | — |
| Phase 1 | 1.1 EDA | 🔲 À faire | — |
| Phase 1 | 1.2 SQL | 🔲 À faire | — |
| Phase 1 | 1.3 Stats appliquées | 🔲 À faire | — |
| Phase 1 | 1.4 Visualisation | 🔲 À faire | — |
| Phase 2 | 2.1 Feature Engineering | 🔲 À faire | — |
| Phase 2 | 2.2 Intro ML | 🔲 À faire | — |
| Phase 2 | 2.3 Évaluation modèles | 🔲 À faire | — |
| Phase 2 | 2.4 Projet DS | 🔲 À faire | — |
| Phase 3 | 3.1 Algos supervisés avancés | 🔲 À faire | — |
| Phase 3 | 3.2 Non supervisé | 🔲 À faire | — |
| Phase 3 | 3.3 Deep Learning | 🔲 À faire | — |
| Phase 3 | 3.4 MLOps | 🔲 À faire | — |
| Phase 3 | 3.5 Projet ML | 🔲 À faire | — |
| Phase 4 | 4.1 Portfolio | 🔲 À faire | — |
| Phase 4 | 4.2 Kaggle | 🔲 À faire | — |
| Phase 4 | 4.3 Veille & spécialisation | 🔲 À faire | — |

---

*Document généré le 22/03/2026 — Mis à jour à chaque validation d'étape*
