# Introduction

Les expressions régulières (RegEx) sont des motifs de recherche utilisés pour identifier des modèles dans des chaînes de caractères. Voici un guide rapide pour vous familiariser avec les commandes et les opérations les plus courantes.

# Recherche et Correspondance

- `^`: Le chapeau est utilisé pour indiquer le début d'une chaîne. Exemple: `^abc` correspond à une chaîne commençant par "abc".

- `$`: Le dollar indique la fin d'une chaîne. Exemple: `xyz$` correspond à une chaîne se terminant par "xyz".

- `.`: Le point correspond à n'importe quel caractère unique. Exemple: `a.b` correspond à "aab" ou "axb".

# Quantificateurs

- `*`: Correspond à zéro ou plusieurs occurrences du caractère précédent. Exemple: `a*` correspond à "", "a", "aa", etc.

- `+`: Correspond à une ou plusieurs occurrences du caractère précédent. Exemple: `1+` correspond à "1", "11", etc.

- `?`: Correspond à zéro ou une occurrence du caractère précédent. Exemple: `ab?c` correspond à "ac" ou "abc".

# Classes de Caractères

- `[...]`: Définit une classe de caractères. Exemple: `[aeiou]` correspond à n'importe quelle voyelle.

- `[^...]`: Correspond à tout caractère qui n'est pas dans la classe spécifiée. Exemple: `[^0-9]` correspond à tout sauf les chiffres.

# Ancrages

- `\b`: Correspond à une frontière de mot. Exemple: `\bword\b` correspond à "word" en tant que mot complet.