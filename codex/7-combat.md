# Chapitre 7 — Le Combat & la Dynamique de Groupe

Le combat dans « Chrome & Néon » n'est pas une suite de duels individuels, mais une épreuve collective gérée sur un **plateau de combat** central. La survie de l'équipe dépend de sa capacité à générer, répartir et consommer les jetons de ressources sous la pression de la rue.

---

## 🔴 🟢 🔵 🖤 1. Les 3 Zones et 4 pools du plateau de combat

Le plateau physique central se divise en trois zones distinctes qui dictent la gestion des jetons :

* La défense
* Les dégats
* L'attrition

Ces trois zones sont alimentées par les 4 pools de tokens : 

### 🔴 Le Pool Rouge
* **Fonctionnement :** Les jetons rouges représentent la pression offensive et les parades d'urgence. 
* **La Règle du Rebond :** Ce sont des pions de défense en attente. Si les jetons rouges présents dans cette zone ne sont pas consommés ou attribués pour parer une menace avant la fin du tour, **ils se transforment automatiquement en dégâts bruts** encaissés par l'escouade.

### 🟢 Le Pool Vert 
* **Fonctionnement :** Les jetons verts sont exclusivement des pions de **défense pure, de blindage et de couverture**. 
* **Rôle :** Ils servent à absorber les impacts et à protéger les membres de l'équipe exposés. Contrairement aux rouges, un jeton vert inutilisé ne se retourne pas contre l'équipe : il s'évapore simplement en fin de tour.

### 🔵 Le Pool Bleu
* **Fonctionnement :** Les jetons bleus constituent la force de frappe directe et l'énergie brute de l'offensive de l'escouade.
* **Rôle :** En fin de tour (lors de la *Damage Step*), les jetons bleus présents dans cette zone sont convertis en **dégâts directs** infligés aux adversaires. 

### 🖤 Le Pool Noir 
* **Fonctionnement :** Le Noir ne provient **jamais** des dés lancés par les joueurs. Il est généré exclusivement par le matériel lourd, le surcadencement (Overclock) ou les traits passifs des Boss et des menaces d'élite.
* **La Sanction :** Les jetons noirs stockés dans cette zone représentent l'usure du terrain, la fatigue et les dégâts incompressibles. En fin de tour, l'équipe doit obligatoirement les répartir et les payer en **Points de Vie (chair)** ou en **Stress (mental)**.

---

## 🔄 Structure Générale du Round

1. **Alternance des Phases d'Attaque :** Chaque personnage (attaquant comme défenseur) doit résoudre une Phase d'Attaque individuelle par round. L'ordre d'itération alterne strictement entre les deux factions :
   * Un personnage de la **Faction A** résout sa Phase d'Attaque.
   * Un personnage de la **Faction B** résout sa Phase d'Attaque.
   * *Répéter l'alternance jusqu'à ce que tous les combattants aient agi.*
   *(Chaque faction choisit librement l'ordre d'activation interne de ses membres).*
2. **Phase de Défense Simultanée :** Une fois l'intégralité des Phases d'Attaque épuisée, les deux factions résolvent la Phase de Défense ensemble.

---

## ⚔️ Phase 1 : Phase d'Attaque

Lors de son activation, chaque personnage déroule dans l'ordre les trois étapes suivantes :

### a) Étape de la Réserve de Dés (Dice Pool Step)
Le joueur assemble sa réserve de dés en additionnant sa Caractéristique, sa Compétence, son Action et les éventuels bonus de ses armes ou logiciels.
* **Humains (Viande) :** Lançaient leurs dés pour obtenir des résultats bruts de couleur.
* **Mécas :** Obtiennent des **Jetons Neutres** et appliquent leur **Cascade d'Allocation** obligatoire pour les convertir.

### b) Étape de Relance (Reroll Step)
Le joueur peut déclencher des capacités spéciales, des programmes de surcharge, dépenser du Stress ou utiliser l'**Overclock** afin de relancer un ou plusieurs dés.

### c) Étape de Placement des Jetons (Place Tokens Step)
Le joueur assigne les jetons générés par son jet d'attaque dans les sections dédiées de sa **Zone de Combat** (son plateau individuel ou de Squad) :
* **Boîte de Dégâts :** Reçoit les jetons offensifs (Jetons Bleus 🔵).
* **Boîte de Défense :** Reçoit les jetons de structure et d'armure (Jetons Verts 🟢 et Rouges 🔴).
* **Boîte d'Attrition :** Reçoit les jetons de pression, d'interruption ou d'usure (Jetons Noirs 🖤).

---

## 🛡️ Phase 2 : Phase de Défense

La Phase de Défense est résolue **simultanément** par les deux factions à la fin du round. Elle s'exécute selon trois étapes strictes et séquentielles :

### a) Étape d'Armure
Chaque faction retire l'intégralité de ses **jetons d'Armure (🟢)** stockés dans sa *Boîte de Défense*.
Pour **chaque jeton d'Armure dépensé**, la faction supprime dans la Zone de Combat ennemie :
1. **Un jeton d'attaque** (au choix dans la *Boîte de Dégâts* ou de *Défense* adverse), **ET**
2. **Un jeton d'usure** (dans la *Boîte d'Attrition* adverse).

*Si une faction possède plus de jetons d'Armure que l'ennemi n'a de jetons cibles, l'excédent d'Armure est défaussé sans effet.*

> **Exemple :** L'escouade des Netrunners possède 3 jetons d'Armure (🟢) dans sa boîte de défense. En retirant ces 3 jetons, elle annule 3 jetons de la Boîte de Dégâts de la Mégacorpo ET 3 jetons de sa Boîte d'Attrition.

### b) Étape des Blessures Directes
Chaque faction retire désormais tous les jetons de dégâts restant dans sa propre **Boîte de Dégâts**.
* Pour **chaque jeton de dégât défaussé**, la faction adverse subit **1 Blessure directe (1 PV en moins)**.
* Chaque faction répartit librement les blessures subies entre ses personnages.
* **Élimination :** Un personnage tombant à 0 PV est retiré du combat. Si la totalité d'une faction est éliminée lors de cette étape, le combat prend fin immédiatement. Les survivants remportent la victoire et peuvent piller un équipement sur chaque cadavre ou châssis détruit.

### c) Étape de Résolution & Attrition
S'il reste des combattants actifs dans les deux factions :
1. **Consolidation :** Les deux factions déplacent tous les jetons restants de leurs *Boîtes de Défense* et d'*Attrition* vers leur **Boîte de Dégâts** (laissant les boîtes d'attrition et de défense totalement vides).
2. **Purge d'Attrition :** Les deux factions retirent, un par un et simultanément, un jeton de leur *Boîte de Dégâts* respective.
3. **Pression Révélée :** La première faction à vider sa *Boîte de Dégâts* subit immédiatement **1 Blessure directe pour chaque jeton de dégât qu'il reste** dans la boîte de la faction adverse (blessures réparties au choix par la faction touchée).
4. **Nettoyage :** Tous les jetons restants sont ensuite défaussés afin que toutes les Zones de Combat soient entièrement vides pour le round suivant.
   
---


