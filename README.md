# Job Shop Scheduling Problem instances tailored to different goals
---
This repository contains the instances generated for the manuscript "Tailoring Job Shop Scheduling Problem Instances through Unified Particle Swarm Optimization", accepted for publication in *IEEE Access*.

## Available instances and instance organization
To make things easier for the user, we have organized the instances into subfolders, following the same structure from the manuscript:

-  **1_Simple instances**: 30 instances that favor LPT while hindering SPT and 30 instances with the opposite goal. These instances were generated with fixed parameters for the UPSO algorithm. 
-  **2_Unbounded instances 1v1**: 9720 instances used 
-  **3_Unbounded intances 1v3**
-  **4_Bounded instances**
-  **5_Large instances**
-  **6_Feature-focused instances**

---
*Disclaimer*: These files provide support for directly running tests within Matlab. To this end the [`MatHH`](https://github.com/iamaya2/MatHH) framework is required. In case you do not want to use `MatHH`, each instance contains a property named `rawInstanceData` with the numerical information of the instance. 

