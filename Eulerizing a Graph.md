Graph theory practice

# Eulerizing a Graph

Make every vertex have an even degree by adding copies of existing edges, using as few added edges as you can. **Click an edge** to add a copy. **Click a blue copy** to remove it.

Odd vertices0

Edges added0

- Odd degree, needs a fix
- Even degree
- Added copy of an edge

What does Eulerizing mean?

A connected graph has an Euler circuit, a trip that uses every edge once and ends where it began, only when every vertex has even degree. To Eulerize a graph, duplicate some existing edges until no odd vertices are left. A graph always has an even number of odd vertices, so they can be paired up. The fewest added edges come from pairing the odd vertices so the paths between the pairs are as short as possible in total, then copying each edge along those paths.