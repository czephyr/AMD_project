## pySpark PageRank
Implementation of the PageRank algorithm using pySpark. 

The project implements Pagerank with teleportation, to avoid spider-traps, and the topic-aware version of the algorithm.

The dataset used to compose the graph was a slice of the Amazon Reviews dataset where products are linked if ever reviewed by at least one shared user. 

It is shown that the topic-aware version of the algorithm ranked products of the selected category with an higher average pagerank value.

The code is availabe in [colab_project.ipynb](colab_project.ipynb).
A quick report on the obtained results is available in [report.pdf](report.pdf)
