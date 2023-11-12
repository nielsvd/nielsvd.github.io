---
layout: default
---

## PhD on Real-time Optimal Control for Robot Arms

Without any bias, I can highly recommend reading the PhD thesis: [Online Motion Planning in Virtual Corridors - for Fast Robotic Systems](https://lirias.kuleuven.be/retrieve/527169).

### Table of Contents
- [Tunnel MPC for Robot Manipulators using SCQP](#tunnel-mpc-for-robot-manipulators-using-scqp)
- [Dual-objective NMPC near Target Manifolds](#dual-objective-nmpc-near-target-manifolds)
- [Dynamic Optimization with Partially Updated Sensitivities](#dynamic-optimization-with-partially-updated-sensitivities)
- [Optimal Control using a Path-parametric System Reformulation](#optimal-control-using-a-path-parametric-system-reformulation)
- [Acados](#acados)


### Tunnel MPC for Robot Manipulators using SCQP

Unfortunately, I never got to publishing my work on Tunnel MPC for robot manipulators in a paper; you can find results in [Chapter 3 of my thesis](https://lirias.kuleuven.be/retrieve/527169) though. You should definitely also checkout out this paper I co-authored with important foundations for the work described below: [Exploiting Convexity in Direct Optimal Control: a Sequential Convex Quadratic Programming Method](https://lirias.kuleuven.be/retrieve/420776); I still use this simple but elegant trick where possible to stabilize optimization schemes.

#### The Reference Approach: Gauss-Newton SQP for Tracking MPC <!-- omit from toc -->

<iframe width="699" height="393" src="https://www.youtube.com/embed/1O-KbzPDnFQ" title="IRB120 SCQP Path Following" frameborder="0" allowfullscreen></iframe>

#### Tunnel Following MPC allowing 20mm Path Deviation using SCQP <!-- omit from toc -->

<iframe width="699" height="393" src="https://www.youtube.com/embed/ASoASVIxNtQ" title="IRB120 SCQP Tunnel Following" frameborder="0" allowfullscreen></iframe>

#### Tunnel Following MPC allowing 10mm Path Deviation using SCQP <!-- omit from toc -->

<iframe width="699" height="393" src="https://www.youtube.com/embed/A7ea9qIqOuI" title="IRB120 SCQP Tunnel Following" frameborder="0" allowfullscreen></iframe>

#### Tunnel Following MPC allowing 1mm Path Deviation using SCQP <!-- omit from toc -->

<iframe width="699" height="393" src="https://www.youtube.com/embed/K78Cq7nCPhU" title="IRB120 SCQP Tunnel Following" frameborder="0" allowfullscreen></iframe>

### Dual-objective NMPC near Target Manifolds

* [Journal paper](https://lirias.kuleuven.be/retrieve/524502)
* [Conference paper](https://lirias.kuleuven.be/retrieve/482620)

_VIDEOS HERE_

### Dynamic Optimization with Partially Updated Sensitivities

* [Conference paper](https://lirias.kuleuven.be/retrieve/449936)
* [Co-authored conference paper](https://www.researchgate.net/profile/Yutao-Chen-6/publication/326508172_Efficient_Partial_Condensing_Algorithms_for_Nonlinear_Model_Predictive_Control_with_Partial_Sensitivity_Update/links/5b51b63345851507a7b2765c/Efficient-Partial-Condensing-Algorithms-for-Nonlinear-Model-Predictive-Control-with-Partial-Sensitivity-Update.pdf)

### Optimal Control using a Path-parametric System Reformulation

This is a really neat trick to reformulate the robot dynamics to become geometric of nature.
* [Real-time NMPC](https://lirias.kuleuven.be/retrieve/401348)
* [Optimal Control](https://lirias.kuleuven.be/retrieve/367564)

_VIDEOS HERE_

### Acados

I was actively involved in the development of the C tool for fast embedded optimal control [`acados`](https://github.com/acados/acados)
* [Paper about acados](https://arxiv.org/pdf/1910.13753)

[back](./)
