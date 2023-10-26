[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=11754452&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.


Graph $A$ has $n$ amount of nodes. Graph $B$ has less nodes then $A$ and is isomorphic to each other

By the formal definition of isomorphism, there is a one-to-one bijection relationship between $A$ and $B$, this means that for every node in A, there is also a direct connection to some node in B once as it is one-to-one and onto. 

But this can't possiblely happen as we know graph $B$ has less nodes than A so there is no possible one-to-one and onto relationship between $A$ and $B$. Therefore, if two graphs do not have the same number of nodes, they cannot be isomorphic.
