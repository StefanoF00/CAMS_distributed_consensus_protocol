# Project regarding Control of Autonomous Multi-Agent Systems presentation exam [Multi Robot Systems Module] @ Sapienza Università di Roma (MSc Control engineering)

Reproduction of the work presented by Cacace et al. in the Paper "A new distributed protocol for consensus of discrete-time systems" [https://doi.org/10.1016/j.ejcon.2023.100833], for didactic purpose. 

In ```/Implementation``` folder, there is the Python script for performing simulations over the three discussed approaches, adding enphasis on the critical design choices:
* Benchmark standard existing and outperformed centralized protocol, in which are highlighted the limits caused by the choice of coupling gain k;
* New proposed centralized protocol, in which are compared the performances by varying the parameter g;
* New proposed distributed protocol, stressing out the theoretical results of equivalence between centralized and distributed control law. 
