<h1>4. Frozen Lake</h1>
<h2>Deterministic Environment</h2>
<h3>Policy Iteration</h3>
The optimal policy from policy iteration is [1 2 1 0 1 0 1 0 2 1 1 0 0 2 2 0]

<h3>Value Iteration</h3>
The optimal policy from value iteration is [1 2 1 0 1 0 1 0 2 1 1 0 0 2 2 0]

<h3>Comment:</h3>
Terminated in 6 steps for both policy iteration and value iteration. The reward is 1 for sure.
The path is deterministic. 0->4->8->9->13->14->15.

<h2>Stochastic Environment(0.1,0.8,0.1 probability in three direction)</h2>
<h3>Policy Iteration</h3>
The optimal policy from policy iteration is [1 2 1 0 1 0 1 0 2 1 1 0 0 2 2 0]

<h3>Value Iteration</h3>
The optimal policy from value iteration is [1 2 1 0 1 0 1 0 2 1 1 0 0 2 2 0]

<h3>Comment:</h3>
Termination may or may not take more steps for both policy iteration and value iteration. The reward maybe 1 or 0 depending on whether fall into the hole or not.
The path is random. For example, one experiment takes 7and 8 steps for policy and value iteration to get to reward one. Another may take 5 steps and fall into the hole and get zero reward.

<h2>Stochastic Environment(1/3 probability in three direction)</h2>
<h3>Policy Iteration</h3>
The optimal policy from policy iteration is [0 3 0 3 0 0 0 0 3 1 0 0 0 2 1 0]

<h3>Value Iteration</h3>
The optimal policy from value iteration is [0 3 0 3 0 0 0 0 3 1 0 0 0 2 1 0]

<h3>Comment:</h3>
Termination takes more steps for both policy iteration and value iteration. The reward maybe 1 or 0.
The path is random. For example, one experiment takes 11 and 13 steps for policy and value iteration to get to reward one. Another may take 25 steps and fall into the hole and get zero reward.


