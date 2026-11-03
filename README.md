# Padel POV 🎾

Un jeu de padel en 3D à la première personne, jouable directement dans le navigateur (Three.js).
Vue « casque VR » sans casque : vous voyez votre raquette devant vous et affrontez un adversaire contrôlé par l'ordinateur. Premier à 7 points.

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

- Terrain bleu, lignes blanches, filet, parois vitrées et grillages
- 5 couleurs de raquette : rouge, bleu, vert, jaune, violet
- Assistance légère : portée de frappe généreuse, balle qui passe toujours le filet, anneau indiquant le point de rebond, raquette qui s'illumine quand la balle est à portée
- Balle lumineuse avec traînée et ombre au sol
- Rebonds sur le sol et les vitres, règles de padel simplifiées
- Sons générés (frappe, rebond, vitre, filet, points)
- Écran d'accueil, pause, écran de fin avec « Rejouer »

## Réglages

Dans `index.html` : sensibilité souris (`0.0022`), vitesse du joueur (`5.5`), taux d'erreur de l'ordi (`0.13`), portée de frappe (`2.1`).

## Licence

[MIT](LICENSE)
