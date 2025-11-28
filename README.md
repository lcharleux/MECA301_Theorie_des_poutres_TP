# MECA301 Sujets de TP

## Utilisation

Ces sujets de TP utilisent Jupyter Lab.
Vous pouvez les utiliser directement sur les machines de Polytech.
Vous pouvez aussi les uitliser sur vos machines personnelles. 
Un tutoriel d'installation avec Miniforge est fourni sur notre site [Positron](https://symmehub.github.io/positron/setup/setup.html).

## Contenu

## Structure des fichiers

Dans ce dépôt, tout le matériel est rassemblé dans `TPs/`.

- `TPs/TMEC301_Tutoriel.ipynb` — tutoriel d’amorçage (Python/NumPy/SymPy).
- `TPs/TMEC301_TP1_ex1.ipynb` — TP1, exercice 1.
- `TPs/TMEC301_TP1_ex2.ipynb` — TP1, exercice 2.
- `TPs/TMEC301_TP2.ipynb` — TP2 (énoncé et activités guidées).
- `TPs/MECA301.py` — utilitaires Python communs (ex. torseurs, aides de calcul).
- `TPs/TP1ex1.svg` — schéma/figure utilisée dans le TP1, ex. 1.
- `TPs/TP1_ex2.svg` — schéma/figure utilisée dans le TP1, ex. 2.
- `TPs/TP2_ex1.svg` — schéma/figure utilisée dans le TP2.

Le dossier `TPs/__pycache__/` contient des caches Python et peut être ignoré.

## Organisation par TP

### TP1
- Notebooks: `TMEC301_TP1_ex1.ipynb`, puis `TMEC301_TP1_ex2.ipynb`.
- Dépendances: `MECA301.py` (importé dans les notebooks si nécessaire).
- Ressources: figures `TP1_ex1.svg` et `TP1_ex2.svg` affichées dans le notebook.

### TP2
- Notebook: `TMEC301_TP2.ipynb`.
- Dépendances: `MECA301.py` (fonctions/outils communs).
- Ressources: figures `TP2_ex1.svg` affichées dans le notebook.

## Lancer les TPs

Depuis la racine du dépôt, lancez Jupyter Lab et ouvrez les notebooks dans `TPs/`:

```bash
jupyter lab
```
