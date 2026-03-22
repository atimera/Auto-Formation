# 🧠 PHASE 0 — SEMAINE 1 : ALGÈBRE (Vecteurs & Bases)

## 🎯 Objectif
Comprendre les bases mathématiques utilisées partout en data :
- vecteurs
- opérations
- intuition géométrique

👉 Objectif final :
Être à l’aise avec la manipulation de données sous forme vectorielle (fondamental pour ML)

---

# 📌 1. C’EST QUOI UN VECTEUR ?

## Définition simple
Un vecteur = une liste de nombres

Exemples :
- v = [1, 2, 3]
- x = [10, 5]

👉 En data :
- une ligne de dataset = un vecteur
- features = dimensions

---

## 📊 Exemple concret

Un utilisateur :
- âge = 25
- salaire = 2000
- score = 0.8

Vecteur :
x = [25, 2000, 0.8]

---

# 📌 2. OPÉRATIONS SUR LES VECTEURS

## ➕ Addition

[1,2] + [3,4] = [4,6]

👉 élément par élément

---

## ✖️ Multiplication par un scalaire

2 × [1,2] = [2,4]

---

## 🔁 Produit scalaire (IMPORTANT)

[1,2] · [3,4] = (1×3) + (2×4) = 11

👉 hyper important en ML :
- similarité
- modèles linéaires

---

# 📌 3. INTUITION (TRÈS IMPORTANT)

Un vecteur =
👉 un point
👉 ou une direction

---

## Exemple visuel

[1,2] = position dans un plan

👉 ML = manipuler des points dans des espaces (souvent énormes)

---

# 📌 4. EN PYTHON (INDISPENSABLE)

```python
import numpy as np

v = np.array([1, 2])
w = np.array([3, 4])

# addition
v + w

# produit scalaire
np.dot(v, w)

# multiplication
2 * v