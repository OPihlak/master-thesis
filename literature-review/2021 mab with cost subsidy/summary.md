It introduces a novel variant of the multi-armed bandit problem that
incorporates the cost of selecting an arm, relevant for applications where the learning agent must consider both cost
and reward optimization. The study demonstrates that traditional multi-armed bandit algorithms do not perform well in
this setting. It establishes a fundamental lower bound on the performance of any online learning algorithm for this
problem and proposes a new algorithm, Cost-Subsidized Explore-Then-Commit (CS-ETC), which achieves near-optimal regret
bounds. The paper includes extensive numerical simulations to compare various algorithms and provides practical guidance
on their use in different scenarios.