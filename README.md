# Policy-Gradient-Cartpole-Reinforce
Policy Gradient Cartpole Reinforce Implementation

## Policy Gradient Methods -
 To find optimal policy , we have looked at the action value function q , and asked the question - for every state which action is giving 
 us the maximum q value.

 Now , we look at methods which learn an optimal policy without considering the value function.

 The policy is by the defined as the probability of picking an action 'a' given that we are at state 's'.
 This is denoted by- PI(a|s)

 The policy parametrization is carried out by applying the softmax function over the priority/preference order assigned to each action.

## Policy Gradient Theorem
Policy gradient theorem provides as analytical expression for calculating gradient of the performance measure with respect to
the policy parameter.

It is a remarkable result which states that the gradient of the performance measure with respect to the policy parameters does 
not involve the gradient of the state distribution with respect to the policy parameters, even though the state distribution 
depends on the policy parameter.
