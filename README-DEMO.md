# GestPilot — démonstration publique

Démonstration autonome de GestPilot (gestion de flotte et de paie de chauffeurs), destinée à GitHub Pages. **Tout est fictif** : le jeu de données de `data.js` (véhicules `DEMO-…`, courriels `example.com`) et les noms du modèle de Préfac sont inventés. Code d’accès affiché à l’écran : `flotte2026`.

## Ce que montre cette version (état du 17/11/2026)

- **Accueil** : « Bonjour », ce qu’il faut traiter aujourd’hui, raccourcis.
- **Flotte** : vue d’ensemble, véhicules et leurs fiches (échéances, kilométrage, vidanges, incidents, documents), locations, dépôts, alertes, archives.
- **Paie** : récap du jour par dépôt (statuts rapides, cycles SameDay, FC du jour, validation), grille du mois, fiches salariés (rémunération, documents, primes et retenues, historique de dépôt), éléments variables, dépôts.
- **Direction** : Récap Routes (routes attendues / payées, à réclamer) et **Suivi Préfac** en tuiles à la suite (ronds + − · = ×, apparence réglable, PDF).
- **Administration** : dépôts (services NextDay / SameDay), utilisateurs.
- Fil d’Ariane, bouton « Retour », tuiles cliquables.

## Déployer sur GitHub Pages

1. Dans le dépôt GitHub, remplacez les fichiers de la racine par ceux de ce dossier : `index.html`, `app.js`, `styles.css`, `data.js`, `README-DEMO.md` et le dossier `logos/`.
2. Dans **Settings → Pages**, vérifiez : **Deploy from a branch**, branche `main`, dossier `/(root)`.
3. Attendez la publication par GitHub Pages et ouvrez l’URL indiquée dans les paramètres Pages.

## Limites de sécurité — démonstration uniquement

Le code d’accès et les contrôles de rôle sont exécutés côté navigateur et visibles/modifiables dans les fichiers publics : ils ne constituent **ni une authentification ni une autorisation sécurisée**. Les données modifiées sont stockées localement dans le navigateur ; il n’y a ni serveur, ni chiffrement de stockage, ni contrôle d’accès fiable, ni sauvegarde centralisée. N’y saisissez ou n’y importez aucune donnée personnelle, réelle, confidentielle ou de production. Une publication GitHub Pages rend les fichiers accessibles publiquement.
