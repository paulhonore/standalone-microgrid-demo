# Standalone microgrid: one fuel tank, no refilling

**Live demo: https://paulhonore.github.io/standalone-microgrid-demo/**

**The microgrid is standalone (islanded): there is no connection to the power grid.**
**The fuel tank is filled only once, at the beginning of the planning period. There is no refuelling.**

Cost-optimal management of solar panels, a battery and a fuel generator over one week, computed by
stochastic optimal control. The page shows simulated weeks hour by hour, compares three strategies
and displays the optimal decision rule and the value function. The tank size (20 l benchmark, up to
100 l) and the penalty for unserved demand can be changed to see their effect on the control.

Paper: P. H. Takam and N. Fruiba, *Stochastic Optimal Control for the Cost-Optimal Management of a
Standalone Microgrid*. Preprint (earlier title): [arXiv:2511.00167](https://arxiv.org/abs/2511.00167).

Research demo. The source code is not part of this repository. No license is granted for redistribution.
