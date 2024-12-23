# LEF-Latent-Exploration-Framework

## Overview

Exploration remains a significant challenge in deep reinforcement learning (RL), particularly in complex environments with high-dimensional observations and sparse rewards. Traditional exploration strategies, like $\epsilon$-greedy and Boltzmann exploration, often fail in such environments, as they do not effectively support the discovery of far-off rewards. To address this, latent-based exploration is proposed to enhance exploration in high-dimensional state spaces by integrating latent representations. 


## Benchmark Comparison

Existing latent-based exploration methods across several metrics. The following table summarizes the key features of different algorithms:

| Algorithm       | Exploration Bonus                                     | Latent Space   | EET | SRL | TAM |
|-----------------|-------------------------------------------------------|----------------|-----|-----|-----|
| RE3             |     | Random         | ✗   | ✗   | ✗   |
| RLE             |                | Random         | ✗   | ✗   | ✗   |
| ICM             |  | Dynamics-based | ✗   | ✓   | ✗   |
| RIDE            | | Dynamics-based | ✗   | ✓   | ✗   |
| LIBERTY         |        | Metric-based   | ✗   | ✗   | ✗   |
| EME             |  | Metric-based   | ✓   | ✗   | ✗   |
| E3B |   |  |  Dynamics-based|  ✓   | ✗   | ✗   |
| ... |   | ... | ...   | ...   | ..  |


## Installation
 

