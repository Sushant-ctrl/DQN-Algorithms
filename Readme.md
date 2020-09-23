# DQN BASED ALGORITHMS

Reinforcement Learning is all about finding the best strategy to do a particular task. These algorithms involve estimating the goodness of the position of the agent in an environment concerning its goal.


### What is Q value?
 Q-values are defined for states and actions. is an estimation of how good is it to take the action at the state.
 

### Finding the Q values

Q values can be found using the bellman optimality equation.
 ![](https://i.imgur.com/gjNlh3U.png)
 
 #### But this repostiory isn't about using this method!!
 
 Here instead of using the conventional method of sampling from the environment and updating the Q values, we use function approximators particularly Neural Networks, thus the name Deep Q Networks.
 
 There are various variants to this algorithm I shall be implementing the following
 
 - [x] DQN with experience replay
 - [ ] Double DQN
 - [ ] Duelling DQN
 - [ ] Noisy DQN
 - [ ] Rainbow DQN
 - [ ] DQN with HER

> These algorithms are implemented on low state representation of state space.
 
 ### Repository Structure
                    
                    |Readme.md
                    |---DQN with experience replay
                    |---Double DQN
                    |---Duelling DQN
                    |---Noisy DQN
                    |---Rainbow DQN
                    |---DQN with HER
 Each subfolder is structured as 
 
                    |Readme.md
                    |---Main.py
                    |---Solver.py
                    |---UTILS.py
                    |---Running Trained Model.py
                    |---Trained Model.pt
 
 