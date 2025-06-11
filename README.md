# 📖 Logic Solver

**Logic Solver** est un outil interactif de vérification de formules logiques propositionnelles en **forme normale conjonctive (CNF)**, basé sur la méthode de **résolution par réfutation** introduite par **J.A. Robinson** en 1965.

Ce site web propose une expérience fluide et intuitive, accessible directement en ligne, sans installation, combinant **puissance algorithmique** et **interface moderne**.

🔗 **Accéder à l'outil** : [Logic Solver en ligne](https://684a1562dc8bb429a2b7a9eb--velvety-nasturtium-55678b.netlify.app))

---

## ✨ Fonctionnalités

- 📝 Création et gestion de formules logiques en CNF  
- 🔍 Test de satisfaisabilité via la **résolution par réfutation**
- 👁️ Aperçu visuel des formules avec la notation logique standard (∧, ∨, ¬)
- ⚡ Algorithme avancé avec :
  - Propagation des unités
  - Élimination des tautologies
  - Traitement des littéraux purs
- 🔄 Module de **conversion automatique en CNF** à partir d'une formule logique classique
- 📁 Visualisation et navigation dans l’ensemble des formules sauvegardées

---

## 🚀 Commencer

Aucune installation requise.

Accédez simplement au site et commencez à manipuler vos formules logiques :  
👉 [[https://684a11e1b5a6be1a4f5120e2--velvety-nasturtium-55678b.netlify.app](https://684a1562dc8bb429a2b7a9eb--velvety-nasturtium-55678b.netlify.app)]([https://684a11e1b5a6be1a4f5120e2--velvety-nasturtium-55678b.netlify.app](https://684a1562dc8bb429a2b7a9eb--velvety-nasturtium-55678b.netlify.app))

---

## 📚 Comment utiliser

### ➕ Créer une nouvelle formule

- Nommer la formule
- Spécifier le nombre de clauses
- Saisir chaque clause avec les littéraux séparés par des espaces  
  - Utiliser `!` pour la négation (ex. : `!P` pour NON P)  
  - Exemple : `P !Q R` représente la clause *(P ∨ ¬Q ∨ R)*

### ✅ Tester une formule existante

- Sélectionner une formule existante
- Le système affiche le résultat : **SATISFIABLE** ou **UNSATISFIABLE**

### 📂 Afficher les formules disponibles

- Visualisation claire avec la notation logique standard
- Possibilité de lancer un test directement depuis la liste

---

## 🧠 Détails Techniques

L’algorithme implémente la **résolution par réfutation** :

1. Lecture de la formule CNF
2. Recherche de paires de clauses contenant des littéraux complémentaires (ex. : `P` et `!P`)
3. Génération des résolvantes
4. Ajout itératif des résolvantes jusqu'à :
   - 💥 Dérivation de la clause vide ⇒ **UNSATISFIABLE**
   - 🔚 Aucune nouvelle clause ⇒ **SATISFIABLE**

### Optimisations incluses

- 🔹 Propagation des clauses unitaires
- 🔹 Élimination des tautologies (`P ∨ ¬P`)
- 🔹 Subsomption (suppression de clauses redondantes)
- 🔹 Élimination des littéraux purs

---

## 👨‍💻 Développeur

Développé par **Boukeha Mohamed Akram**, dans le cadre du cours d’**Advanced Logic** à l’**École Nationale Supérieure d’Informatique (ESI)**, année universitaire **2024–2025**.

---

## 🙏 Remerciements

- M. **Khelifati Si Larbi**
- M. **Faical Touka**
- Mme **Charabi Leila**
- Mme **Meziani Lila**  
*(Encadrants académiques)*

Et à **J.A. Robinson** pour la méthode de résolution.

---
