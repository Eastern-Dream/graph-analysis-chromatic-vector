# analyze-chromatic-vector
FMU Undergraduate Mathematics Capstone Research Project

# Background
In graph theory, the chromatic polynomial of a graph is a polynomial that counts the
number of proper vertex colorings of the graph using a given number of colors. Formally,
let G be a graph with n vertices, and let k be a positive integer. The chromatic polynomial
P(G, k) is defined as the number of proper k-colorings of G, i.e., the number of ways to
color the vertices of G with k colors such that no adjacent vertices have the same color.
The chromatic polynomial is a fundamental concept in graph theory and is closely related
to the chromatic number, which is the smallest number of colors needed to properly color
a graph. The chromatic polynomial provides a way to count the number of possible
colorings for a given number of colors, which can be used to study various properties of
graphs, including planarity and graph coloring algorithms.

The chromatic vector is the vector of absolute value of coefficients of the chromatic
polynomial. A chromatic vector considered greater than another is when every element of
one vector is larger than every element of another vector (i.e., comparing element-wise).
There exists published theorem that tells us what would make a graph yields the smallest
chromatic vector but there has not been any publication that hints at what would make a
graph yields the largest chromatic vector. Thus, we would like to ask and potentially
answers the question “Which graphs have biggest chromatic polynomials for a given
number of vertices and edges?”.
