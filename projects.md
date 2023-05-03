---
layout: page
permalink: /projects/index.html
title: Projects
---

## Research Projects

The specific problems I have worked on so far are as follows:

- [network structure inference](https://chyj528.github.io/mypaper/ACC_2023_Learn_Game_Structure.pdf);
- [differentially private games](https://chyj528.github.io/mypaper/ACC_2023_Private_Game.pdf);
- [price shaping problem](https://chyj528.github.io/mypaper/Automatica_2022.pdf);
- [climate-economics dynamic game](https://chyj528.github.io/mypaper/arXiv_climate.pdf).

## Network Structure Inference

We investigate the capacity of an adversary to learn the underlying interaction
network through repeated best response actions in linear-quadratic games. The
adversary strategically perturbs the decisions of a set of action-compromised
players and observes the sequential decisions of a set of action-leaked players.
The central question pertains to whether such an adversary can fully reconstruct
or effectively estimate the underlying interaction structure among the players.

To begin with, we establish a series of results that characterize the
learnability of the interaction graph from the adversary's perspective by
drawing connections between this network learning problem in games and classical
system identification theory. Subsequently, taking into account the inherent
stability and sparsity constraints inherent in the network interaction
structure, we propose a stable and sparse system identification framework for
learning the interaction graph under both full player action observation and
partial player action observation.

Some of the results is accepted by ACC2023. The complete manuscript is 
available on request.

<div style="display:flex">
    <img src="https://chyj528.github.io/research/inference/noise_performance.png" alt="Image 1" style="width:50%;">
    <img src="https://chyj528.github.io/research/inference/T_performance.png" alt="Image 2" style="width:50%;">
</div>

## Differentially Private Games

We study network games where players are involved in information aggregation
processes subject to the differential privacy requirement for players’ payoff
functions. We propose a Laplace linear-quadratic functional perturbation (LLQFP)
mechanism, which perturbs players' payoff functions with linear-quadratic
functions whose coefficients are produced from truncated Laplace distributions.

For monotone games, we show that the LLQFP mechanism maintains the concavity
property of the perturbed payoff functions, and produces a perturbed NE whose
distance from the original NE is bounded and adjustable by Laplace parameter
tuning. We focus on linear-quadratic games, which is a fundamental type of
network games with players' payoffs being linear-quadratic functions, and derive
explicit conditions on how the LLQFP mechanism ensures differential privacy with
a given privacy budget.

<div style="display:flex">
<img src="https://chyj528.github.io/research/privacy/ne_distribution.png" 
alt="Image 1" style="width:50%;">
<img src="https://chyj528.github.io/research/privacy/payoffs.png" alt="Image 2" style="width:50%;">
</div>


## Climate-Economics Dynamic Game

One of the most widely used models for studying the geographical economics 
of climate change is the Regional Integrated model of Climate and the 
Economy (RICE). We investigate how cooperation and competition arise in regional climate policies under the RICE framework from the standpoints of game theory and optimal control. 

First, we show that the RICE model is inherently a dynamic game. Second, we
study both cooperative and non-cooperative solutions to this RICE dynamic game.

- Cooperative settings:
  - We investigate the global social welfare equilibrium that maximizes the
    weighted and cumulative social welfare across regions.
  - We divide the regions into two clusters: developed and developing, and look
    at the social welfare frontier under the notion of Pareto optimality.
  - We present a receding horizon approach to approximate the global social
    welfare equilibrium for robustness and computational efficiency.
- Non-cooperative settings:
  - We study best-response dynamics and open-loop Nash equilibrium of the RICE
    game. A Recursive Best-response Algorithm for Dynamic Games (RBA-DG) is
    proposed to describe the sequences of best-response decisions for dynamic
    games, which indicates convergence to open-loop Nash equilibrium when
    applied to the RICE game by numerical studies.
  - We also study online receding horizon feedback decisions of the RICE game. A
    Receding Horizon Feedback Algorithm for Dynamic Games (RHFA-DG) is proposed.

All these proposed solution concepts are implemented and open sourced using the
latest updated parameters and data.

The results reveal how game theory may be used to facilitate international
negotiations towards consensus on regional climate-change mitigation policies,
as well as how cooperative and competitive regional relations shape climate
change for our future.

<div style="display:flex">
    <img src="https://chyj528.github.io/research/climate/DICE_workflow.png" alt="Image 1" style="width:50%;">
    <img src="https://chyj528.github.io/research/climate/RICE_workflow.png" alt="Image 2" style="width:50%;">
</div>


