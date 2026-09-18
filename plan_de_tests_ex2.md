# Plan de tests - Ex2

| Fonction         | Cas à tester              | Entrée            | Résultat attendu        | Bon? |
|------------------|---------------------------|-------------------|-------------------------|------|
| est_pair         | nombre pair               | 4                 | True                    |      |
| est_pair         | nombre impair             | 3                 | False                   |      |
| est_pair         | zéro                      | 0                 | True                    |      |
| note_lettre      | note = 95                 | 95                | "A"                     |      |
| note_lettre      | note = 80 (limite)        | 80                | "B"                     |      |
| note_lettre      | note = 89                 | 89                | "B"                     |      |
| filtrer_positifs | mélange +/-/0             | [-3, 5, -1, 8, 0] | [5, 8]                  |      |
| filtrer_positifs | liste originale inchangée | [-3, 5, -1, 8, 0] | reste [-3, 5, -1, 8, 0] |      |
| filtrer_positifs | type du résultat          | [-3, 5]           | list                    |      |

Consigne : compléter les TODO dans `test_ex2_pratique.py`, puis corriger les
bogues dans `ex2_pratique.py` jusqu'à ce que `pytest` passe au vert.
