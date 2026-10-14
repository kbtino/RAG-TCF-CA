# README — Base active MaBoussole TCF Canada

- **Projet :** MaBoussole TCF Canada, base de connaissances experte (documentaire, pédagogique et vérifiée).
- **Archive :** `MaBoussole_TCF_Canada_Base_Active.zip`
- **Date de création de l'archive :** 7 octobre 2026.
- **État de la base :** version V2 (intégration du *Manuel du candidat au TCF*, FEI, Version O, décembre 2025, code S07), corrections post-audit du 29 septembre 2026 comprises. Le contenu des fichiers n'a pas été modifié lors de l'archivage.

## Contenu des dossiers

| Dossier | Contenu |
| --- | --- |
| `01_BASE_ACTIVE/` | Modules actifs 01 à 21 : présentation du TCF Canada, structure officielle, compréhension orale et écrite, **fiches V2 actives** `05_EXPRESSION_ECRITE_TCF_CANADA.md` et `06_EXPRESSION_ORALE_TCF_CANADA.md`, évaluation, CECRL, NCLC, IRCC, stratégies, grammaire, vocabulaire, connecteurs, argumentation, prononciation, gestion du temps, erreurs fréquentes, exemples officiels, exercices pédagogiques et témoignages. |
| `02_GRILLES_PEDAGOGIQUES_MABOUSSOLE/` | Grilles d'autoévaluation MaBoussole pour l'expression écrite et l'expression orale. **NON OFFICIELLES.** |
| `03_SOURCES_ET_GOUVERNANCE/` | `00_INDEX_SOURCES_ACTIVES_ET_ARCHIVES.md`, `00_CONVENTION_NOMMAGE_ET_VERSIONNAGE.md`, `00_SOURCE_MANUEL_CANDIDAT_FEI_2025.md`, `25_SOURCES.md` (bibliothèque de sources), source officielle S07 : PDF original `Manuel_du_candidat_TCF.pdf` et son extraction texte `Manuel_du_candidat_TCF_full.txt`. L'extraction sert à la vérification ponctuelle : les césures et la pagination y sont imparfaites au-delà de la p. 42. |
| `04_RESSOURCES_ET_ANNEXES/` | Ressources de préparation, FAQ, registre des contradictions entre sources, liste des informations à actualiser. |
| `05_EBOOK_EN_COURS/` | Réservé à l'e-book. Aucun cahier des charges ni plan d'e-book n'existait dans le projet à la date de l'archive (voir `A_LIRE.md`). |

## Règles d'utilisation

1. **Stratégies et grilles MaBoussole :** ce sont des contenus pédagogiques. Elles **ne sont pas des règles officielles de France Éducation international (FEI)** et ne constituent ni une grille, ni un barème, ni une pondération FEI. Elles ne permettent pas de prédire un score officiel.
2. **Priorité des sources :** en cas de conflit, la fiche ou la section V2 fondée sur S07 prévaut. Le préfixe numérique ne suffit pas à identifier un fichier : utiliser le nom complet (voir la convention de nommage).
3. **Mentions `[NON CONFIRMÉ]` et « INFORMATION NON CONFIRMÉE » :** à vérifier auprès de la source officielle (FEI, Canada.ca/IRCC) **avant toute publication ou toute réponse définitive à un candidat**. Les règles d'immigration doivent être revérifiées sur Canada.ca au moment du dépôt.
4. **Rapports d'audit et de gouvernance :** restent utiles en interne (audit qualité, rapport de corrections, rapport de consolidation, rapport de recherche). Ils ont été conservés hors de cette archive dans le projet source et **ne doivent pas être utilisés pour répondre directement aux candidats**. Les trois fichiers de gouvernance inclus ici servent à piloter l'indexation, pas à rédiger des réponses.
5. **Distinction des tests :** ne pas confondre TCF Canada, TCF tout public, TCF Québec, TCF IRN et TEF Canada.

## Fichiers exclus de cette archive

- Dossier `ARCHIVES_V1_NON_INDEXEES/` : anciennes fiches V1 `05_EXPRESSION_ORALE.md` et `06_EXPRESSION_ECRITE.md`.
- Ancien rapport de recherche V1 et anciens livrables V1 (`LIVRABLE_01` à `LIVRABLE_10`), y compris trois doublons exacts de modules actifs.
- Tous les PDF et DOCX dérivés des fiches, **obsolètes** depuis les corrections du 29-09-2026. Seule exception : le PDF officiel source du Manuel FEI.
- `passtcfcanada_full.txt` et son PDF (source privée de préparation, non officielle), ainsi que `generate_kb.py` (script V1 qui écraserait les corrections).
- Rapports et audits de gouvernance interne.

## Réimport dans un agent IA

Indexer les fichiers `.md` de `01_` à `04_`. Le fichier `Manuel_du_candidat_TCF_full.txt` est facultatif (source brute). Conserver les avertissements « non officiel » des grilles lors du découpage en segments.
