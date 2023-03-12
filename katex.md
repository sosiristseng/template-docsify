# KaTeX example

Powered by [docsify-katex](https://upupming.site/docsify-katex/docs/)

## Repeating fractions

$$\frac{1}{\Bigl(\sqrt{\phi \sqrt{5}}-\phi\Bigr) e^{\frac25 \pi}} \equiv 1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {1+\frac{e^{-6\pi}} {1+\frac{e^{-8\pi}} {1+\cdots} } } }$$

## Summation notation

$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$

## Probability density of normal distribution

$$f(x) = \frac{1}{\sqrt{2\pi}\sigma}e^{-\frac{(x-\mu)^2}{2\sigma^2}}$$

## The ratio of two consecutive numbers in Fibonacci Sequence

$$\lim_{n\to \infty}\frac{A_{n-1}}{A_n}=\frac{\sqrt{5}-1}{2}.$$

## Factorisation

$$
\begin{aligned}(x−1)(x−3)&=x^2−4x+3 \cr
&=x^2−4x+4−1 \cr
&=(x−2)^2−1
\end{aligned}
$$

## Dirichlet function

$$
D(x)=
\begin{cases}
1,& x \in Q \cr
0,& x \notin Q
\end{cases}
$$

## Gauss's law

$$
\iiint_{\Omega}\left(\frac{\partial P}{\partial x}+\frac{\partial Q}{\partial y}+\frac{\partial R}{\partial z}\right) d v=\iint_{\Sigma} P d y d z+Q d z d x+R d x d y
$$

## Vandermonde matrix

$$
D_{n-1}=\left|\begin{array}{cccc}
1 & 1 & \dots & 1 \cr
x_{2} & x_{3} & \dots & x_{n} \cr
\vdots & \vdots & & \vdots \cr
x_{2}^{n-2} & x_{3}^{n-2} & \dots & x_{n}^{n-2}
\end{array}\right|=\prod_{2 \leq j<i \leq n}\left(x_{i}-x_{j}\right)
$$

## Lorenz Equations

$$
\begin{aligned}
\dot{x} &= \sigma(y-x) \cr
\dot{y} &= \rho x - y - xz \cr
\dot{z} &= -\beta z + xy
\end{aligned}
$$

## Maxwell's Equations

$$
\begin{aligned}
\nabla \times \vec{\mathbf{B}} -, \frac1c, \frac{\partial\vec{\mathbf{E}}}{\partial t} &= \frac{4\pi}{c}\vec{\mathbf{j}} \cr
\nabla \cdot \vec{\mathbf{E}} &= 4 \pi \rho \cr
\nabla \times \vec{\mathbf{E}}, +, \frac1c, \frac{\partial\vec{\mathbf{B}}}{\partial t} &= \vec{\mathbf{0}} \cr
\nabla \cdot \vec{\mathbf{B}} &= 0
\end{aligned}
$$

## Chemical expression

Powered by [mhchem](https://mhchem.github.io/MathJax-mhchem/). However, nested `$`...`$` blocks are not supported by docsify.

$\ce{CO2 + C -> 2 CO}$

$\ce{Hg^2+ ->[I-] HgI2 ->[I-] [Hg^{II}I4]^2-}$

$C_p[\ce{H2O(l)}] = \pu{75.3 J // mol K}$

$\ce{A ->[{text above}][{text below}] B}$

$\ce{x Na(NH4)HPO4 ->[\Delta] (NaPO3)_x + x NH3 ^ + x H2O}$
