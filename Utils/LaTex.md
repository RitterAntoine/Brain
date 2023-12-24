# LaTeX equations

Inline equation: `$equation$`

Display equation: `$$equation$$`

# Operators

- $x + y$
- $x - y$
- $x \times y$
- $x \div y$
- $\dfrac{x}{y}$
- $\sqrt{x}$

# Symbols

- $\pi \approx 3.14159$
- $\pm \, 0.2$
- $\dfrac{0}{1} \neq \infty$
- $0 < x < 1$
- $0 \leq x \leq 1$
- $x \geq 10$
- $\forall \, x \in (1,2)$
- $\exists \, x \notin [0,1]$
- $A \subset B$
- $A \subseteq B$
- $A \cup B$
- $A \cap B$
- $X \implies Y$
- $X \impliedby Y$
- $a \to b$
- $a \longrightarrow b$
- $a \Rightarrow b$
- $a \Longrightarrow b$
- $a \propto b$

- $\bar a$
- $\tilde a$
- $\breve a$
- $\hat a$
- $a^ \prime$
- $a^ \dagger$
- $a^ \ast$
- $a^ \star$
- $\mathcal A$
- $\mathrm a$
- $\cdots$
- $\vdots$
- $\#$
- $\$$
- $\%$
- $\&$
- $\{ \}$
- $\_$

# Space

- Horizontal space: `\quad`
- Large horizontal space: `\qquad`
- Small space: `\,`
- Medium space: `\:`
- Large space: `\;`
- Negative space: `\!`

# Greek alphabets

| Small Letter | Capital Letter | Alternative |
|--------------|----------------|-------------|
| $\alpha$     | $A$            |             |
| $\beta$      | $B$            |             |
| $\gamma$     | $\Gamma$       |             |
| $\delta$     | $\Delta$       |             |
| $\epsilon$   | $E$            | $\varepsilon$ |
| $\zeta$      | $Z$            |             |
| $\eta$       | $H$            |             |
| $\theta$     | $\Theta$       | $\vartheta$ |
| $\iota$      | $I$            |             |
| $\kappa$     | $K$            | $\varkappa$ |
| $\lambda$    | $\Lambda$      |             |
| $\mu$        | $M$            |             |
| $\nu$        | $N$            |             |
| $\xi$        | $\Xi$          |             |
| $\omicron$   | $O$            |             |
| $\pi$        | $\Pi$          | $\varpi$    |
| $\rho$       | $P$            | $\varrho$   |
| $\sigma$     | $\Sigma$       | $\varsigma$ |
| $\tau$       | $T$            |             |
| $\upsilon$   | $\Upsilon$     |             |
| $\phi$       | $\Phi$         | $\varphi$   |
| $\chi$       | $X$            |             |
| $\psi$       | $\Psi$         |             |
| $\omega$     | $\Omega$       |             |

# Equations

$$\mathbb{N} = \{ a \in \mathbb{Z} : a > 0 \}$$

$$\forall \; x \in X \quad \exists \; y \leq \epsilon$$

$$\color{blue}{X \sim Normal \; (\mu,\sigma^2)}$$

$$P \left( A=2 \, \middle| \, \dfrac{A^2}{B}>4 \right)$$

$$f(x) = x^2 - x^\frac{1}{\pi}$$

$$f(X,n) = X_n + X_{n-1}$$

$$f(x) = \sqrt[3]{2x} + \sqrt{x-2}$$

$$\mathrm{e} = \sum_{n=0}^{\infty} \dfrac{1}{n!}$$

$$\int_{a}^{b} x^2 \, dx$$

$$\lim_{{x \to \infty}} f(x)$$

$$\dfrac{\partial f}{\partial x} = \lim_{{h \to 0}} \dfrac{f(x+h)-f(x)}{h}$$

$$\sum_{k=1}^{n} k^2 = \dfrac{n(n+1)(2n+1)}{6}$$
## Functions

### Trigonometric Functions

- $\sin x$
- $\cos x$
- $\tan x$
- $\cot x$
- $\sec x$
- $\csc x$

### Hyperbolic Functions

- $\sinh x$
- $\cosh x$
- $\tanh x$
- $\coth x$
- $\sech x$
- $\csch x$

### Logarithmic Functions

- $\log x$
- $\ln x$

### Exponential Functions

- $e^x$
- $2^x$
- $10^x$

### Piecewise Functions

$$
f(x) =
\begin{cases}
x^2 & \text{if } x \geq 0 \\
\sqrt{x} & \text{if } x < 0
\end{cases}
$$

### Absolute Value

- $|x|$

### Floor and Ceiling

- $\lfloor x \rfloor$
- $\lceil x \rceil$

### Min and Max

- $\min(a, b)$
- $\max(a, b)$

## Matrices

### Basic Matrix

$$
A =
\begin{bmatrix}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{bmatrix}
$$

### Matrix Operations

#### Addition

$$
C = A + B =
\begin{bmatrix}
a_{11}+b_{11} & a_{12}+b_{12} \\
a_{21}+b_{21} & a_{22}+b_{22}
\end{bmatrix}
$$

#### Subtraction

$$
C = A - B =
\begin{bmatrix}
a_{11}-b_{11} & a_{12}-b_{12} \\
a_{21}-b_{21} & a_{22}-b_{22}
\end{bmatrix}
$$

#### Scalar Multiplication

$$
C = kA =
\begin{bmatrix}
ka_{11} & ka_{12} \\
ka_{21} & ka_{22}
\end{bmatrix}
$$

#### Matrix Multiplication

$$
C = AB =
\begin{bmatrix}
c_{11} & c_{12} \\
c_{21} & c_{22}
\end{bmatrix}
$$

where

$$
c_{11} = a_{11}b_{11} + a_{12}b_{21}, \quad
c_{12} = a_{11}b_{12} + a_{12}b_{22}, \quad
c_{21} = a_{21}b_{11} + a_{22}b_{21}, \quad
c_{22} = a_{21}b_{12} + a_{22}b_{22}
$$

### Transpose

$$
A^T =
\begin{bmatrix}
a_{11} & a_{21} \\
a_{12} & a_{22}
\end{bmatrix}
$$

### Determinant

$$
\text{det}(A) = |A| = a_{11}a_{22} - a_{12}a_{21}
$$

### Inverse

$$
A^{-1} =
\frac{1}{|A|}
\begin{bmatrix}
a_{22} & -a_{12} \\
-a_{21} & a_{11}
\end{bmatrix}
$$

The LaTeX and Markdown syntax provided above is based on a comprehensive guide available at [https://ashki23.github.io/markdown-latex.html](https://ashki23.github.io/markdown-latex.html). This resource offers detailed explanations and examples for incorporating LaTeX mathematical expressions and Markdown formatting into documents. Readers are encouraged to visit the source for additional insights and a deeper understanding of the presented markup techniques.