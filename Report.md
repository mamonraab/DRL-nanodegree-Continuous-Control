

The project done by using policy-based methods to learn the optimal policy 
The observation space consists of 33 variables
the action vector is a number between -1 and 1.

-	Policy-based methods have( critic)  high variance
-	value-based methods(actor)  have  low variance
combine both actor and critic  to get a Actor-critic methods  where Actor represented as a neural network that update the policy by choice best action to maxmamize the reward  and the critic another network that evaluate the policy being learned  that been used to train the actor

Hyperparameters

There were many hyperparameters involved in the experiment. The value of each of them is given below:
Hyperparameter 	Value
Replay buffer size 	1e6
Batch size 	800
Actor Learning rate 	1e-4
Critic Learning rate 	3e-4
Max  timesteps per episode 	1500
$\gamma$ (discount factor) 	0.99
$\tau$ 	1e-3



idea for improvment



The Q-prop algorithm, which combines both off-policy and on-policy learning, could be good one to try.
