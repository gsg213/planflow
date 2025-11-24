# PlanFlow: Local trajectory planning for autonomous driving using Flow-guided occupancy grids

## Abstract
Local trajectory planning for autonomous vehicles in urban scenarios requires reliable decisions around dense traffic and several agents’ interactions. The planner’s input strongly influences its reaction to different situations, hence the importance of choosing the appropriate representation. Bird’s-eye-view (BEV) grids provide spatial coverage, while vectorized representations offer efficiency but risk missing information. We propose using flow-guided occupancy grids, which are BEV occupancy maps augmented with cell flow vectors to combine occupancy, motion and uncertainty. Based on this representation, we present PlanFlow, a model based on a compact CNN as backbone with a MLP decoder, trained combining L1 and collision aware losses. We trained and evaluated PlanFlow on nuScenes against BEV input baselines, achieving robust accuracy and low collision rates, displaying improvement over the SOTA approaches by using flow-guided grids for trajectory planning reasoning.


## Qualitative results
A scene from nuScenes validation split is used to validate the trajectories in each scenario.
Example 1:
<img src="./imgs/S0.gif">
Example 2:
<img src="./imgs/S1.gif">
Example 3:
<img src="./imgs/S2.gif">
Example 4:
<img src="./imgs/S3.gif">
Example 5:
<img src="./imgs/S4.gif">
Example 6:
<img src="./imgs/S5.gif">
