# About
This is the repository containing all codes, original and transformed datasets, and result of my FMU Undergraduate Mathematics Capstone Research Project. Please check out the [presentation](Presentation.pdf) for more information.

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

# Methodology

### Python Packages and Methods

For this research project, I used the following Python packages:

- Pandas: for data manipulation and analysis.
- NetworkX: for graph theory and graph operations.
- NumPy: for data manipulation and matrix operations.
- SciPy: for statistical computations.
- Matplotlib: for graph visualization.

### Code Outline

The code for my research project will accomplish the following tasks:

1. Load and preprocess the dataset of connected graphs up to order 9 using Pandas.
2. Sort the dataset by the chromatic vector and group it by vertices and edges using Pandas.
3. Utilize NetworkX in conjunction with Pandas to calculate and add the following graph properties to the dataset:
   - Number of spanning tree
   - Number of biconnected components
   - Number of 3-cycles
   - Number of 4-cycles
   - Number of 5-cycles
   - Number of 6-cycles
   - Number of spanning trees
   - Degree sequence
   - Degree variance
   - Degree deviation
4. Utilize Pandas to analyze the dataset and identify the graphs that yield the largest chromatic vectors in their respective groups.
5. Statistical analysis using Pandas and SciPy to calculate the percentile rank of maximum chromatic vector graph properties versus other non-max graphs within their group.
6. Visualize graphs and results using NetworkX in conjunction with Matplotlib for data visualization.
