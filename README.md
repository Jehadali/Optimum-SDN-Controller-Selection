# Optimum-SDN-Controller-Selection

The optimal SDN controller selection methodology is explained here.


Feature based analysis were performed uisng ANP and AHP. Problem formulation and Modeling was done through ANP as explained in the paper.


The experiments can be performed for checking the QoS Improvement.


The delay calculation module finds the delay between the source and destination hosts using tcpdumps


B_1 and B_2 are the topologies generated via Brite. Link for topologies generation via brite is given below; The topology generation model we have used is waxman.

The pdf file in the files section named "Topology generation via brite.pdf" explains step by step process how we have generated these topologies.

https://www.cs.bu.edu/brite/user_manual/node30.html


The topology conversion module converts the topolgies generated via Brite i.e. B_1 and B_2 to Mininet. It uses FNSS i.e. Fast network simulation setup i.e.

https://fnss.github.io/

Topology parsing from FNSS 

https://fnss.readthedocs.io/en/latest/_modules/fnss/topologies/parsers.html#parse_brite

Installing and downloading BRITE 

https://www.cs.bu.edu/brite/user_manual/node46.html

The D-ITG calculates the delay between the source and destination during the high traffic load scenario.

http://www.grid.unina.it/software/ITG/

The link to video i have made for mininet installation 

https://www.youtube.com/watch?v=nXzyFWYE5Sw&t=86s

How to create any topology and save it as a python code. Please follow this link i have created a video for it.

https://www.youtube.com/watch?v=tzRG-0eQHA0&feature=youtu.be
