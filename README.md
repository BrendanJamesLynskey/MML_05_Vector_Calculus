# Vector Calculus

Deck 05 of the [Mathematics for Machine Learning &mdash; Companion Series](https://github.com/BrendanJamesLynskey/MML_Hub).

**Live presentation:** https://brendanjameslynskey.github.io/MML_05_Vector_Calculus/

Partial derivatives, the gradient, the Jacobian, gradients of matrix
expressions, the chain rule, backpropagation as the chain rule on a DAG,
automatic differentiation, multivariate Taylor series. Includes an
interactive gradient-descent visualiser on a 2D loss surface.

## What's inside

- Univariate differentiation &mdash; the rules and the linear-approximation view
- Partial derivatives and the gradient as a row vector
- The Jacobian as a matrix of partial derivatives
- Gradients of vector- and matrix-valued functions (with shape conventions)
- The chain rule as a matrix product
- Useful identities ($\nabla \mathbf{x}^\top A \mathbf{x}$, $\nabla\log\det A$, &hellip;)
- Backpropagation = chain rule on a computation DAG
- Forward-mode vs reverse-mode automatic differentiation
- Higher-order derivatives, the Hessian, and the multivariate Taylor series
- Interactive 2D gradient-descent demo with adjustable step size

Companion to chapter 5 of:

> Deisenroth, M. P., Faisal, A. A. &amp; Ong, C. S. (2020). *Mathematics for Machine Learning.* Cambridge University Press. Free PDF: [mml-book.github.io](https://mml-book.github.io/).

Single-page HTML, KaTeX-rendered maths, no build step. Open `index.html` directly.
