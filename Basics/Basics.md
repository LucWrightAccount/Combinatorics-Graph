# Basics

**Graph**  
Definition: A graph (or network) is a pair of sets $G = (V(G), E(G))$ where,
- $V(G)$ is a set of vertices (sometiems called nodes)
- $E(G)$ is a set of edges where each edge is associated with a multiset of vertices with 2 elements (i.e {x,x}, {x,y} where $x,y \in V(G)$ )

**Simple**  
Definitiion: A graph is simpl when there are no loops and no multiple links between the same pair of vertices.

When a graph is simpl its edges can be ambigously associated with 2-element subsets of $V(G)$

![Simple Graph](image-6.png)

**Isomporphic**

Definition: two graphs are isomporphic if their vertices can be labeled with the same set of labels and they result in the same edge sets.

**Complete Graph**

Definition: A complete graph $K_n$ with vertices is the simple graph with all possible edges. There are $n \choose 2$
 edges in $K_n$

 ![Complete Graphs](image-5.png)

 **Compliments**

 Definition: Given a simple graph G on n vertices its compliemnt is the grpah on the same vertex set, but whose edge set is $E(K_n) - E(G)$. This graph is denoted by $\overline G$

 ![Compliments](image-4.png)

 **Paths** 
 Definition: $P_n$ is the graph with vertices $1,2,3,..., n,n+1$ and edges $\{ \{1,2\}, \{2,3\}, \ldots, \{n,n+1\} \}$

Note: $P_n$ has n edges and this number is also known as the length of the path.

![Parhs](image-2.png)
**Cycles**

Definition: $C_n$ is the graph with verticies $\{1,2,3,4,5, ...,n\}$ and $$\{ \{1,2\}, \{2,3\}, \ldots, \{n-1,n\},\{n,1\}\}$$

![Cycles](image-3.png)
**Wheels**

Defintion: $W_n$ is called the n-pkoed wheel

Note $W_n$ has n+1 vertices. The central vertex is called the hub and the rest are rim vertices

![Wheels](image-1.png)

**Complete Bipartite Graph**

$K_m,_n$ is the graph with vertex set $\{a_1, a_2, \ldots, a_m\} \cup \{b_1, b_2, \ldots, b_n\}$ with all possible edges $\{a_i,b_i\}$

![$K_m,_n$](image.png)

Definition: A graph B is bipartite when $V(B) = X \cup Y$ with $X \cap Y \neq 0 $ , and each edge e has one endpoint in X and one end point in Y.

The Set $X$ and $Y$ are known as the partite sets of $B$

![alt text](image-7.png)

**k-regualr**
Definition A graph G is $k-regular$ when evyer vertex has degree $k$

