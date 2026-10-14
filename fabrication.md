## Fabrication de CDD (Custom Dice Duel)

### Impression 3D

Les pièces du jeu sont imprimées en 3D à partir des fichiers du dossier [stl/](stl). Les deux fichiers suivants doivent être imprimés avec un agrandissement de **250 %** par rapport à leur taille d'origine :

- `Dice_Forge_Dice_v1.stl` : le corps du dé. Ce modèle provient de Thingiverse, voir la référence ci-dessous.
- `faceDe.stl` : une face de dé ; il faut en imprimer au moins 6 exemplaires pour obtenir toutes les faces d'un dé.

> ⚠️ Le fichier `support_pour_xtool_f1_ultra.stl` n'est pas une pièce du jeu et ne suit pas cette règle d'agrandissement : il n'est utile que pour la gravure laser (voir le paragraphe suivant).

### Gravure laser

Une fois les faces de dé imprimées, elles sont gravées au laser pour y dessiner les icônes du jeu. Deux fichiers du dépôt sont dédiés à cette étape :

- `stl/support_pour_xtool_f1_ultra.stl` : un support à imprimer en 3D, à sa taille réelle (sans agrandissement), qui sert à maintenir les faces de dé en place lors de la gravure avec une Xtool F1 Ultra.
- `laser/gravure_laser_Xtool_F1_ultra.xs` : le fichier de gravure, à ouvrir avec xTool Creative Space, contenant le motif des icônes à graver sur chaque face.

### Références

- Corps du dé (`Dice_Forge_Dice_v1.stl`) : [Dice Forge Dice v1 sur Thingiverse](https://www.thingiverse.com/thing:3724097)
