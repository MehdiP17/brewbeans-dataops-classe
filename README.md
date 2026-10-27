# Brew Beans — DataOps (Module 07)

Projet pédagogique fictif : apprendre Git, GitHub et Markdown en travaillant sur des ventes de cafés.

## Références communes

- `data/reference/ventes_reference.csv` : **40 transactions** historiques (ne pas modifier).
- `data/reference/magasins.csv` : référentiel des magasins.
- `data/livraisons/livraison_paris_20261026.csv` : **3 nouvelles transactions**, dont `BB-041` est enregistrée à **40,00 EUR** avant correction officielle à **45,00 EUR**.
- `scripts/reference/preparer_ventes.py` : script pandas fourni à copier, puis à adapter en remplaçant uniquement la constante `GROUPE`.

## Travail individuel avec fork

- Chaque étudiant crée son **fork** à partir du dépôt du formateur (bouton GitHub « Fork »), puis clone **son propre fork**.
- Chaque étudiant travaille sur une branche `nompromo_groupeN` (exemple : `daft-ft-21_groupe1`) dans son fork. Le numéro N est attribué par le formateur.
- Données produites : `data/groupeN/livraison_corrigee.csv` et `data/groupeN/ventes.csv`.
- Script Python pandas : `scripts/groupeN/preparer_ventes.py`.
- Documentation : `docs/groupeN/README.md`.

Chaque étudiant publie sa branche dans **son fork personnel**, sans invitation comme collaborateur au dépôt d’origine. **Une seule Pull Request sera présentée par un volontaire**, de son fork vers le dépôt d’origine et la branche `main`. Il n’est pas demandé à chaque étudiant d’ouvrir une PR.

## Conditions d'exécution

Depuis la racine du dépôt, avec Python et pandas installés :

```bash
python scripts/groupe1/preparer_ventes.py
```

Cette commande n'est utilisable qu'après la préparation des fichiers du groupe. Remplacer `groupe1` pour les autres binômes et adapter la constante `GROUPE` du script.

Les données sont entièrement fictives. Ne pas publier de données clients réelles ni de secrets.
