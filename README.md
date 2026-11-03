# Padel POV 🎾

Un jeu de padel en 3D à la première personne, jouable directement dans le navigateur (Three.js).
Vue « casque VR » sans casque : choisissez votre star (Ronaldo, Messi, Neymar ou Mbappé) et affrontez l'ordinateur en 1 contre 1 ou en 2 contre 2 avec un coéquipier, dans un stade aux tribunes rouges inspiré d'Anfield. Premier à 7 points.

## Lancer le jeu

- **En ligne :** 👉 [jouer sur yannirabia.github.io/padel-pov](https://yannirabia.github.io/padel-pov/)
- **Le plus simple :** ouvrez `index.html` dans Chrome, Firefox ou Safari (connexion Internet requise pour charger Three.js).
- **Si la page reste noire :** lancez un serveur local dans le dossier, puis ouvrez http://localhost:8000
  ```bash
  python3 -m http.server 8000
  ```

## Commandes

| Action | Touche |
| --- | --- |
| Se déplacer | `Z` `Q` `S` `D` (ou `W` `A` `S` `D`) ou flèches |
| Regarder / viser | Souris |
| Frapper / servir | Clic gauche ou `Espace` |
| Lob | Regarder vers le haut en frappant |
| Balle courte | Regarder vers le bas en frappant |
| Pause | `Échap` |

## Fonctionnalités

- 2 modes : **1 contre 1** ou **2 contre 2** (votre coéquipier couvre l'autre moitié du terrain)
- 4 personnages au choix — Ronaldo, Messi, Neymar, Mbappé — avec maillot, numéro et nom, animés (course, frappe)
- 3 niveaux : **Amateur**, **Pro**, **Expert** — l'adversaire court plus vite, se trompe moins et frappe plus fort et plus près des lignes à chaque niveau
- Stade avec quatre tribunes pleines de supporters qui sautent à chaque point
- Terrain bleu, lignes blanches, filet, parois vitrées et grillages
- 5 couleurs de raquette : rouge, bleu, vert, jaune, violet
- Assistance légère : portée de frappe généreuse, balle qui passe toujours le filet, anneau indiquant le point de rebond, raquette qui s'illumine quand la balle est à portée
- Balle lumineuse avec traînée et ombre au sol
- Rebonds sur le sol et les vitres, règles de padel simplifiées
- Sons générés (frappe, rebond, vitre, filet, points)
- Écran d'accueil, pause, écran de fin avec « Rejouer »

## Réglages

Dans `index.html` : sensibilité souris (`0.0022`), vitesse du joueur (`5.5`), niveaux de difficulté (objet `LEVELS` : vitesse des adversaires, taux d'erreur, puissance, portée de frappe).

## Licence

[MIT](LICENSE)
