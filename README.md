[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/QM7QGF1q)
# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Proof:

Let $G_{1}, G_{2}$ be any graphs with otherwise isomorphic, connected bodies and containing vertices with unknown isomorphism $u_{1}, v_{1}$ and $u_{2}, v_{2}$ respectively.

Suppose that vertice $u_{1}$ is a vertice contained within the main isomorphic, connected body of $G_{1}$ and also connected with $v_{1}$ where $u_{1}$ is it's only connection, likewise with $u_{2}, v_{2}$, and $G_{2}$. Also suppose that $u_{1}$ can be directly mapped to $u_{2}$ in isomorphism.

Let $E_{1}$ represent the edge $u_{1}, v_{1}$, and $E_{2}$ represent the edge $u_{2}, v_{2}$.

There exists a one-to-one and onto functon $f: u_{1} \rightarrow v_{1}$ such that $(u_{1}, v_{1}) \in E_{1}$ and $(f(u_{1}), f(v_{1})) = (u_{2}, v_{2}) \in E_{2}$

By definition of isomorphism, $G_{1}$ is isomorphic to $G_{2}$.

Thus, two graphs do not have to be completely connected in order to be isomorphic.
