---
marp: true
theme: labmtg_theme
paginate: true
header: Start-up Seminar
footer: "2025/06/04"
math: mathjax
---

<!--
_class: lead
_paginate: false
_header: ""
_footer: ""
-->
## 250604
# Start-up Seminar for B4
## Shunta Kochi


---
<!--
_paginate: false
_header: ""
_footer: ""
-->
# Agenda

1. 機械学習とは何か
2. 機械学習プロジェクトの進め方
 

---
<!--
_class: sublead
_paginate: false
_header: ""
_footer: ""
-->

# 1. 機械学習とは何か？

---

**1. 機械学習とは何か？**

## 1. 機械学習とは
大量のデータから **入力→出力** の関係を学習し，未知データも予測できるアルゴリズムの集合

### なぜ機械学習か？
| 伝統的手法では困難 | 機械学習が得意 |
|-------------------|----------------|
| ルールが⻑大      | データ→自動学習 |
| 環境変動が激しい | 継続学習で追随 |
| データが膨大      | パターン抽出 |

---

**1. How are ML/DL Used in Urban Transportation?**

## 2. Traffic Control & Policy Optimization with RL
- Traffic Signal Control
- Dynamic routing: real-time navigation for drivers and AVs
- On-demand mobility: ride-hailing dispatch optimization
- Dynamic pricing: congestion tax, tolls, fares

→ Real-time adaptive mobility management

#### Papers
<small class="reference">
1. Jiang, Q., Qin, M., Shi, S., Sun, W., & Zheng, B. (2022). Multi-agent reinforcement learning for traffic signal control through universal communication method. arXiv. https://arxiv.org/abs/2204.12190<br>
2. Lu, R., Hong, S. H., & Zhang, X. (2018). A dynamic pricing demand response algorithm for smart grid: Reinforcement learning approach. Applied Energy, 220, 220–230. https://doi.org/10.1016/j.apenergy.2018.03.072

</small>

---

**1. How are ML/DL Used in Urban Transportation?**

## 3. Apply ML/DL to Public Transportation
- ML for demand and delay prediction
- Scheduling optimization
- Anomaly detection in equipment and systems

#### Papers
<small class="reference">
1. Alexandre, T., Bernardini, F., Viterbo, J., & Pantoja, C. E. (2023). Machine learning applied to public transportation by bus: A systematic literature review. Transportation Research Record, 2677(7), 639–660. https://doi.org/10.1177/03611981231174827<br>
2. Zhao, W. & Deng, J. (2025). Fault prediction and maintenance of urban rail transit power supply system based on big data. Applied Mathematics and Nonlinear Sciences, 10(1), 2025. https://doi.org/10.2478/amns-2025-0225<br>
3. Nassir, N., Balaprakash, P., & Ben-Akiva, M. (2023). MARLin: A meta-learned adaptive reinforcement learning policy for optimizing urban traffic signal control. *Information Sciences, 646*, 119063. https://doi.org/10.1016/j.ins.2023.119063

</small>

---

**1. How are ML/DL Used in Urban Transportation?**

## 4. Agent-Based Modeling $\times$ ML
- ABM reproduces traffic phenomena by simulating the behavior of individual agents
- An approach that uses machine learning to build a surrogate model as a proxy for the simulator and performs a fast approximate evaluation has been attracting attention
- Incorportate LLM into agent decision making to reproduce a wide variety of behavior patterns and decision-making processes.
- Integrate Reinforcement Learning into ABM and search for effective interventions

#### Papers
<small class="reference">
1. Natterer, E. S., Rao, S. R., Tejada Lapuerta, A., Engelhardt, R., Hörl, S., & Bogenberger, K. (n.d.). Machine learning surrogates for agent-based models in transportation policy analysis. SSRN. https://doi.org/10.2139/ssrn.5182100<br>
2. Liu, T., Yang, J., & Yin, Y. (2025). Toward LLM-agent-based modeling of transportation systems: A conceptual framework. arXiv. https://arxiv.org/abs/2412.06681<br>
3. Yuan, Y., Silva, F. L. da, & Glatt, R. (2023). Reinforcement learning in agent-based modeling to reduce carbon emissions in transportation. In NeurIPS 2023 Workshop on Tackling Climate Change with Machine Learning. https://www.climatechange.ai/papers/neurips2023/70
</small>

---

**1. How are ML/DL Used in Urban Transportation?**

## 5. On-Demand Mobility Systems

- Demand prediction and vehicle dispatch optimization
- MaaS, ride-sharing , autonomous taxi fleet management

#### Papers
<small class="reference">
1. Eshkevari, S. S., Tang, X., Qin, Z., Mei, J., Zhang, C., Meng, Q., & Xu, J. (2022). Reinforcement learning in the wild: Scalable RL dispatching algorithm deployed in ridehailing marketplace. arXiv. https://arxiv.org/abs/2202.05118<br>
2. Brusselaers, N., Hjorth, S., Fredriksson, A. and Gundlegård, D. (2025), "The potential of machine learning modeling to predict urban construction transport demand", Smart and Sustainable Built Environment, Vol. ahead-of-print No. ahead-of-print. https://doi.org/10.1108/SASBE-12-2024-0558
</small>

---
<!--
_class: sublead
_paginate: false
_header: ""
_footer: ""
-->

# 2. Adaptive Traffic Signal Control with RL
![bg left](../images/TSC_with_RL.png)

---

**2. Adaptive Traffic Signal Control with RL**

## Background
- Urban traffic congestion is a serious societal issue, significantly influenced by the method of traffic signal control.
- Traditional systems relied on fixed-time or traffic-actuated controls based on empirical rules.
- There is a growing demand for autonomous signal control that can adapt in real time to changing traffic conditions.
- Recently, reinforcement learning has gained attention as a promising approach, enabling signal agents to learn optimal control policies through trial and error.

#### Papers
<small class="reference">
1. Wang, Y., Long, M., Wu, Q., Liu, W., Pi, J., & Yang, X. (2025). A parallel hybrid action space reinforcement learning model for real-world adaptive traffic signal control. arXiv. https://arxiv.org/abs/2503.14250
</small>

---

**2. Adaptive Traffic Signal Control with RL**

## RL Architectures for Signal Control
- Reinforcement Learning for large-scale traffic signal control can be broadly categorized based on agent architecture: single-agent, multi-agent, and hierarchical approaches.

### 1. Single-Agent
- Control the entire network with one RL agent

#### Papers
<small class="reference">
1. Li, Q., Niu, J., Luo, Q., & Yu, L. (2025). Large-scale regional traffic signal control based on single-agent reinforcement learning. arXiv. https://arxiv.org/abs/2503.09252
arXiv<br>
</small>

---

**2. Adaptive Traffic Signal Control with RL**

## RL Architectures for Signal Control

### 2. Multi-agent
- Assign an agent to each intersection, offering scalability but requiring coordination


#### Papers
<small class="reference">
1. Wei, H., Chen, C., Zheng, G., Wu, K., Gayah, V., Xu, K., & Li, Z. (2019). PressLight: Learning max pressure control to coordinate traffic signals in arterial network. In Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining (pp. 1290–1298). ACM. https://doi.org/10.1145/3292500.3330949
<br>

</small>

---

**2. Adaptive Traffic Signal Control with RL**

## RL Architectures for Signal Control

### 3. Hierarchical control
- An approach that lies between the above two and divides the control problem hierarchically has also been studied.


#### Papers
<small class="reference">
1. Fu, Y., Zhong, L., Li, Z., & Di, X. (2025). Federated hierarchical reinforcement learning for adaptive traffic signal control. arXiv. https://doi.org/10.48550/arXiv.2504.05553<br>
</small>

---

**2. Adaptive Traffic Signal Control with RL**

## Simulation Platforms

- **SUMO**: German open-source traffic simulator known for its detailed vehicle-level simulation and external control via TraCl, widely used in RL studies for medium-scale networks.
- **CityFlow**: Developed by Tsinghua University. It is specialized for large-scale traffic network simulations and is increasingly used as a benchmark environment for multi-intersection RL control.
- **MATSim**: Less commonly used for directly integrating reinforcement learning agents, with relatively few examples of such implementations.


#### Papers
<small class="reference">
1. Fu, Y., Zhong, L., Li, Z., & Di, X. (2025). Federated hierarchical reinforcement learning for adaptive traffic signal control. arXiv. https://doi.org/10.48550/arXiv.2504.05553<br>
</small>

---
<!--
_class: sublead
_paginate: false
_header: ""
_footer: ""
-->

# 3. Dynamic Route Optimization
![bg right](../images/Route_Opt.png)

---

**3. Dynamic Route Optimization**

## Background

- Dynamic route optimization in urban traffic systems refers to guiding vehicles in real time based on traffic congestion and demand fluctuations.
- In reinforcement learning, agents observe traffic states (e.g., congestion levels, vehicle position) and learn optimal routing policies through trial-and-error interactions that yield rewards.
- The main goals include minimizing total travel time and congestion, and reducing fuel consumption.

---

**3. Dynamic Route Optimization**

## RL Algorithms

- Classical methods like Q-learning or DQN
- Multi-agent frameworks such as RouteRL enable collaborative learning among vehicle agents, and newer approaches incorporate GNNs and Transformers for generalization and complex planning tasks.

#### Papers
<small class="reference">
1. Koh, S., Zhou, B., Fang, H., Yang, P., Yang, Z., Yang, Q., Guan, L., & Jie, Z. (2020). Real-time deep reinforcement learning based vehicle routing and navigation. Applied Soft Computing, 96, 106694. https://doi.org/10.1016/j.asoc.2020.106694<br>
2. Akman, A. O., Psarou, A., Gorczyca, Ł., Varga, Z. G., Jamróz, G., & Kucharski, R. (2025). RouteRL: Multi-agent reinforcement learning framework for urban route choice with autonomous vehicles. arXiv. https://doi.org/10.48550/arXiv.2502.20065<br>
3. Fuertes, D., Cavallaro, A., del-Blanco, C. R., Jaureguizar, F., & García, N. (2023). NaviFormer: A deep reinforcement learning transformer-like model to holistically solve the navigation problem. OpenReview. https://openreview.net/forum?id=Pj3ErOxlLo
</small>

---

**3. Dynamic Route Optimization**

## Routing Strategies
- **Centralized routing**: A traffic control center or server computing optimal routes for the entire city and distributing them to individual vehicles.
- **Decentralized cooperative routing**: allows each vehicle (agent) to independently determine its path, with recent research focusing on enabling inter-vehicle communication and coordination for improved efficiency.

#### Papers
<small class="reference">
1. Xiao, Z., Li, P., Liu, C., Gao, H., & Wang, X. (2024). MACNS: A generic graph neural network integrated deep reinforcement learning based multi-agent collaborative navigation system for dynamic trajectory planning. Information Fusion, 105, 102250. https://doi.org/10.1016/j.inffus.2024.102250<br>
</small>

---

**3. Dynamic Route Optimization**

## Simulation Platforms

- **SUMO**: Well-suited for microscopic traffic flow simulation, enabling detailed modeling of individual vehicle behavior.
- **MATSim**: Designed for large-scale urban transportation simulation, making it suitable for evaluating city-wide dynamic routing strategies.

---
<!--
_paginate: false
_header: ""
_footer: ""
-->

# Schedule

**May** : Decide research topic
**Early June**: Study related work and model techniques
**Late June**: Conduct preliminary analysis
**July**: Build a prototype model
