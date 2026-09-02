# Chapitre 6 — Résolution des Actions

Toute situation incertaine, périlleuse ou opposée se résout par un **jet de dés**. Ce chapitre détaille le fonctionnement de la réserve de dés, la méthode de calcul du résultat et le traitement des succès et des échecs.

---

## 🎲 1. Constitution de la Réserve de Dés

Lorsqu'un personnage tente une action dont l'issue est douteuse, le joueur rassemble son **pool de d6** en additionnant trois éléments de sa fiche :

$$\text{Réserve de Dés} = \text{Composant} + \text{Action} + \text{Domaine} (+ \text{Bonus éventuels})$$

> **Exemple :**
> * **Action :** Pirater sous pression un terminal de sécurité en tapant à toute vitesse.
> * **Composant :** 🔴 CHAIR / CHROME ($3$)
> * **Action :** AGIR ($2$)
> * **Domaine :** NET ($3$)
> * **Total :** $3 + 2 + 3 = \mathbf{8\text{ d6}}$ à lancer.

---

## 🎯 2. Seuil de Difficulté et Marge de Succès

Contrairement aux systèmes où l'on additionne les dés, ce moteur utilise une **lecture par seuil de réussite fixe**.

* Tout dé affichant **4, 5 ou 6** compte comme un **Succès** ($\text{S}$).
* Tout dé affichant **1, 2 ou 3** est un **Échec**.

### Le Seuil de Difficulté ($\text{SD}$)
Le Meneur de Jeu fixe le nombre de **Succès requis** pour réussir l'action en fonction des conditions :

| Difficulté | Succès requis ($\text{SD}$) | Situation typique |
| :--- | :---: | :--- |
| **Simple** | $1\text{ S}$ | Action de routine sous légère pression. |
| **Moyenne** | $2\text{ S}$ | Tâche standard dans des conditions hostiles. |
| **Difficile** | $3\text{ S}$ | Intervention complexe sous le feu ennemi. |
| **Extrême** | $4\text{ S}$ | Exploit technique ou physique face à un système militaire. |
| **Critique** | $5+\text{ S}$ | Action quasi impossible nécessitant une maîtrise totale. |

---

## 📈 3. Résultat du Jet et Marges

Une fois les dés lancés, on compte le nombre de succès obtenus par rapport au $\text{SD}$ demandé :

* **Échec ($< \text{SD}$) :** L'action échoue ou s'accompagne d'une complication majeure imposée par le MJ.
* **Succès ($\ge \text{SD}$) :** L'action réussit.
* **Marge de Succès ($\text{MS}$) :** Chaque succès supplémentaire obtenu au-delà du $\text{SD}$ forme la **Marge**.
  $$\text{MS} = \text{Succès obtenus} - \text{Difficulté } (\text{SD})$$

### Utilisation de la Marge ($\text{MS}$)
Les points de $\text{MS}$ permettent au joueur d'ajouter des effets tactiques :
* **Dégâts / Impact :** Ajouter $+1$ dégât ou $+1$ d'efficacité par point de $\text{MS}$.
* **Rapidité :** Réduire le temps d'exécution de moitié.
* **Discrétion :** Ne laisser aucune trace numérique ou physique.
* **Avantage tactique :** Donner $+1\text{ d6}$ au prochain jet d'un allié.

---

## 💥 4. Rejets et Tensions (Succès Critiques & Échecs)

### Triomphe (Succès Critique)
Si le lancer comporte **trois "6" ou plus**, le personnage obtient un **Triomphe**. L'action réussit immédiatement avec l'effet maximal escompté, même si le nombre total de succès était inférieur au $\text{SD}$, et gagne un avantage narratif majeur.

### Complication Majeure (Échec Critique)
Si le jet ne produit **aucun succès** (aucun $4, 5, 6$) et contient **au moins la moitié de "1"**, c'est un échec critique. Le système réagit violemment : alarme déclenchée, arme enrayée, surchauffe d'implant ou contre-attaque immédiate de la matrice.

---

## ⚔️ 5. Oppositions Directes

Lorsque deux personnages s'affrontent directement (un tir contre une esquive, une intrusion contre un pare-feu, une intimidation contre une résistance mentale) :

1. Les deux participants lancent leur réserve de dés respective.
2. Celui qui obtient le **plus grand nombre de Succès** remporte l'opposition.
3. La Marge du vainqueur correspond à la différence de succès entre les deux jets :
   $$\text{MS} = \text{Succès du Vainqueur} - \text{Succès du Défenseur}$$
