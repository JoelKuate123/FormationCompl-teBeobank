# Formation Complète Beobank

Support de formation Python (NumPy/Pandas) et SQL, bâti sur un dataset bancaire fictif "Beobank" (5 tables relationnelles). Formation d'une journée (9h00–16h30), matin Pandas / après-midi SQL, sur les mêmes questions métier pour comparaison directe.


## Structure du dépôt

```
data/                              CSV source (CTR, TIE, TIE_ADR, TIE_X_CTR, TXN_X_CTR)
dataset/                           Présentation du dataset Beobank
cours_structures_donnees/          Listes, dicts, tuples (bases Python)
cours_numpy_pandas/                Cours NumPy et Pandas (fondamentaux)
cours_pandas_facile_debutant/      Pandas version débutant / vulgarisée
cours_pandas_dataset_beobank/      Pandas appliqué au dataset Beobank (100 cas, mises en situation, exercices)
cours_sql/                         Cours SQL + mises en situation + exercices (dataset Beobank)
cours_sql_vertica_natif/           Variante SQL Vertica natif
sas_vs_python/                     Comparatif SAS vs Python
participant_cahiers_exercices1/    Cahiers participants (Jour1/2/3)
Support formateur/                 Cahiers corrigés formateur (Jour1/2/3)

```

## Dataset Beobank

5 tables CSV dans `data/` :
- `CTR` — contrats
- `TIE` — tiers (clients)
- `TIE_ADR` — adresses des tiers
- `TIE_X_CTR` — lien tiers/contrats
- `TXN_X_CTR` — transactions par contrat

## Prérequis

- Python 3.x, Jupyter Notebook/Lab
- pandas, numpy

## Utilisation

Ouvrir les notebooks (`.ipynb`) dans l'ordre du déroulé pédagogique. Chaque module cours a son cahier d'exercices participants et son corrigé formateur associé.

## Contacter Joel
[LinkedIn — Joel Parfait Kuate](https://www.linkedin.com/in/joelparfaitkuate/) 

