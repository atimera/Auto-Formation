# 🧠 PHASE 0 — SEMAINE 2 : MATRICES

## 🎯 Objectif
Comprendre :
- ce qu’est une matrice
- comment manipuler des datasets
- base du fonctionnement des modèles ML

---

# 📌 1. C’EST QUOI UNE MATRICE ?

Une matrice = tableau de nombres

Exemple :
X = [
 [1, 2],
 [3, 4],
 [5, 6]
]

👉 3 lignes, 2 colonnes

---

## 📊 En data

Dataset :

| âge | salaire |
|----|--------|
| 25 | 2000 |
| 30 | 2500 |
| 35 | 3000 |

👉 matrice :
X = [
 [25, 2000],
 [30, 2500],
 [35, 3000]
]

---

# 📌 2. DIMENSION

Matrice (n, m)
- n = lignes (observations)
- m = colonnes (features)

---

# 📌 3. OPÉRATIONS

## ➕ Addition

Même dimension obligatoire

---

## 🔁 Transposée

On échange lignes et colonnes

---

## 🔥 Multiplication matricielle (TRÈS IMPORTANT)

👉 condition :
colonnes de A = lignes de B

---

## Exemple :

A (2x3)
B (3x2)

👉 possible

---

## Calcul :

Chaque élément =
produit scalaire ligne × colonne

---

# 📌 4. EN PYTHON

```python
import numpy as np

X = np.array([
    [1,2],
    [3,4]
])

Y = np.array([
    [5,6],
    [7,8]
])

# multiplication matricielle
np.dot(X, Y)