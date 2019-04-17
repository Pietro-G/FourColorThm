# FourColorThm
Complementary work for A formal proof of the Four Color Theorem

# Breakdown of the Presentation

# Background History
This problem was unsolved for about 127 years and then it was finally completed in the 70's with a method that received some controversy. In 1852 Francis Guthrie was colloring in the countries of England/ Britain and suspected that he could color it with four colors so that neighboring countries were colored differently. Francis Guthrie showed his brother who in turn showed Augustus De Morgan the initial 4 color theorem on 10/23/1852. De Morgan was excited while Hamilton was not, and interest died down in the Four Color Theorem. Till 1878, when Alfred Bray Kempe picked up the four colored theorem. He published his work in 1879 in the second edition of the American Journal of Mathematics. In his approach he used the concept of Kempe Chains, which is a connected chain of points on the graph (See Page 263 in your book).  

  Define Problem 
  ---
  The four color theorem states that any seperation of a plane into contigous regions, also known as a "Map" can be colored using at most four colors where the regions in our graph G would only be considered adjacent if two regions share border (not just a point).
  
  Defining it in the scope of graph thoery, given any map, where the states/regions represent vertices, there exists a mapping to a planar graph where no two adjacent vertices receive the same color. Such plane graph can be acheived with at most 4 colors and is therefore 4 colorable. 
  
  The mapping can be easily done by replacing every region by a vertex and connecting two vertices by an edge exactly when the two regions share a border. 
  
# Insert 4 Map Questions Here
Is the world map 4 colorable? ![world map](http://www.bestcoloringpagesforkids.com/wp-content/uploads/2014/12/World-Map-Coloring-Pages.gif)
Is the USA map 4 colorable? ![USA MAP](https://www.prepaidreviews.com/blog/wp-content/uploads/2015/09/Blank_US_Map.svg_.png)
Is this graph 4-colorable? ![planar](https://upload.wikimedia.org/wikipedia/commons/thumb/1/18/Poussin_graph_planar.svg/1200px-Poussin_graph_planar.svg.png) 

# Notation
Kempe Chain: ![Kempe Chain Idea](https://image.slidesharecdn.com/fa2c963a-1619-4736-944b-9d3f72fd2b36-150313081557-conversion-gate01/95/sfc-21-638.jpg?cb=1426234785)
Lemma 1: For any planar graph Gn with n ( n ≥ 6 ) vertices, there are vertices n v , n−1 v , …, 6 v such that d(vi) ≤ 5 and i i i G = G − v −1 are also planar graphs for i from n down to 6 . 

# Theorem (Four Color Thm): Every planar graph is four colorable. 
Proof: Let the planar graph with n vertices, n is at least 1, and denoted by Gn . There are 3 cases to discuss.
	Case 1:  When 1 <= n <= 4, the result holds (it’s obvious, G1 – G4)
	Case 2:  When n = 5, the maximal planar graph with 5 vertices is the full graph deleting an edge, i.e., the planar graph with 5 vertices and 9 edges, 
	Case 3:  If Lemma 1, occurs then It will be shown that c(Gi) = c(Gi−1 + vi) = 4 for i
from 6 up to n in the following.
 For i from 6 up to n , since c(G5 ) = 4 by Case.2,
let c(Gi−1) = 4, and 
C(v) = {c(u)_i | c(u) is the color of vertex u
in Gi−1 , and u is adjacent to i v in Gi }
Note that C(vi) ≤ 4 and C(vi) ≤ d(vi) ≤ 5 . There
are 3 cases (Case.3.1 - Case.3.3) to discuss.
