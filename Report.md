

The project done by using policy-based methods to learn the optimal policy 
The observation space consists of 33 variables
the action vector is a number between -1 and 1.

-	Policy-based methods have( critic)  high variance
-	value-based methods(actor)  have  low variance
combine both actor and critic  to get a Actor-critic methods  where Actor represented as a neural network that update the policy by choice best action to maxmamize the reward  and the critic another network that evaluate the policy being learned  that been used to train the actor

