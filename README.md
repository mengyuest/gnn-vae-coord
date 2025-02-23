# Reliable and Efficient Multi-Agent Coordination via Graph Neural Network Variational Autoencoders

[![Conference](https://img.shields.io/badge/ICRA2025-Accepted-success)](https://2025.ieee-icra.org/)

[Project page](https://mengyuest.github.io/gnn-vae-coord/)

[<ins>Yue Meng</ins><sup>1</sup>](https://mengyuest.github.io/), [<ins>Nathalie Majcherczyk</ins><sup>2</sup>](https://scholar.google.com/citations?hl=en&user=gQMpFlIAAAAJ&view_op=list_works&sortby=pubdate), [<ins>Wenliang Liu</ins><sup>2</sup>](https://scholar.google.com/citations?user=bO40W5UAAAAJ&hl=en), [<ins>Scott Kiesel</ins><sup>2</sup>](https://scholar.google.com/citations?hl=en&user=hRyYQAIAAAAJ&view_op=list_works&sortby=pubdate), [<ins>Chuchu Fan</ins><sup>1</sup>](https://chuchu.mit.edu/), [<ins>Federico Pecora</ins><sup>2</sup>](https://www.amazon.science/author/federico-pecora)

[<sup>1</sup><ins>Reliable Autonomous Systems Lab @ MIT (REALM)</ins>](https://aeroastro.mit.edu/realm/) 

[<sup>2</sup><ins>Amazon Robotics</ins>](https://amazon.jobs/content/en/teams/ftr/amazon-robotics)

> Official implementation for ICRA2025 paper, "Reliable and Efficient Multi-Agent Coordination via Graph Neural Network Variational Autoencoders." [\[link\]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10638176)

> The work was done when Yue was an Applied Science Intern at Amazon Robotics.

## Formulation
![image info](./img/coord-formulation.png)
Coordination graph formualation


![image info](./img/gnn-vae-coord-arch.png)
GNN-VAE framework for Multi-agent coordination


## Experimental results
![image info](./img/viz_scale_tavg_v1.png)
<b>Ours</b> can generate close-to-oracle (<b>MILP</b>) assignments with the optimality ratio consistently over 0.9 while the optimality ratio curves for <b>B-BTS</b> and <b>CMA-ES</b> drop quickly as the number of robots is more than 20. This shows the great generalizability of our approach. <b>Ours</b> can be 10 to 20 times faster than the baselines, solving coordination problem with 250 robots in less than 5 seconds on average.

## Requirements and Demos
Coming soon.