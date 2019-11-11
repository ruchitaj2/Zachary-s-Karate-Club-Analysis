# Zachary's Karate Club Graph Analysis

This is an assignment on NetworkX graph analysis for a data science program. An unweighted network data of Zachary's Karate Club was given for analysis. Several centrality metrics were calculated for all nodes to compare how influential or important the nodes are in the network. The graph was then visualized to show nodes in different sizes according to degree of each node. 

The network is then clustered using Spectral CLustering algortihm to see whether the resulting clusters centered on node 34 and node 1 and whether node 9 stayed with node 34 (the administrator of the club) or node 1 (the instructor of the club). How are these result compared to the results of the original study. Did these algorithm successfully predict who node 9 sided with?

Read about Zachary’s Karate Club Problem here: https://en.wikipedia.org/wiki/Zachary% 27s_karate_club. 

My Directory to analysis: https://github.com/ruchitaj2/Zachary-s-Karate-Club-Analysis

## Dataset Information:

Download the adjacency matrix for this problem from here:
http://networkdata.ics.uci.edu/data/karate/
and obtain the correct community assignments from Table 1 (column: club after ﬁssion) in the original paper:
http://aris.ss.uci.edu/~lin/76.pdf 

## Objective of the exercise:
Perform spectral clustering for k = 2 and report the two clusters.
(It is recommended (though not required) to use MATLAB as it is extremely eﬃcient for solving both problems.)

## Instrustions for running the code:
1. The corresponding codes are in .ipnyb format which requires Jupyter notebook.  
2. Make sure the dataset required is in the same folder path as the .ipnyb file.   
3. Dataset file : karate.gml 
4. Please run the blocks sequentially.  


## Reference: 
Zachary W. (1977). An information flow model for conflict and fission in small groups. Journal of Anthropological Research, 33, 452-473.


