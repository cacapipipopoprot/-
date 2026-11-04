# La Nuit au Musée de Cire — Fan Game (1 seule nuit)

Fan game jouable inspiré du concept "gardien de nuit" (type FNAF), en **une seule nuit de 12 AM à 6 AM** (~5 minutes réelles). Non affilié à FNAF.

## Personnages (historiques, statues de cire animées)

- 🎩 **Napoléon** — rapide, attaque par la porte gauche
- 👑 **Cléopâtre** — passe par l'entrée, attaque par la droite
- ⚔️ **Jeanne d'Arc** — surgit de la cuisine, attaque par la droite
- 🧑‍🔬 **Einstein** — imprévisible, peut choisir les deux côtés

## Mécaniques originales (absentes de FNAF)

- 🌡️ **Chauffage du musée (R/F)** : monter la température ramollit la cire et ralentit toutes les statues (mouvement et attaque), mais la batterie se vide beaucoup plus vite. Compromis permanent à gérer.
- 🔥 **Chalumeau à cire (X/V)** : 3 charges max, 1 charge rechargée toutes les 40 s. Si une statue est à la porte visée, un jet de cire brûlante la renvoie **2 salles en arrière** et l'étourdit **10 secondes**.

## Comment jouer

Ouvre `index.html` dans un navigateur (aucun serveur nécessaire).

L'écran des **caméras (C)** affiche une **carte du musée** : chaque salle est placée comme sur un plan, les emojis montrent la position des statues en direct, et un ⚠️ rouge clignotant signale une statue à une porte.

- **Survivre jusqu'à 6 AM** en surveillant la carte des caméras, en fermant les portes et en utilisant les lumières.
- La **batterie** se vide en permanence (plus vite avec portes fermées, lumières, caméras et chauffage). À 0 %, tout s'éteint...
- Si une statue atteint une porte et que celle-ci est ouverte, c'est le jumpscare.
- Le HUD affiche la batterie ⚡, l'heure avec la progression 12→6 h, et un bandeau ⚠️ quand une statue est à une porte.

### Contrôles

| Touche | Action |
|---|---|
| A | Porte gauche |
| Z | Lumière gauche |
| C (ou Espace) | Monter/baisser les caméras |
| 1-7 (ou clic sur la carte) | Changer de caméra |
| E | Lumière droite |
| D | Porte droite |
| R / F | Chauffage + / − (ralentit la cire, coûte de la batterie) |
| X / V | Chalumeau à cire gauche / droite |

Tout est aussi cliquable à la souris.
