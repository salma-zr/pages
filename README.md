# Corrections Détaillées - Examens de Probabilités Numériques

## Description

Ce dépôt contient des corrections extrêmement détaillées pour les examens de Probabilités Numériques de janvier 2013 et janvier 2015 (M2 Probabilités & Finance, UPMC-École Polytechnique).

## Fichier principal

**`corrections_detaillees.tex`** - Document LaTeX complet (133 Ko, 3732 lignes)

## Contenu

### Examen du 10 janvier 2013

#### Problème 1 : Autour du schéma de Milstein
- **Question 1.a-c** : Existence, unicité, moments et schéma d'Euler pour les EDS
- **Question 2.a-b** : Positivité du schéma de Milstein (constant par morceaux et continu)
- **Question 3.a-b** : Transformation exponentielle et conditions de positivité
- **Question 4.a-b** : Convergence des schémas de Milstein et critère de positivité
- **Question 5** : Modèle CIR généralisé $(CIR)_\alpha$ pour $\alpha \in [1/2, 1]$
- **Question 6** : Processus d'Ornstein-Uhlenbeck et lien avec le CIR
  - Démonstration que $Z_t^2$ suit un CIR
  - Schéma de simulation exacte pour le cas $a = \vartheta^2/4$
- **Question 7-8** : Modèle de Heston
  - Conditionnement et réduction de variance
  - Conditions de positivité

#### Problème 2 : Autour du pont de diffusion
- **Question 1** : Loi de l'infimum du pont brownien et simulation
- **Question 2** : Loi conditionnelle du schéma d'Euler et méthode de Monte Carlo pour fonctionnelles de la trajectoire
- **Question 3** : Options barrière basse avec correction par poids

### Examen du 5 janvier 2015

#### Quasi-Monte Carlo I
- **Question 1** : Méthode de Box-Müller en version QMC avec suite de Halton
- **Question 2** : Variation au sens de Hardy-Krause et inégalité de Koksma-Hlawka

#### Quasi-Monte Carlo II : Randomisation
- **Question 1** : Invariance de l'intégrale par translation modulo 1
- **Question 2** : Randomized QMC et calcul de variance
- **Question 3** : Fonctions périodiques isotropes
  - Majoration de la variance par la discrépance
  - Comparaison avec Monte Carlo standard
  - Avantages du RQMC : convergence $O((\log n)^{2d}/n^2M)$

#### Problème : Couvrir une option digitale
- Calcul numérique du "kappa" (sensibilité) d'un call digital
- Majoration de l'erreur par moments et densité
- Approximation de dérivée par différence finie
- Techniques avancées de réduction de variance

### Fiche Récapitulative

Section complète regroupant :

1. **Inégalités fondamentales**
   - Inégalités probabilistes (Markov, Cauchy-Schwarz, Jensen, Doob, BDG)
   - Inégalités analytiques (Young, Grönwall, Koksma-Hlawka)

2. **Notions théoriques essentielles**
   - Calcul stochastique (formule d'Itô, théorèmes d'existence et d'unicité)
   - Schémas numériques (Euler, Milstein, convergence)
   - Condition de Feller pour le CIR
   - Méthodes Monte Carlo et Quasi-Monte Carlo

3. **Astuces et techniques de calcul**
   - Complétion du carré
   - Transformation exponentielle
   - Solution exacte d'Ornstein-Uhlenbeck
   - Lien CIR - OU
   - Symétrie du mouvement brownien
   - Pont brownien et loi conditionnelle
   - Méthodes de réduction de variance

4. **Tableaux récapitulatifs**
   - Ordres de convergence des schémas
   - Conditions de positivité
   - Comparaison des méthodes MC/QMC/RQMC

## Caractéristiques du document

✅ **Corrections extrêmement détaillées** : Chaque étape est expliquée en profondeur

✅ **Aucun saut d'étapes** : Tous les calculs intermédiaires sont présentés

✅ **Rappels théoriques** : Théorèmes, définitions et formules clés

✅ **Astuces de calcul** : Techniques et méthodes utiles mises en évidence

✅ **Justifications rigoureuses** : Chaque affirmation est justifiée

✅ **Remarques pédagogiques** : Interprétations et applications pratiques

✅ **Structure claire** : Organisation par problème, sous-problème et question

## Compilation du document

Pour compiler le document LaTeX en PDF :

```bash
pdflatex corrections_detaillees.tex
pdflatex corrections_detaillees.tex  # Seconde compilation pour les références
```

Note : Le document nécessite les packages LaTeX suivants :
- amsmath, amssymb, amsthm
- mathtools
- geometry
- enumitem
- hyperref
- thmtools
- babel (french)

## Thèmes abordés

### Calcul stochastique
- Équations différentielles stochastiques (EDS)
- Formule d'Itô
- Processus de diffusion
- Mouvement brownien et ponts browniens

### Schémas numériques
- Schéma d'Euler (convergence forte d'ordre 1/2)
- Schéma de Milstein (convergence forte d'ordre 1)
- Conditions de positivité
- Simulation exacte (Ornstein-Uhlenbeck)

### Modèles financiers
- Modèle de Cox-Ingersoll-Ross (CIR)
- Modèle de Heston (volatilité stochastique)
- Options barrière
- Options digitales
- Calcul de sensibilités (Greeks)

### Méthodes de Monte Carlo
- Monte Carlo standard
- Quasi-Monte Carlo (QMC)
- Randomized QMC
- Réduction de variance
- Conditionnement

### Analyse numérique
- Suites à faible discrépance (Halton, Sobol)
- Théorème de Koksma-Hlawka
- Variation au sens de Hardy-Krause
- Différenciation numérique

## Statistiques

- **Nombre de pages** : ~80-100 pages (estimé après compilation)
- **Nombre de lignes** : 3732 lignes
- **Taille du fichier source** : 133 Ko
- **Nombre de questions traitées** : Plus de 30 questions détaillées
- **Nombre d'inégalités listées** : Plus de 15 inégalités fondamentales
- **Nombre de théorèmes explicités** : Plus de 10 théorèmes majeurs

## Utilisation

Ce document est destiné aux étudiants de M2 en probabilités, finance quantitative, ou mathématiques appliquées qui souhaitent :
- Préparer les examens de probabilités numériques
- Comprendre en profondeur les schémas numériques pour les EDS
- Maîtriser les méthodes de Monte Carlo et Quasi-Monte Carlo
- Approfondir les modèles stochastiques utilisés en finance

## Auteur

Corrections réalisées avec une attention particulière portée à :
- La rigueur mathématique
- La clarté pédagogique
- L'exhaustivité des explications
- La présentation structurée

---

*Document créé le 3 janvier 2026*
