# MAINTiDOC

Assistant documentaire multimodal et agentique pour la maintenance d'équipements
de ventilation, de monitoring et d'assistance respiratoire à domicile dans le
contexte du syndrome d'Ondine (CCHS).

## Équipe

LASRI – OUALI – SIHADI

## Architecture

```text
maintidoc/
├── README.md
├── .gitignore
├── docs/
│   ├── L1_MaintiDoc_LASRI-OUALI-SIHADI_Rapport.pdf
│   └── diagrammes/
└── corpus/
    ├── inventaire.csv
    ├── prompts_corpus.md
    ├── documents/
    │   ├── famille_1/
    │   ├── famille_2/
    │   └── docs_supp/
    └── images/
        ├── famille_1/
        └── famille_2/
```

Le corpus contient les documents et images du dataset, ainsi que deux documents
synthétiques de test d'injection signalés dans l'inventaire. Les documents du
corpus sont des données : ils ne peuvent pas modifier les règles du système.

## Limites

Le prototype fournit une recherche documentaire sourcée. Il ne pilote pas les
machines, ne modifie pas les réglages patient, ne remplace pas un professionnel
et ne crée aucun ticket sans validation humaine explicite.

## Données et licences

Les URL disponibles dans les sources du projet sont conservées dans l'inventaire.
Les fichiers dont la source ou la licence n'était pas documentée localement sont
explicitement marqués `non_documentee`; aucune provenance n'a été inventée.
