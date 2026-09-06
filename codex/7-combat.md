[TODO]
# Chapitre 7 — Le Combat

Le combat dans « Chrome & Néon » n'est pas une suite de duels individuels, mais une épreuve collective gérée sur un **plateau de combat** central. La survie de l'équipe dépend de sa capacité à générer, répartir et consommer les jetons de ressources sous la pression de la rue.

---

## 🔴 🟢 🔵 🖤 1. Les 4 pools et 3 Zones du plateau de combat

Le plateau physique central se divise en trois zones distinctes qui dictent la gestion des jetons :

* La défense
* Les dégats
* L'attrition

Ces trois zones sont alimentées par les 4 pools de tokens : 

### 🔴 Le Pool Rouge
Les jetons rouges sont générés par les faces rouges des Dés.
* **Fonctionnement :** Les jetons rouges représentent la pression offensive et les parades d'urgence. 
* **La Règle du Rebond :** Ce sont des pions de défense en attente. Si les jetons rouges présents dans cette zone ne sont pas consommés ou attribués pour parer une menace avant la fin du tour, **ils se transforment automatiquement en dégâts bruts** encaissés par l'escouade.

### 🟢 Le Pool Vert 
Les jetons verts sont générés par les faces vertes des Dés.
* **Fonctionnement :** Les jetons verts sont exclusivement des pions de **défense pure, de blindage et de couverture**. 
* **Rôle :** Ils servent à absorber les impacts et à protéger les membres de l'équipe exposés. Contrairement aux rouges, un jeton vert inutilisé ne se retourne pas contre l'équipe : il s'évapore simplement en fin de tour.

### 🔵 Le Pool Bleu
Les jetons bleux sont générés par les faces bleues des Dés.
* **Fonctionnement :** Les jetons bleus constituent la force de frappe directe et l'énergie brute de l'offensive de l'escouade.
* **Rôle :** En fin de tour (lors de la *Damage Step*), les jetons bleus présents dans cette zone sont convertis en **dégâts directs** infligés aux adversaires. 

### 🖤 Le Pool Noir 
Les jetons noirs ne sont pas générés par des lancés de Dés.
* **Fonctionnement :** Les jetons noirs représentent l'usure du terrain, la fatigue et les dégâts incompressibles.
* **La Sanction :** En fin de tour, l'équipe doit obligatoirement les répartir et les payer en **Points de Vie (chair)** ou en **Stress (mental)**.

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

### a) Étape de la Réserve de Dés
Le joueur assemble sa réserve de dés en additionnant sa Caractéristique, sa Compétence, son Action et les éventuels bonus de ses armes ou logiciels.
* **Humains (Viande) :** Lançaient leurs dés pour obtenir des résultats bruts de couleur.
* **Mécas :** Obtiennent des **Jetons Neutres** et appliquent leur **Cascade d'Allocation** obligatoire pour les convertir.

### b) Étape de Relance
Le joueur peut déclencher des capacités spéciales, des programmes de surcharge, dépenser du Stress ou utiliser l'**Overclock** afin de relancer un ou plusieurs dés.

### c) Étape de Placement des Jetons
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

# Chapitre 7 — Le Combat

Le combat dans *Chrome & Néon* est un affrontement tactique, simultané et déterministe. Inspiré de l'architecture des duels stratégiques, il élimine la suprématie de l'initiative brute au profit d'une **phase d'enchères tactiques à l'aveugle** et d'une **résolution par strates**.

Aucune attaque ne bypass la défense : l'Armure protège contre toutes les formes d'agression, et toute frappe expose à une riposte immédiate.

---

## ⚙️ 1. Structure du Round de Combat

Chaque round de combat se déroule en **4 étapes strictes** résolues en parallèle par toutes les factions engagées :
[ Étape 1 : Lancer & Fixation ] ──> Jet des dés, placement des jetons fixes (🟢🔵🔴).
[ Étape 2 : Observation ]      ──> Analyse du plateau adverse (Télémétrie).
[ Étape 3 : Jokers à l'Aveugle]──> Allocation secrète des jetons Jokers (🌟).
[ Étape 4 : Résolution ]       ──> 🔵 Distance ──> 🔴 Mêlée ──> 🖤 Attrition

---

## 🎲 2. Déroulement des Étapes

### Étape 1 — Lancer & Fixation des Jetons
Chaque combattant constitue sa réserve de dés ($N$) et effectue son lancer.
* **Jetons Fixes (🟢, 🔵, 🔴) :** Les jetons issus des faces pures sont immédiatement placés sur la fiche dans leurs jauges respectives (Armure, Distance, Mêlée). Ils sont visibles de tous.
* **Faces Noires (🖤) :** Chaque face Noire génère immédiatement **1 Jeton d'Attrition** dans la zone d'usure du joueur qui a lancé le dé.

### Étape 2 — Temps d'Observation (Télémétrie)
Les joueurs disposent d'un temps d'analyse pour évaluer les forces en présence. La répartition des jetons fixes adverses révèle ses intentions brutes (position défensive, préparation d'une salve à distance ou charge au contact).

### Étape 3 — Allocation des Jokers (🌟) à l'Aveugle
Les faces Jokers (🌟) représentent la flexibilité tactique et la marge de manœuvre.
* Chaque joueur affecte ses jetons Jokers **face cachée** dans ses différentes jauges (Vert 🟢, Bleu 🔵 ou Rouge 🔴).
* Une fois les choix arrêtés, tous les joueurs révèlent simultanément l'affectation de leurs Jokers.

---

## ⚔️ 3. Étape 4 — Résolution Simultanée par Strates

Toutes les actions de la même strate se résolvent **en même temps**. Les blessures et l'épuisement subis n'interrompent pas les capacités d'un combattant avant qu'il n'ait pu résoudre sa propre frappe dans la strate concernée.


### Strate 1 : Phase Distance & Piratage (🔵 Bleus)
1. **Échange de Tirs :** Les jetons Bleus (🔵) engagés par les attaquants sont confrontés aux jetons Verts (🟢) de leurs cibles.
2. **Filtrage par l'Armure :** Chaque jeton Vert (🟢) annule $1$ jeton Bleu (🔵). Le surplus de Bleus dépasse le Cap de l'arme/logiciel et inflige des dégâts nets.
3. **Consommation de l'Armure :** Les jetons Verts (🟢) dépensés pour bloquer les tirs à distance sont retirés du plateau.
4. **Tir de Riposte (🔴) :** Un personnage ciblé à distance peut immédiatement dépenser ses jetons Rouges (🔴) pour effectuer un tir de couverture ou appliquer une contre-pression sur l'agresseur.

### Strate 2 : Phase de Mêlée & Impact (🔴 Rouges)
1. **Assaut au Contact :** Les jetons Rouges (🔴) engagés en attaque sont résolus.
2. **Filtrage par l'Armure Restante :** L'attaquant affronte les jetons Verts (🟢) que le défenseur a réussi à conserver après la Phase Distance.
3. **Dégâts & Riposte Mêlée :** Les jetons Rouges non bloqués infligent des blessures directes au HARDWARE ou à la chair. Le défenseur résout simultanément ses propres jetons Rouges de mêlée.

### Strate 3 : Phase d'Attrition & Friction (🖤 Noirs)
1. **Pression & Surchauffe :** On fait le bilan des jetons d'Attrition accumulés via les faces Noires (🖤) et la Pression système subie.
2. **Application de l'Usure :** L'Attrition applique des dégâts d'usure directe, du Stress de Résille ou de la détérioration de composants qui ignorent l'Armure.
3. **Nettoyage :** Tous les jetons non consommés sont défaussés avant le round suivant.

---

## 🪖 4. Règles d'Équipement & Caps

* **Cap d'Arme ($C$) :** Une arme ne peut jamais délivrer plus de $C$ jetons de dégâts (🔵 ou 🔴) par round, quelle que soit la taille de la réserve de dés lancée. Le surplus est perdu ou converti.
* **Armure Omnidirectionnelle (🟢) :** L'Armure protège contre **toutes** les attaques (Distance et Mêlée). C'est une ressource globale à répartir intelligemment entre les différentes strates du round.
