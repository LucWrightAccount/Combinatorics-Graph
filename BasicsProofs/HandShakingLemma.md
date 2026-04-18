## HandShaking Lemma 
If G is a graph with vertices $v_1,v_2,v_3,...v_n$, then $d(v_1)+d(v_2)+d(v_3), ... +d(v_n) = 2|E| $

### Proof
Every edge has exactly two ends. Therefore every edge is counted exactly two times in $v_1,v_2,v_3,...v_n$, then $d(v_1)+d(v_2)+d(v_3), ... +d(v_n) = 2|E| $. Therefore the sum is 2|E|.

## Handshaking in Bipartite Graphs
**Let** B be a bipartite graph with partite sets
$\{x_1, x_2,\ldots, x_n \}$, and 
$\{y_1, y_2,\ldots, y_n \}$

**Then**,
- $ d(x_1) + d(x_2)+ \ldots+ d(x_n)  = |E(B)|$
- $ d(y_1) + d(y_2)+ \ldots+ d(y_n)  = |E(B)|$

### Proof

\begin{proof}
Since every edge has exactly one endpoint in $\{x_1, x,_2, x_3, \ldots, x_n\}$, each edge is counted exactly one tim in the sum $ d(x_1) + d(x_2)+ \ldots+ d(x_n)  = |E(B)|$.

**Therefore** the sum is |E(B)| 

$Q.E.D$