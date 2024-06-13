# Les Matrices

Une matrice est un tableau rectangulaire de nombres, organisé en lignes et en colonnes.

## Notation et Types

- **Notation** : \( A = \begin{pmatrix} a_{11} & a_{12} \\ a_{21} & a_{22} \end{pmatrix} \)
- **Matrices carrées** : Nombre de lignes = Nombre de colonnes.
- **Matrices nulles** : Tous les éléments sont zéro.
- **Matrices identité** : Matrice carrée avec des 1 sur la diagonale principale et des 0 ailleurs.

## Opérations sur les Matrices

1. **Addition**
   - \( A + B = \begin{pmatrix} a_{11} & a_{12} \\ a_{21} & a_{22} \end{pmatrix} + \begin{pmatrix} b_{11} & b_{12} \\ b_{21} & b_{22} \end{pmatrix} = \begin{pmatrix} a_{11} + b_{11} & a_{12} + b_{12} \\ a_{21} + b_{21} & a_{22} + b_{22} \end{pmatrix} \)

2. **Multiplication**
   - \( AB = \begin{pmatrix} a_{11} & a_{12} \\ a_{21} & a_{22} \end{pmatrix} \begin{pmatrix} b_{11} & b_{12} \\ b_{21} & b_{22} \end{pmatrix} \)

3. **Transposition**
   - \( A^T = \begin{pmatrix} a_{11} & a_{21} \\ a_{12} & a_{22} \end{pmatrix} \)

## Déterminant et Inverse

- **Déterminant** : \( \text{det}(A) = a_{11}a_{22} - a_{12}a_{21} \)
- **Inverse** : \( A^{-1} = \frac{1}{\text{det}(A)} \begin{pmatrix} a_{22} & -a_{12} \\ -a_{21} & a_{11} \end{pmatrix} \) (si le déterminant n'est pas nul).

[Retour à la page principale des mathématiques](maths.md)
