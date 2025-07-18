# "Complexity: 5 Questions" bipartite expert-ideas network 

Data for the bipartite expert-ideas network extracted from the 24 interviews in the book "Complexity: 5 Questions" (Gershenson, 2008). Book available here: https://www.researchgate.net/publication/260868740_Complexity_5_Questions

The data comes as a source-target edgelist:
* source (the interviewee, e.g. "Peter M. Allen")
* target (a keyword, e.g. "networks")

Important note: 
* Using ChatGPT-4o, 10 keywords were retrieved for each interviewee's perspective on complexity; then, a semantic analysis was performed. 

The figure below was created using Cytoscape. For visualization purposes, (node) ideas are colored according to the degree ($k$): gray ($k<6$), blue ($6\leq k <12$), and red ($k\geq 12$); with $k=12$ meaning at least 50% co-occurrence.

<img src="complexity_bipartie_network.png" alt="Complexity" width="800px"/>

Also, check out Hiroki Sayama's repository for rigorous data collection of complex systems topics: https://github.com/hsayama/complex-systems-topic-network-2024