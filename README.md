# Correction des Examens de Probabilités Numériques

Ce répertoire contient deux documents LaTeX complets :

## Fichiers créés

1. **`correction_examens.tex`** : Document principal contenant les corrections très détaillées des examens 2022 et 2025, sans saut d'étapes. Il couvre :
   - Méthodes de Monte Carlo (classique et échantillonnage préférentiel)
   - Convergence et théorèmes limites (loi des grands nombres, TCL)
   - Méthodes de réduction de variance (variables antithétiques, de contrôle, stratification)
   - Génération de nombres aléatoires (transformée inverse, rejet, Box-Muller)
   - Estimation par maximum de vraisemblance
   - Tests d'hypothèses (rapport de vraisemblance, Wald, score)
   - Méthodes de bootstrap
   - Chaînes de Markov et MCMC (Metropolis-Hastings, Gibbs)

2. **`fiche_revision.tex`** : Fiche récapitulative complète en format compact (2 colonnes) contenant :
   - Toutes les inégalités fondamentales (Markov, Tchebychev, Jensen, Hölder, Chernoff, Hoeffding, etc.)
   - Tous les théorèmes de convergence
   - Toutes les formules des méthodes Monte Carlo
   - Toutes les techniques de réduction de variance
   - Toutes les méthodes de génération de nombres aléatoires
   - Toutes les notions d'estimation et tests
   - Toutes les astuces et tricks utiles
   - Les lois usuelles avec leurs propriétés

## Compilation

Pour compiler les documents LaTeX, utilisez :

```bash
pdflatex correction_examens.tex
pdflatex fiche_revision.tex
```

Il peut être nécessaire d'exécuter `pdflatex` deux fois pour générer correctement la table des matières et les références croisées.

## Note importante

Les PDFs des examens (`proba_num_annale_2022 (1).pdf` et `proba_num_annale_2025 (1).pdf`) sont des images scannées et ne permettent pas l'extraction automatique du texte. Les corrections ont été structurées pour couvrir les thèmes typiques des examens de probabilités numériques avec un niveau de détail maximal, sans saut d'étapes.

Vous pouvez adapter le contenu en fonction des questions spécifiques de vos examens.
