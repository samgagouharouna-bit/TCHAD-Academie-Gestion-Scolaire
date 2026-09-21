# TCHAD ACADÉMIE — Gestion Scolaire V2

Application desktop Windows + macOS basée sur le prototype fourni.

## Modules
- Tableau de bord
- Élèves et dossiers
- Enseignants
- Classes & matières
- Notes & bulletins
- Présences
- Paiements / frais scolaires
- Emploi du temps
- Rapports & statistiques
- Utilisateurs
- Paramètres établissement
- Sauvegarde/restauration locale
- Impression / export PDF via l’application

## Installation développeur
1. Installer Node.js LTS.
2. Dans ce dossier : `npm install`
3. Tester : `npm start`
4. Générer les installateurs : `npm run build`

Les fichiers Windows sont générés dans `dist/` (NSIS + portable) et les fichiers macOS dans `dist/` (DMG + ZIP).

## Stockage
Les données sont stockées localement dans le dossier de données utilisateur d’Electron. Le menu **Fichier** permet de sauvegarder/restaurer une sauvegarde JSON.

## Identité
AGROFOOD BUSINESS AND TECHNOLOGY SERVICES (ABTS) — Moundou, Tchad.

## Identité visuelle
Le logo officiel TCHAD ACADÉMIE est intégré dans l’interface, le favicon et l’icône Windows de l’application.

## Corrections V2.1
- Conservation correcte des frais Primaire, Collège et Lycée après redémarrage.
- Modification des frais Primaire, Collège et Lycée depuis Paiements.
- Les classes et matières personnalisées sont maintenant utilisées dans les formulaires, notes et emplois du temps.
- Logo TCHAD ACADÉMIE intégré à l’interface et aux ressources de l’application.
