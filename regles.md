## Règles de CDD (Custom Dice Duel)

### Principe

*Custom Dice Duel* (CDD) est un jeu de duel opposant 2 joueurs, où se mêlent stratégie et une bonne dose de chance, pour désigner le meilleur des deux.

Chaque joueur commence la partie avec 10 points de vie (PV). Le premier joueur dont les points de vie tombent à zéro perd le duel. Si les deux joueurs tombent à zéro point de vie au cours du même tour, la partie se termine sur une égalité.

Tant qu'aucun joueur n'a remporté la partie à l'issue d'un tour, un nouveau tour est joué.

### Tour de jeu

Au début de chaque tour, les deux joueurs lancent simultanément leurs 2 dés.

On résout d'abord les effets spéciaux affichés sur les dés, dans l'ordre suivant :

- la **relance** (<img src="images/icone_relancer.svg" alt="icône relance" height="20">) : le joueur **peut** relancer son **autre** dé (celui qui n'affiche pas la Relance) ; s'il choisit de le faire, seul le nouveau résultat obtenu est conservé ;
- la **récupération de points de vie** (<img src="images/icone_coeur.svg" alt="icône cœur" height="20">) : le joueur regagne le nombre de points de vie indiqué sur le dé.

Une fois ces effets résolus, chaque joueur additionne sa **force d'attaque** (<img src="images/icone_epee.svg" alt="icône épée" height="20">) et sa **défense** (<img src="images/icone_bouclier.svg" alt="icône bouclier" height="20">) à partir des faces obtenues sur ses deux dés : la valeur d'une face correspond au nombre d'icônes Épée ou Bouclier qu'elle affiche. Chaque joueur inflige alors à son adversaire des dégâts égaux à sa force d'attaque moins la défense adverse (un résultat négatif compte comme 0 dégât).

### Exemple de tour

> **Tour 4 — Alice contre Benoît**
>
> Alice lance ses 2 dés et obtient : <img src="images/icone_epee.svg" alt="icône épée" height="18"><img src="images/icone_epee.svg" alt="icône épée" height="18"><img src="images/icone_epee.svg" alt="icône épée" height="18"> **Épée × 3** (force d'attaque 3) et <img src="images/icone_bouclier.svg" alt="icône bouclier" height="18"> **Bouclier × 1** (défense 1).
>
> Benoît lance ses 2 dés et obtient : <img src="images/icone_relancer.svg" alt="icône relance" height="18"> **Relance** et <img src="images/icone_coeur.svg" alt="icône cœur" height="18"><img src="images/icone_coeur.svg" alt="icône cœur" height="18"> **Cœur × 2** (soin 2). Grâce à la Relance, Benoît **peut** choisir de relancer son autre dé (celui qui affiche les Cœurs). Il tente sa chance : ce dé relancé affiche désormais <img src="images/icone_epee.svg" alt="icône épée" height="18"><img src="images/icone_epee.svg" alt="icône épée" height="18"> **Épée × 2** (force d'attaque 2) à la place des Cœurs.
>
> Une fois tous les dés fixés :
>
> | Joueur | Force d'attaque | Défense | Autre effet |
> |---|---|---|---|
> | Alice | <img src="images/icone_epee.svg" alt="icône épée" height="16"><img src="images/icone_epee.svg" alt="icône épée" height="16"><img src="images/icone_epee.svg" alt="icône épée" height="16"> (3) | <img src="images/icone_bouclier.svg" alt="icône bouclier" height="16"> (1) | — |
> | Benoît | <img src="images/icone_epee.svg" alt="icône épée" height="16"><img src="images/icone_epee.svg" alt="icône épée" height="16"> (2) | — (0) | Aucun (les Cœurs ont été perdus en relançant) |
>
> **Calcul des dégâts**
>
> - Alice inflige à Benoît : 3 (attaque d'Alice) − 0 (défense de Benoît) = **3 dégâts**
> - Benoît inflige à Alice : 2 (attaque de Benoît) − 1 (défense d'Alice) = **1 dégât**
>
> **Bilan du tour**
>
> - Alice : 10 − 1 = **9 PV**
> - Benoît : 10 − 3 = **7 PV** (le pari de la relance ne lui a pas permis de se soigner)

### Règles d'un dé

La puissance d'une face de dé est symbolisé par un certain nombres d'étoiles (<img src="images/icone_etoile.svg" alt="icône étoile" height="16">)

- Un dé ne peut pas jamais plus du 9 étoiles.

- Un dé doit toujours avoir 6 faces.

- On ne peut pas échanger les faces de dés. Une fois installée, une face ne peut être remplacée que par une nouvelle face fraichement obtenue.


### Les faces de dés

A vous de jouer, pour l'obtention de nouvelle faces vous pouvez : 
- les cacher dans une zone de jeux (fouille)
- les donner en récompenses (quizz, épreuves, ...)
- mettre en place une boutique (achat)

### Tapis de jeu

Il est conseillé de jouer sur un sol comme un tapis pour amortir le bruit. Cela peut même devenir une variante de jeu si le tapis a des motifs (+1 en attaque si dans la couleur rouge, ...).

### Aide de jeu

Voici la liste des icônes gravées sur les faces des dés. La colonne « Effet » sera complétée au fur et à mesure que les règles de chaque face seront définies.

| Icône | Nom | Effet |
|---|---|---|
| <img src="images/icone_bouclier.svg" alt="icône bouclier" height="32"> | Bouclier | Réduit les dégâts reçus de sa valeur (défense). |
| <img src="images/icone_coeur.svg" alt="icône cœur" height="32"> | Cœur | Rend au joueur le nombre de points de vie indiqué. |
| <img src="images/icone_defense_parfaite.svg" alt="icône défense parfaite" height="32"> | Défense parfaite | Se déclenche si tous les dégâts de l'adversaire ont été bloqués, ou si ce dernier n'a infligé aucun dégât avec son attaque (aucune de ses faces ne permettant d'en infliger). Dans ce cas, on compte les symboles situés à droite de la flèche. |
| <img src="images/icone_epee.svg" alt="icône épée" height="32"> | Épée | Inflige des dégâts à l'adversaire, égaux à sa valeur (force d'attaque). |
| <img src="images/icone_etoile.svg" alt="icône étoile" height="32"> | Étoile | Indique la **puissance** d'une face de dé. |
| <img src="images/icone_faux.svg" alt="icône faux" height="32"> | Faux | Inflige un point de dégât imbloquable. |
| <img src="images/icone_multiplication.svg" alt="icône multiplication" height="32"> | Multiplication | Multiplie la valeur de l'autre dé. |
| <img src="images/icone_relancer.svg" alt="icône relance" height="32"> | Relance | Permet, si le joueur le souhaite, de relancer son autre dé ; seul le nouveau résultat est alors conservé. |

