La loi de Poisson est une distribution de probabilité discrète qui modélise le nombre d'événements se produisant dans un intervalle de temps donné, lorsque ces événements sont rares et indépendants. Elle est souvent utilisée dans le contexte sportif pour modéliser le nombre de buts marqués lors d'un match de football.

## **Définition de la loi de Poisson**

La loi de Poisson est définie par la fonction de masse de probabilité suivante :

$$ P(X=k) = \frac {e^{-\lambda} \times \lambda ^k} {k!} $$

où :

- $P(X=k)$ est la probabilité que la variable aléatoire $X$ prenne la valeur $k$
- $e$ est la base du logarithme naturel (environ 2.71828)
- $\lambda$ est l’espérance de la variable aléatoire $X$
- $k$ est le nombre d’événements

## Exemple d’application

Supposons que $X$ représente le nombre de buts marqués par l'OM dans un match de football, et que $\lambda$ soit l'espérance de $X$. Si l'OM a marqué en moyenne 2 buts par match, alors $\lambda=2$.

### **Calcul de la probabilité**

Pour calculer la probabilité que l'OM marque exactement 1 but dans un match, nous utilisons la formule de la loi de Poisson avec $k=1$ et $\lambda=2$:

$$ P(X=1) = \frac {e^{-2} \times 2 ^1} {1!} $$

En utilisant l'indication fournie que $e^{-2}$ est environ égal à 0.135, nous pouvons calculer la probabilité :

$$ P(X=1) \sim 0.135 \times 2 $$

$$ P(X=1) \sim 0.27 $$

Ainsi, la probabilité que l'OM marque exactement 11 but dans un match est d'environ 27% (arrondi à l'unité).