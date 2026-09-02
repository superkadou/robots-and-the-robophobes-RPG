# Chapitre 6 — Résolution des Actions & Tests

Dans « Chrome & Néon », chaque action critique où l'échec a des conséquences utilise un système unifié basé sur les composants et la lecture des faces des dés.

---

## 🎲 1. Le Lancer de Dés

Lorsqu'un personnage entreprend une action non-conflictuelle (crocheter une serrure, pirater un terminal, franchir un obstacle, analyser une situation), le joueur constitue sa réserve de dés (pool) :
$$\text{Réserve} = \text{Composant} + \text{Action} + \text{Compétence (Archétype/Domaine)}$$

Il lance l'ensemble sous forme de **d6 standard**. 

### Lecture des Faces (Les Couleurs)
Chaque dé produit un résultat selon sa face, indépendamment de sa valeur numérique :
* **Faces 1 - 2 :** 🔴 **ROUGE** *(Chair / Impact physique)*
* **Faces 3 - 4 :** 🟢 **VERT** *(Structure / Survie / Résistance)*
* **Faces 5 - 6 :** 🔵 **BLEU** *(Système / Flux / Données)*

---

## 🎯 2. La Règle du Succès Ciblé

Pour qu'un dé compte comme un **Succès (S)**, sa couleur doit **impérativement correspondre à la couleur du Composant sollicité** par l'action :

* **Test basé sur 🔴 CHAIR / CHROME :** Seuls les dés donnant une face 🔴 **Rouge** comptent comme des succès.
* **Test basé sur 🔵 ESPRIT / SOFTWARE :** Seuls les dés donnant une face 🔵 **Bleue** comptent comme des succès.
* **Test basé sur 🟢 ÂME / OS :** Seuls les dés donnant une face 🟢 **Verte** comptent comme des succès.

---

## 📊 3. Difficulté & Seuils (SR)

Le MJ détermine le nombre de Succès requis selon la complexité de l'action :
* **Routine (1 S) :** Franchir un obstacle simple, pirater une bécane basique.
* **Complexe (2 S) :** Crocheter une serrure électronique civile, analyser un code piégé.
* **Expert (3+ S) :** Infiltrer un mainframe corpo, réparer un réacteur en marche sous le feu.

### La Coopération de Groupe
Pour les tâches d'envergure, plusieurs personnages peuvent combiner leurs efforts. Les dés de la bonne couleur obtenus par l'ensemble des participants s'additionnent pour atteindre le Seuil de Réussite (SR) global de la tâche.
