# "Complexity: 5 Questions" bipartite network 

Data for the bipartite expert-ideas network extracted from the 24 interviews in the book "Complexity: 5 Questions" (Gershenson, 2008). Book available here: https://www.researchgate.net/publication/260868740_Complexity_5_Questions

The data comes as a source-target edgelist:
* source (the interviewee, e.g. "Peter M. Allen")
* target (a keyword, e.g. "networks")

**Method:** Using ChatGPT-4o, 10 keywords were retrieved for each interviewee's perspective on complexity; then, a semantic analysis was performed. After loading the file, the prompt used was the following (step by step execution is recommended):

1. Identify the 24 interviewees in the book.
2. For each of the 24 interviewees extract 10 keywords related to the interviewee's perspective on complexity. Create a two-column table: "expert" and "keywords". Convert the keywords to a simpler underscored form. Remove special characters.
3. Perform a semantic analysis over the keywords.
4. Create an source-target edgelist table. The "source" column will contain the name of the expert, the "target" column the keywords. 
5. Export to csv.

_Important note:_ The output might vary even for the same prompt.

The figure below was created using Cytoscape. For visualization purposes, (node) ideas are colored according to the degree ($k$): gray ($k<6$), blue ($6\leq k <12$), and red ($k\geq 12$); with $k=12$ meaning at least 50% co-occurrence.

<img src="complexity_bipartie_network.png" alt="Complexity" width="800px"/>

Also, check out Hiroki Sayama's repository for rigorous data collection of complex systems topics: https://github.com/hsayama/complex-systems-topic-network-2024

Contact: nico.carlock@gmail.com
