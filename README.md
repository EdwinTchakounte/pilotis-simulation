# Pilotis - simulation du flow

Visualisation interactive et autonome du flux Pilotis (RegTech COSUMAF/CEMAC) :

- **Parcours** par declencheur (topologie animee, vitesse reglable, journal cliquable).
- **Obligations recurrentes** (simulation de l'exercice, etats des cycles).
- **Alertes & criticite** (gravite reglementaire, d'apres la base de connaissance).
- **Avis experts** (actif uniquement dans le runtime Artifact de claude.ai).

Page unique, sans backend. Donnees embarquees (jeu de demonstration, non issues de production).

## Deploiement
Site statique : `index.html` a la racine. Se deploie tel quel sur Vercel
(framework preset : "Other", aucune commande de build).
