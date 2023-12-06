[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12764678&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.


To prove that two graphs can not be isomorphic if they do not share the 
the same amount of nodes, we need to first talk about what it means to be bijective.
Bijection means that something is one to one, and onto. Onto means that if you 
have two graphs $A$ and $B$, then every node in $A$ can be mapped to $B$. 
One-to-one is similar but in reverse, so every node in $B$ has to be mapped
to a node in $A$. Because of these definitions, we need to have a 
node that can map to another node for all nodes in the graphs. Since this is the
case and we know one of the graphs will have at least one more node than the other, 
we then know that we can't map all the nodes in one graph to the other without 
a node that wasn't able to be mapped to its own node. Therefore two graphs cant be 
isomorphic if they do not share the same amount of nodes.
