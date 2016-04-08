# dismathportfolio-vittorionavarro

##Week 8
**Algorithms** 
  - Is a finite set of precise instructions
	- **Properties of Algorithm:**
	  * INPUT
	  * OUTPUT
	  * DEFINITENESS
	  * CORRECTNESS
	  * FINITENESS
	  * GENERALITY
	  * EFFECTIVENESS
	  
**Pseudocode** Is a high-level desciption of an algorithm that uses the structural conventions of programming knowledge
- **Searching Algorithms**
  - Linear Search <br>
  ![ScreenShot](linear.jpg) 
  - Binary Search <br>
  ![ScreenShot](binary.jpg) 

##Week 9
- **Sorting Algorithms**
  - Bubble Sort <br>
  ![ScreenShot](bubblesort.jpg) 
  - Insertion Sort <br>
  ![ScreenShot](insertsort.jpg)
  - Greedy Algorithm <br>
  ![Screenshot](greedy.jpg)

##Week 10
**Growth of Functions**
  * Using Big-O, Big-Ω,and Big-ϴ
    - Big-O, upper bound
    - Big-Ω, lower bound
    - Big-ϴ, both upper and lower bound <br>
    ![Screenshot](bigo.jpg)
	- *Algorithm Time Complexity
	- *Division and Modulo Operator
  		- Let a be an integer and d positive integer. Then there is a unique Q and r with 0 ≤ r < d such that a = dQ + r.
  		- Q = a div d
		- r = a mod d

##Week 12
**Graph Theory**
  - **Graphs** - discrete structures consisting of vertices and edges that connect these vertices.  
  	- **Degree** - is the number of edges incident with it. A loop in a vertex contributes twice.
		- Isolated - is a vertex of degree zero.
		- Pendant - is a vertex of degree one.
  - **Handshake Theory** : 2e = ∑deg(v)
  - *Subgraphs* <br>
  ![Screenshot] (subgraph.jpg)
  - *Unions* <br>
  ![Screenshot] (union.jpg)

  - **Path** - a sequence of edges travelling from vertex to vertex along the edges.
  - **Eulerian**
    - Euler Circuit - passes through every edge and goes back to the starting point. Has even number of degrees.
    - Euler Path - passes through every edge but does not go back to the starting point. Has exactly 2 odd degrees.
  - **Hamiltonian**
    - Hamilton Circuit - passes through every nodes and goes back to the starting point.
    - Hamilton Path - passes through every nodes but does not go back to the starting point.
  - **Matrices of Graphs** - connected is 1; not connected is 0 <br>
  ![Screenshot](matrix.jpg)

  - **Isomorphism of Graphs** - The graphs are isomorphic if there exists a one-to-one and onto function.
  - **Planar Graphs** - graphs that can be drawn in the plane without the edges crossing each other.
  - **Euler's Formula** : r = e - v + 2
	- r - regions
	- e - edges 
	- v - vertices
  - **Kuratowski's Theorem** - A graph is nonplanar if and only if it contains a subgraph homeomorphic to K3,3 or K5.
