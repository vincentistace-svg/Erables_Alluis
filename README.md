# Érablière – suivi des placettes

Application web pour smartphone : suivi des 19 placettes d'érables plantées en février 2007 (25 plants par placette, 5 × 5 à 1 m).

- **Parcelle** : plan des 19 placettes (disposition du fichier d'origine), coloré selon la circonférence du plus gros érable, le nombre d'érables ou l'ancienneté de la dernière coupe. Toucher une placette ouvre son historique.
- **Mesurer** : date, placette, nombre d'érables, circonférence (cm) des 1 à 3 plus gros, remarques.
- **Bois** : campagnes de prélèvement (date, stères, placettes, remarque), graphique annuel et cumul. Les campagnes 2019 à 2025 sont préchargées.
- **Données** : sauvegarde / restauration JSON, export CSV pour Excel ou Numbers.

## Mise en ligne sur GitHub Pages

1. Créer un dépôt (ex. `erabliere`) et y déposer tous les fichiers de ce dossier.
2. *Settings → Pages → Build and deployment* : Source « Deploy from a branch », branche `main`, dossier `/ (root)`.
3. L'adresse s'affiche après une minute : `https://<utilisateur>.github.io/erabliere/`.
4. Sur le téléphone, ouvrir l'adresse puis « Ajouter à l'écran d'accueil ». L'application fonctionne ensuite hors connexion.

## Où sont les données ?

Dans le navigateur du téléphone (stockage local), pas sur GitHub. Le dépôt ne contient que l'application ; vos mesures restent privées même si le dépôt est public. Exportez régulièrement une sauvegarde (onglet Données) : elle permet de changer de téléphone ou de restaurer les données si le navigateur est réinitialisé.
