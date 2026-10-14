# Index des sources actives et des archives — Base MaBoussole TCF Canada

> **Catégorie : RAPPORT (gouvernance d'indexation).** Créé le 29 septembre 2026 dans le cadre des corrections post-audit (voir `11_RAPPORT_CORRECTIONS_POST_AUDIT.md`). Ce fichier indique à l'agent IA et aux rédacteurs **quels fichiers utiliser pour répondre** et **lesquels ne jamais utiliser comme source autonome**. Il ne crée aucune règle TCF.

## 1. Règle de priorité

> **En cas de conflit entre une fiche V1 et une fiche V2, la fiche V2 fondée sur S07 prévaut systématiquement. Les fiches archivées V1 ne doivent jamais être utilisées comme source autonome pour produire une réponse destinée à un candidat.**

Règles complémentaires (rappel de la gouvernance existante, sans ajout de règle d'examen) :

- Le préfixe numérique ne suffit pas à identifier un fichier : utiliser le nom de fichier complet (voir `00_CONVENTION_NOMMAGE_ET_VERSIONNAGE.md`).
- Dans un module contenant une section V1 et une section « Mise à jour V2 — Manuel FEI », la section V2 prévaut pour les éléments qu'elle cite.
- Les grilles MaBoussole sont **pédagogiques et non officielles** ; elles ne doivent jamais être présentées comme des grilles, barèmes ou pondérations de France Éducation international.
- Toute règle d'immigration doit être revérifiée sur Canada.ca au moment du dépôt.

## 2. Sources actives prioritaires

| Fichier | Catégorie | Statut | Priorité / nature | Usage |
| --- | --- | --- | --- | --- |
| `05_EXPRESSION_ECRITE_TCF_CANADA.md` | FICHE_TCF_CANADA | Active (V2) | **Priorité haute** | Fiche de référence pour l'expression écrite du TCF Canada (fondée sur S07). |
| `06_EXPRESSION_ORALE_TCF_CANADA.md` | FICHE_TCF_CANADA | Active (V2) | **Priorité haute** | Fiche de référence pour l'expression orale du TCF Canada (fondée sur S07). |
| `07_GRILLE_PEDAGOGIQUE_MABOUSSOLE_EXPRESSION_ECRITE.md` | GRILLE_PEDAGOGIQUE | Active | **Pédagogique non officiel** | Autoévaluation et correction formative en EE ; jamais présentée comme grille FEI. |
| `08_GRILLE_PEDAGOGIQUE_MABOUSSOLE_EXPRESSION_ORALE.md` | GRILLE_PEDAGOGIQUE | Active | **Pédagogique non officiel** | Autoévaluation et correction formative en EO ; jamais présentée comme grille FEI. |
| `00_SOURCE_MANUEL_CANDIDAT_FEI_2025.md` | SOURCE | Active | **Officiel** (S07, [OFFICIEL, A]) | Fiche descriptive du *Manuel du candidat au TCF*, Version O, décembre 2025 : pages pertinentes, contradictions internes, pagination. |
| `LIVRABLE_01_RAPPORT_RECHERCHE_V2.md` | RAPPORT | Active | **Gouvernance** | Méthode de qualification, hiérarchie des sources, lacunes maintenues ; ne pas citer comme source d'une règle d'examen. |

## 3. Autres fichiers actifs (modules thématiques)

| Fichier | Catégorie | Remarque |
| --- | --- | --- |
| `01_TCF_CANADA_OVERVIEW.md` | MODULE | Vue d'ensemble ; passage V1 sur le Manuel marqué dépassé. |
| `02_OFFICIAL_STRUCTURE.md` | MODULE | Section V2 prioritaire ; phrase V1 sur l'oral marquée remplacée. |
| `03_COMPREHENSION_ORALE.md` | MODULE | — |
| `04_COMPREHENSION_ECRITE.md` | MODULE | — |
| `07_EVALUATION.md` | MODULE | Résultats, NCLC, délais (précision de variante ajoutée). |
| `08_CECRL.md` | MODULE | — |
| `09_NCLC.md` | MODULE | Cibles de préparation requalifiées. |
| `10_IRCC_IMMIGRATION.md` | MODULE | Exemples de programmes marqués [NON CONFIRMÉ] : revérifier sur Canada.ca. |
| `11_STRATEGIES.md` à `20_EXERCICES_PEDAGOGIQUES.md` | MODULE | Contenus pédagogiques et experts ([EXPERT, C], [ACADÉMIQUE, B]) ; non officiels. |
| `21_TEMOIGNAGES_CANDIDATS.md` | MODULE | Thèmes V1 marqués « source non traçable ». |
| `22_RESSOURCES.md` | MODULE | URL des exemples FEI EO/EE vérifiées le 29-09-2026. |
| `23_FAQ.md` | MODULE | Réponses V1 dépassées signalées ; section V2 prioritaire. |
| `24_CONTRADICTIONS.md`, `25_SOURCES.md`, `26_INFORMATION_A_ACTUALISER.md` | MODULE | Gouvernance documentaire intégrée aux modules. |

## 4. Fichiers de gouvernance (ne pas utiliser pour répondre à un candidat)

| Fichier | Catégorie | Usage |
| --- | --- | --- |
| `00_INDEX_SOURCES_ACTIVES_ET_ARCHIVES.md` | RAPPORT | Présent index. |
| `00_CONVENTION_NOMMAGE_ET_VERSIONNAGE.md` | RAPPORT | Convention d'identification des fichiers. |
| `RAPPORT_CONSOLIDATION_V2.md` | RAPPORT | Journal de l'intégration V2 et points ouverts. |
| `10_AUDIT_QUALITE_POST_INTEGRATION_MANUEL_FEI.md` | AUDIT | Audit qualité (anomalies A01–A19). |
| `11_RAPPORT_CORRECTIONS_POST_AUDIT.md` | RAPPORT | Suivi des corrections post-audit. |
| `LIVRABLE_02_ARCHITECTURE.md` à `LIVRABLE_10_AGENT_IA_CHECKLIST.md` | RAPPORT | Livrables de conception V1 ; non audités sur S07. En cas d'écart, les modules V2 et `LIVRABLE_01_RAPPORT_RECHERCHE_V2.md` prévalent. |

## 5. Archives (non indexées)

| Fichier | Emplacement | Catégorie | Remplacé par | Consigne |
| --- | --- | --- | --- | --- |
| `05_EXPRESSION_ORALE.md` | `ARCHIVES_V1_NON_INDEXEES/` | ARCHIVE | `06_EXPRESSION_ORALE_TCF_CANADA.md` | **Ne pas utiliser pour répondre ; consulter uniquement pour l'historique.** |
| `06_EXPRESSION_ECRITE.md` | `ARCHIVES_V1_NON_INDEXEES/` | ARCHIVE | `05_EXPRESSION_ECRITE_TCF_CANADA.md` | **Ne pas utiliser pour répondre ; consulter uniquement pour l'historique.** |
| `LIVRABLE_01_RAPPORT_RECHERCHE.md` | racine (non déplacé) | ARCHIVE | `LIVRABLE_01_RAPPORT_RECHERCHE_V2.md` | Version V1 du rapport de recherche : exclure de l'indexation ; historique uniquement. |

Le dossier `ARCHIVES_V1_NON_INDEXEES/` doit être **exclu en totalité** du pipeline d'indexation.

## 6. Fichiers non Markdown (hors indexation par défaut)

| Fichier(s) | Statut | Consigne |
| --- | --- | --- |
| `*.pdf`, `*.docx` (00_SOURCE, 05_EE, 06_EO, 07_GRILLE, 08_GRILLE, 10_AUDIT, 23_FAQ, RAPPORT_CONSOLIDATION_V2, LIVRABLE_01 V1) | **Obsolètes** depuis les corrections du 29-09-2026 (non régénérés) | Ne pas indexer. Seuls les fichiers `.md` font foi. |
| `Manuel_du_candidat_TCF_full.txt` | SOURCE brute (extraction texte de S07) | Vérification ponctuelle uniquement ; césures et pagination imparfaites (voir note de méthode dans `00_SOURCE_MANUEL_CANDIDAT_FEI_2025.md`). |
| `passtcfcanada_full.txt` | SOURCE privée de préparation — **NON officielle** ([EXPERT, C]) | Ne jamais indexer comme source officielle ; sujets et corrigés non officiels et non prédictifs. |
| `generate_kb.py` | Script de génération V1 | **Ne pas exécuter** : il recréerait à la racine les fiches V1 `05_EXPRESSION_ORALE.md` et `06_EXPRESSION_ECRITE.md` et écraserait les modules corrigés. |
