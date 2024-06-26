---
title: Graph Algorithms Visualization Package
date: 2021-06-01
tags: [Python,Graph,Algorithms]
---

<hr>
After learning Graph Algorithms in CMPUT 204 I was excited to implement them and thus I created a Python Package which aims to create visual outputs for popular Graph Algorithms. The package takes an adjacency matrix as an input from the user then prints the graph where the nodes coloured in Red represent the edges traversed by the Algorithm.     
        
        
So far the package includes Breadth First Search (BFS), Depth First Search (DFS), Topological Sort, Prim's and Kruskal's algorithm for MST. I will continue implementing and adding more algorithms like A* Search etc.  

    
    
It is not just limited to getting a visual output, but the algorithms will be optimised by using heuristics for non-polynomial time algorithms.   
This project aims to create a better understanding of the working of graph algorithms, improve the computation time and optimising the algorithms.  
It could be used by analysts as well as students and teachers, as a teaching aid.

The full code can be found on my [GitHub repository](https://github.com/Akarsh654/Graph-Algorithms-Package) and the package can be viewed on [Pypi](https://pypi.org/project/graph-algo-vis/0.2/#description)    

To run the package: pip install graph-algo-vis    
<hr>

### Sample input file   

```
4
0 5 10 5
0 0 5 0
0 10 0 0
0 0 10 0
0

```    
<hr>  

### Sample output for DFS:   
![1](https://i.ibb.co/mXPTWQK/DFS-Result.png)   

### Sample output for Topological Sort:  
![2](https://i.ibb.co/Rz4qPMv/Graph-after-Topological-Sort.png)   

<hr>  

### Code for BFS  
<script src="https://gist.github.com/Akarsh654/7a2f08f2d039803c443af24f8fbfcd41.js"></script>
   

### Code for Topological Sort  
<script src="https://gist.github.com/Akarsh654/d31d1f4787df711aed59d320ba1ded77.js"></script>
<hr>  
