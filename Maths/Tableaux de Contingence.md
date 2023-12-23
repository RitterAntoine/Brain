# Introduction aux Tableaux de Contingence et à l'Indépendance Statistique

Un tableau de contingence est une manière organisée de représenter la distribution conjointe de deux variables. Il est souvent utilisé en statistique pour étudier les relations entre des variables catégorielles. L'indépendance statistique entre deux variables signifie que la probabilité d'occurrence d'un événement particulier pour l'une des variables n'est pas affectée par la valeur de l'autre variable.
# Exemple d'utilisation
Le tableau fourni est le suivant :

|X/Y|y1|y2|Totaux|
|---|---|---|---|
|x1|||16|
|x2|||24|
|Totaux|30|10|40|

## Calculs des Effectifs Conjoint

Pour déterminer les effectifs conjoints $n_{ij}$ dans le cas où les variables X et Y sont indépendantes, nous utilisons la formule suivante :

$$ n_{ij} = \frac {n_{i*} \times n_{*j}}{n} $$

où :

- $n_{ij}$ est l'effectif conjoint pour la cellule (i, j),
- $n_{i*}$ est le total de la ligne i,
- $n_{*j}$ est le total de la colonne j,
- $n$ est le total général.

**Calculs des Effectifs Conjoint pour l'Indépendance :**

1. $n_{11}=\frac{16\times30}{40}=12$
2. $n_{12}=\frac{16\times10}{40}=4$
3. $n_{21}=\frac{24\times30}{40}=18$
4. $n_{22}=\frac{24\times10}{40}=6$

En simplifiant les calculs, nous obtenons les effectifs conjoints dans l'ordre demandé ci-dessus :

$n_{11}=12$, $n_{12}=4$, $n_{21}=18$ et $n_{22}=6$

Ces valeurs représentent la distribution conjointe des variables X et Y sous l'hypothèse d'indépendance statistique. L'indépendance statistique entre X et Y signifie que la fréquence d'occurrence de chaque combinaison de valeurs de X et Y est le produit des fréquences marginales correspondantes, ce qui confirme le modèle d'indépendance entre les deux variables.