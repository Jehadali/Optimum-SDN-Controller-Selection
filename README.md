# Optimum-SDN-Controller-Selection

The optimal SDN controller selection methodology is explained here.


The experiments can be performed for checking the QoS Improvement.


The delay calculation module finds the delay between the source and destination hosts using tcpdumps


B_1 and B_2 are the topologies generated via Brite. Link for topologies generation via brite is given below; The topology generation model we have used is waxman.

https://www.cs.bu.edu/brite/user_manual/node30.html


The topology conversion module converts the topolgies generated via Brite i.e. B_1 and B_2 to Mininet. It uses FNSS i.e. Fast network simulation setup i.e.

https://fnss.github.io/


The D-ITG calculates the delay between the source and destination during the high traffic load scenario.

http://www.grid.unina.it/software/ITG/

