---
layout: default
---

## Robust Collision-free Navigation in Confined Spaces

Work carried out by PhD student Yunfan Gao (University of Freiburg & Bosch):
* [Semi-Infinite Programming for Collision-Avoidance in Optimal and Model Predictive Control](https://arxiv.org/pdf/2508.12335)
* [Stochastic Model Predictive Control with Optimal Linear Feedback for Mobile Robots in Dynamic Environments](https://arxiv.org/pdf/2407.14220)
* [Real-Time-Feasible Collision-Free Motion Planning For Ellipsoidal Objects](https://arxiv.org/pdf/2409.12007)
* [Collision-free Motion Planning for Mobile Robots by Zero-order Robust Optimization-based MPC](https://arxiv.org/pdf/2306.17445)

## Industrial Multi-Robot Navigation

An industrial perspective on multi-robot planning in factories and warehouses:
* [Link to workshop paper](https://github.com/nielsvd/nielsvd.github.io/files/13329013/van_Duijkeren_et_al_2022_An_Industrial_Perspective_on_Multi-Agent_Decision_Making.pdf)

## Caster-wheel Aware MPC for Mobile Robots

Work carried out by MSc thesis student Jon Arrizabalaga (at Bosch):
* [Link to conference paper](https://arxiv.org/pdf/2110.05604)

## Traffic Control by Reordering Execution Schedules

Work carried out by MSc thesis student Alex Berndt (at Bosch).
* [Link to IEEE Transactions on Robotics paper](https://arxiv.org/pdf/2312.04190)
  * [Link to code](https://github.com/alexberndt/sadg-controller)
* [Link to workshop paper](https://arxiv.org/abs/2010.05254)
* [Alex' talk during the workshop](https://www.youtube.com/watch?v=EOthdSH1jYE)

The SADG-based (Switchable Action Dependency Graph) control scheme enables fast reaction times to delayed vehicles in the execution of a multi-agent routing plan without recomputing the solution to a new MAPF problem. It instead solves a smaller-scale MILP problem to determine a new ordering for vehicles to visit resources.

SADG Receding Horizon Feedback Control Scheme | Typical MAPF Execution Schemes |
:-------------------------:|:-------------------------:|
![](assets/diagrams/feedback_diagram.svg)| ![](assets/diagrams/typical_mapf_scheme.svg) |

_Our approach significantly reduces the cumulative route completion of agents subjected to large delays by optimizing the ordering of agents based on their progress in a receding horizon fashion, while maintaining collision- and deadlock-free plan execution guarantees._

 Switchable Action Dependency Graph | Roadmap |
:-------------------------:|:-------------------------:|
![](assets/animations/sadg.gif) | ![](assets/animations/roadmap.gif) |


[back](./)
