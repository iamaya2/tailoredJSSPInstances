# Job Shop Scheduling Problem instances tailored to different goals
---
This repository contains the instances generated for the manuscript "Tailoring Job Shop Scheduling Problem Instances through Unified Particle Swarm Optimization", accepted for publication in *IEEE Access*.

## Available instances and instance organization
To make things easier for the user, we have organized the instances into subfolders, following the same structure from the manuscript:

1. [**Simple instances**:](./Instances/1_Simple%20instances) 30 instances that favor LPT while hindering SPT and 30 instances with the opposite goal. These instances were generated with fixed parameters for the UPSO algorithm. Total: 60 instances.
1. [**Unbounded instances 1v1**:](./Instances/2_Unbounded%20instances%201v1) 30 instances for 4 pair-wise comparisons with 81 different parameter combinations for UPSO. Total: 9720 instances.
1. [**Unbounded intances 1v3**:](./Instances/3_Unbounded%20intances%201v3) 30 instances generated for favoring one heuristic while hindering the others, and viceversa, for 4 heuristics. These instances are generated with the best two parameter configurations for UPSO. Total: 480 instances.
1. [**Bounded instances**:](./Instances/4_Bounded%20instances) Similar to the previous one but this folder also considers 5 specific performance gap levels between the solvers. Total: 2400 instances.
1. [**Large instances**:](./Instances/5_Large%20instances) 30 larger instances for 8 different heuristic configurations. These instances are generated with the best parameter settings identified for UPSO. Total: 240 instances.
1. [**Feature-focused instances**:](./Instances/6_Feature-focused%20instances) 100 instances that maximize the value for each available feature and 100 instances that minimize them. Additionally, 2500 instances with intermediate feature values. Total: 3500 instances.

## Requirements
- Matlab R2020b
- [MatHH framework](https://github.com/iamaya2/MatHH)
- 16 GB RAM

## Disclaimer
These files provide support for directly running tests within Matlab. To this end the [`MatHH`](https://github.com/iamaya2/MatHH) framework is required. In case you do not want to use `MatHH`, each instance contains a property named `rawInstanceData` with the numerical information of the instance. 

## Contact information
Iván Amaya - [iamaya2@tec.mx](mailto:iamaya2@tec.mx)

Distributed under the MIT license. See [LICENSE](./LICENSE) for more information.
