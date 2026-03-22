# 🧠 PHASE 0 — SEMAINE 3 : PROBABILITÉS (BASES)

## 🎯 Objectif
Comprendre :
- ce qu’est une probabilité
- événements
- indépendance

---

# 📌 1. C’EST QUOI UNE PROBABILITÉ ?

👉 Probabilité = chance qu’un événement arrive

Valeur entre 0 et 1

- 0 → impossible
- 1 → certain

---

## 🎲 Exemple

Pile ou face :

P(pile) = 0.5

---

# 📌 2. ÉVÉNEMENT

👉 Un événement = quelque chose qui peut arriver

Exemples :
- tirer un 6
- pleuvoir demain

---

# 📌 3. RÈGLES IMPORTANTES

## ➕ Addition

Si A et B exclusifs :

P(A ou B) = P(A) + P(B)

👉 Deux événements exclusifs : ils ne peuvent PAS arriver ensemble

---

## ✖️ Multiplication

Si indépendants :

P(A et B) = P(A) × P(B)

---

# 📌 4. INDÉPENDANCE

Deux événements indépendants :

👉 l’un n’influence pas l’autre

Exemple :
- lancer 2 fois une pièce

---

# 📌 5. INTUITION ML

👉 Exemple :

Spam detection :

P(spam | mot="promo")

👉 probabilité conditionnelle (on verra après)

---

# 🧪 EXERCICES

## Exercice 1
Pile ou face :

P(pile et pile)

---

## Exercice 2
Dé à 6 faces :

P(nombre pair)

---

## Exercice 3
Deux événements :

P(A) = 0.4  
P(B) = 0.5  

Si indépendants :

P(A et B) ?

---

## Exercice 4 (concept)
Explique indépendance avec un exemple

---

# 🚀 MINI PRATIQUE

Simuler en Python :

- lancer une pièce 1000 fois
- calculer fréquence

---

# ✅ CRITÈRE

- comprendre indépendance
- comprendre multiplication