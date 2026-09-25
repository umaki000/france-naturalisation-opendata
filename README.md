# France Naturalisation Infos — Données ouvertes

Jeux de données compilés par [France Naturalisation Infos](https://france-naturalisation.net), site d'information indépendant sur la procédure de naturalisation française, publiés en libre réutilisation sous [Licence Ouverte / Open Licence 2.0](https://www.etalab.gouv.fr/licence-ouverte-open-licence/).

Ces mêmes jeux de données sont également référencés sur [data.gouv.fr](https://www.data.gouv.fr/organizations/france-naturalisation-infos), la plateforme officielle des données publiques françaises.

## Jeux de données

### 1. Centres d'examen DELF/DALF en France
140 centres agréés pour passer le DELF ou le DALF (diplômes de français langue étrangère) en France métropolitaine et outre-mer. Le DELF B2 est l'un des diplômes reconnus pour justifier de la maîtrise du français exigée lors d'une demande de naturalisation.

- [`centres-delf-dalf.csv`](./centres-delf-dalf.csv)
- [`centres-delf-dalf.json`](./centres-delf-dalf.json)
- Colonnes : `nom_centre`, `adresse`, `code_postal`, `ville`, `telephone`, `email`, `site_web`, `latitude`, `longitude`

### 2. Centres d'examen civique et TCF pour la naturalisation
429 centres où passer le test de connaissance du français (TCF) et l'évaluation civique requis dans le cadre d'une demande de naturalisation.

- [`centres-examen-civique.csv`](./centres-examen-civique.csv)
- [`centres-examen-civique.json`](./centres-examen-civique.json)
- Colonnes : `nom_centre`, `adresse`, `code_postal`, `ville`, `site_web_inscription`, `latitude`, `longitude`

### 3. Naturalisations françaises par nationalité d'origine (2016-2026)
Nombre de personnes naturalisées françaises par décret entre 2016 et 2026, par nationalité d'origine, avec répartition femmes/hommes — compilé à partir des décrets publiés au Journal officiel.

- [`naturalisations-nationalite.csv`](./naturalisations-nationalite.csv)
- [`naturalisations-nationalite.json`](./naturalisations-nationalite.json)
- Colonnes : `nationalite`, `naturalisations_2016_2026`, `rang_national`, `part_femmes_pct`, `part_hommes_pct`, `fiche_pays_url`

## Sources et mises à jour

Les fichiers de ce dépôt sont des instantanés. Les versions les plus à jour sont toujours disponibles directement sur le site :

- https://france-naturalisation.net/donnees-ouvertes
- https://france-naturalisation.net/centres-delf-dalf.csv
- https://france-naturalisation.net/centres-examen-civique.csv
- https://france-naturalisation.net/naturalisations-nationalite.csv

## Licence

[Licence Ouverte / Open Licence 2.0](https://www.etalab.gouv.fr/licence-ouverte-open-licence/) — réutilisation libre, y compris commerciale, sous réserve de mention de la source ("France Naturalisation Infos — france-naturalisation.net").

## Contact

info@france-naturalisation.net
