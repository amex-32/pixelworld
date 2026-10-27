# PixelWorld

Toile collaborative en temps réel, dans l'esprit de r/place : plusieurs joueurs posent des pixels sur une grille de 1000 x 1000, avec un délai entre deux poses. Serveur Node.js (Express, Socket.IO), rendu en Canvas côté navigateur. Pensé pour tourner sur un réseau local.

Projet de groupe réalisé en formation.

## Lancer le projet

```bash
npm install
node server.js
```

Le serveur affiche l'adresse locale et l'adresse réseau à donner aux autres joueurs (port 3000).

## Structure

- `server.js` : serveur, état de la grille et sauvegarde périodique
- `js/` : rendu, caméra (zoom, déplacement), réseau et interface
- `docs/cahier-des-charges.md` : cahier des charges et découpage des tâches
- `docs/ADRs/` : décisions d'architecture
