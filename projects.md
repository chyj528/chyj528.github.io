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
- [cooperation and non-cooperation for climate-economics](https://chyj528.github.io/mypaper/arXiv_climate.pdf).

[comment]: <> (### Network Structure Inference)

[comment]: <> (We investigate the capacity of an adversary to learn the underlying interaction)

[comment]: <> (network through repeated best response actions in linear-quadratic games. The)

[comment]: <> (adversary strategically perturbs the decisions of a set of action-compromised)

[comment]: <> (players and observes the sequential decisions of a set of action-leaked players.)

[comment]: <> (The central question pertains to whether such an adversary can fully reconstruct)

[comment]: <> (or effectively estimate the underlying interaction structure among the players.)

[comment]: <> (To begin with, we establish a series of results that characterize the)

[comment]: <> (learnability of the interaction graph from the adversary's perspective by)

[comment]: <> (drawing connections between this network learning problem in games and classical)

[comment]: <> (system identification theory. Subsequently, taking into account the inherent)

[comment]: <> (stability and sparsity constraints inherent in the network interaction)

[comment]: <> (structure, we propose a stable and sparse system identification framework for)

[comment]: <> (learning the interaction graph under both full player action observation and)

[comment]: <> (partial player action observation.)

[comment]: <> (Some of the results is accepted by ACC2023. The complete manuscript is )

[comment]: <> (available on request.)

[comment]: <> (<div style="display:flex">)

[comment]: <> (    <img src="https://chyj528.github.io/research/inference/noise_performance.png" alt="Image 1" style="width:50%;">)

[comment]: <> (    <img src="https://chyj528.github.io/research/inference/T_performance.png" alt="Image 2" style="width:50%;">)

[comment]: <> (</div>)

[comment]: <> (### Differentially Private Games)

[comment]: <> (<img src="https://chyj528.github.io/research/privacy/Pipeline.png">)

[comment]: <> (We study network games where players are involved in information aggregation)

[comment]: <> (processes subject to the differential privacy requirement for players’ payoff)

[comment]: <> (functions. We propose a Laplace linear-quadratic functional perturbation &#40;LLQFP&#41;)

[comment]: <> (mechanism, which perturbs players' payoff functions with linear-quadratic)

[comment]: <> (functions whose coefficients are produced from truncated Laplace distributions.)

[comment]: <> (For monotone games, we show that the LLQFP mechanism maintains the concavity)

[comment]: <> (property of the perturbed payoff functions, and produces a perturbed NE whose)

[comment]: <> (distance from the original NE is bounded and adjustable by Laplace parameter)

[comment]: <> (tuning. We focus on linear-quadratic games, which is a fundamental type of)

[comment]: <> (network games with players' payoffs being linear-quadratic functions, and derive)

[comment]: <> (explicit conditions on how the LLQFP mechanism ensures differential privacy with)

[comment]: <> (a given privacy budget.)

[comment]: <> (### Price Shaping Problem)

[comment]: <> (&#40;to guarantee unit resource price under a threshold&#41;)

[comment]: <> (<img src="https://chyj528.github.io/research/shaping/rhp_ehp.png">)

[comment]: <> (### Cooperation and Non-cooperation for Climate-Economics)

[comment]: <> (<div style="display:flex">)

[comment]: <> (    <img src="https://chyj528.github.io/research/climate/DICE_workflow.png" alt="Image 1" style="width:50%;">)

[comment]: <> (    <img src="https://chyj528.github.io/research/climate/RICE_workflow.png" alt="Image 2" style="width:50%;">)

[comment]: <> (</div>)


[comment]: <> (<div class="no-indent">)

[comment]: <> (One of the most widely used models for studying the geographical economics )

[comment]: <> (of climate change is the Regional Integrated model of Climate and the )

[comment]: <> (Economy &#40;RICE&#41;. We investigate how cooperation and competition arise in regional climate policies under the RICE framework from the standpoints of game theory and optimal control. )

[comment]: <> (First, we show that the RICE model is inherently a dynamic game. Second, we)

[comment]: <> (study both cooperative and non-cooperative solutions to this RICE dynamic game.)

[comment]: <> (- Cooperative settings:)

[comment]: <> (  - We investigate the global social welfare equilibrium that maximizes the)

[comment]: <> (    weighted and cumulative social welfare across regions.)

[comment]: <> (  - We divide the regions into two clusters: developed and developing, and look)

[comment]: <> (    at the social welfare frontier under the notion of Pareto optimality.)

[comment]: <> (  - We present a receding horizon approach to approximate the global social)

[comment]: <> (    welfare equilibrium for robustness and computational efficiency.)

[comment]: <> (- Non-cooperative settings:)

[comment]: <> (  - We study best-response dynamics and open-loop Nash equilibrium of the RICE)

[comment]: <> (    game. A Recursive Best-response Algorithm for Dynamic Games &#40;RBA-DG&#41; is)

[comment]: <> (    proposed to describe the sequences of best-response decisions for dynamic)

[comment]: <> (    games, which indicates convergence to open-loop Nash equilibrium when)

[comment]: <> (    applied to the RICE game by numerical studies.)

[comment]: <> (  - We also study online receding horizon feedback decisions of the RICE game. A)

[comment]: <> (    Receding Horizon Feedback Algorithm for Dynamic Games &#40;RHFA-DG&#41; is proposed.)

[comment]: <> (All these proposed solution concepts are implemented and open sourced using the)

[comment]: <> (latest updated parameters and data.)

[comment]: <> (The results reveal how game theory may be used to facilitate international)

[comment]: <> (negotiations towards consensus on regional climate-change mitigation policies,)

[comment]: <> (as well as how cooperative and competitive regional relations shape climate)

[comment]: <> (change for our future.)

[comment]: <> (</div> )