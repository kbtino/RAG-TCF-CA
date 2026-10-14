# Convention de nommage et de versionnage — Base MaBoussole TCF Canada

> **Catégorie : RAPPORT (gouvernance documentaire).** Créé le 29 septembre 2026 pour traiter l'anomalie A16 de l'audit (`10_AUDIT_QUALITE_POST_INTEGRATION_MANUEL_FEI.md`). **Aucun fichier n'est renommé** : ce document fixe la manière d'identifier les fichiers existants sans ambiguïté.

## 1. Convention

> **Le préfixe numérique ne doit pas être utilisé seul comme identifiant documentaire. L'identifiant officiel est le nom de fichier complet, accompagné d'une catégorie : `SOURCE`, `MODULE`, `FICHE_TCF_CANADA`, `GRILLE_PEDAGOGIQUE`, `RAPPORT`, `AUDIT` ou `ARCHIVE`.**

Exemple de citation correcte : `05_EXPRESSION_ECRITE_TCF_CANADA.md` (FICHE_TCF_CANADA). Exemple incorrect : « la fiche 05 ».

## 2. Définition des catégories

| Catégorie | Définition | Indexation pour réponses candidats |
| --- | --- | --- |
| `SOURCE` | Fiche décrivant une source primaire du corpus (ex. Manuel FEI, S07). | Oui |
| `MODULE` | Module thématique de la base (01 à 26, hors fiches TCF Canada spécialisées). | Oui |
| `FICHE_TCF_CANADA` | Fiche V2 approfondie consacrée à une épreuve du TCF Canada, fondée sur S07. | Oui — priorité haute |
| `GRILLE_PEDAGOGIQUE` | Outil d'évaluation formative MaBoussole, **non officiel**. | Oui, avec mention « non officiel » obligatoire |
| `RAPPORT` | Document de gouvernance, de méthode, de suivi ou d'index. | Non (usage interne) |
| `AUDIT` | Rapport de contrôle qualité. | Non (usage interne) |
| `ARCHIVE` | Version remplacée, conservée pour l'historique. | **Non — jamais** |

## 3. Collisions de préfixes documentées

| Préfixe | Fichier 1 (catégorie) | Fichier 2 (catégorie) | Risque | Résolution |
| --- | --- | --- | --- | --- |
| 05 | `05_EXPRESSION_ECRITE_TCF_CANADA.md` (FICHE_TCF_CANADA, active) | `05_EXPRESSION_ORALE.md` (ARCHIVE, V1) | Même préfixe, **thèmes inversés** (écrit / oral) | V1 archivée dans `ARCHIVES_V1_NON_INDEXEES/` avec bandeau. |
| 06 | `06_EXPRESSION_ORALE_TCF_CANADA.md` (FICHE_TCF_CANADA, active) | `06_EXPRESSION_ECRITE.md` (ARCHIVE, V1) | Même préfixe, **thèmes inversés** (oral / écrit) | V1 archivée dans `ARCHIVES_V1_NON_INDEXEES/` avec bandeau. |
| 07 | `07_EVALUATION.md` (MODULE) | `07_GRILLE_PEDAGOGIQUE_MABOUSSOLE_EXPRESSION_ECRITE.md` (GRILLE_PEDAGOGIQUE) | Confusion entre évaluation officielle et grille non officielle | Citer le nom complet et la catégorie. |
| 08 | `08_CECRL.md` (MODULE) | `08_GRILLE_PEDAGOGIQUE_MABOUSSOLE_EXPRESSION_ORALE.md` (GRILLE_PEDAGOGIQUE) | Confusion entre cadre officiel (CECR) et grille non officielle | Citer le nom complet et la catégorie. |
| 10 | `10_IRCC_IMMIGRATION.md` (MODULE) | `10_AUDIT_QUALITE_POST_INTEGRATION_MANUEL_FEI.md` (AUDIT) | Un audit interne pourrait être indexé comme contenu d'immigration | L'audit est exclu des réponses candidats. |
| 11 | `11_STRATEGIES.md` (MODULE) | `11_RAPPORT_CORRECTIONS_POST_AUDIT.md` (RAPPORT) | Collision créée par le rapport post-audit | Le rapport est exclu des réponses candidats. |

## 4. Règles de versionnage

1. **V1** : fichiers issus de la première génération de la base (sources S01–S06).
2. **V2** : intégration du *Manuel du candidat au TCF* FEI, Version O, décembre 2025 (S07), soit par une section « Mise à jour V2 — Manuel FEI » ajoutée à un module, soit par une fiche `FICHE_TCF_CANADA` dédiée.
3. **Correctifs post-audit** : marqués dans le texte par la mention « correctif post-audit » suivie, lorsque c'est utile, de l'identifiant d'anomalie (A01–A19) et de la date du 29-09-2026.
4. Un passage V1 remplacé est **marqué** (barré, bandeau ou mention « dépassé »), jamais supprimé silencieusement.
5. Une fiche entièrement remplacée reçoit un bandeau « FICHE ARCHIVÉE » et est déplacée dans `ARCHIVES_V1_NON_INDEXEES/`.
6. Les versions PDF/DOCX ne font pas foi : seul le fichier `.md` est la version de référence.
7. Tout nouveau fichier doit porter un nom explicite, unique sans son préfixe, et être ajouté à `00_INDEX_SOURCES_ACTIVES_ET_ARCHIVES.md` avec sa catégorie.

## 5. Format des balises de qualification

Format de référence : `[NATURE, LETTRE]`, par exemple [OFFICIEL, A], [INSTITUTIONNEL, B], [INFÉRENCE, C], [EXPERT, C], [TÉMOIGNAGE, D], ou la mention [NON CONFIRMÉ]. La source éventuelle est notée à part, par exemple `[OFFICIEL, A] [S01]`. Les autres combinaisons admises par la méthode de `LIVRABLE_01_RAPPORT_RECHERCHE_V2.md` (§2.1-2.2), comme [OFFICIEL, B] (source officielle unique ou accès incomplet) ou [ACADÉMIQUE, B], restent valides.
