# NETWORK-ANALYSIS-OF-CLASS-STUDENTS-FOR-BENCH-PARTNER-
Project analysis on dataset of class students to select a bench partner using R.

1 impIemented a small social network of a class bench partner which have around 27 nodes that represents all students of class.

2 These nodes are interconnected with each other in such a format  that they represent a social network of seating arrangement.

3 By looking at the network we can see the connectivity among students how they are prefer their friends to seat beside them.

## STEPS:

-Read csv for nodes and edges.

-Use graph.data.frame function to create network of nodes and edges.

-Find adjecency matrix.

-Plot the graph using plot function and assign arrow size to edges for better understanding.

-Count the number of nodes using vcount function.

-Count the number of edges using ecount function.

-Find the density function using,
		(ecount)/(vcount*vcount-1)
-Find the degree of each node.

-Find transitivity using,
	         (no. of ties evolved in reciprocal relation)/(total 						no. of actual ties).
           
![dataset](https://user-images.githubusercontent.com/32256364/42993281-9d9c0b30-8c28-11e8-8339-db4456d12e8b.png)
![network](https://user-images.githubusercontent.com/32256364/42993282-9ddcd214-8c28-11e8-8098-eccd0f1841f6.png)     
           
 ## Conclusion:
 
 In this whole study work, a network of students and their choice for bench partner plotted graphically. This shows the connectivity among all students and their first second choice for bench partner. So it forms a small social network which shows seating arrangement for class students with their choice for bench partners.

