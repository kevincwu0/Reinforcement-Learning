# Reinforcement Learning

When one thinks of AI, one usually don't think of supervised and unsupervised machine learning. These tasks are pretty trivial compared to what our conception of what we think AIs are doing such as beating DOTA and Go world champions, self-driving cars, beating video games.

Reinforcement Learning is all the rage because it can do all the above and more. Lots of the theories was discovered in the 70s and 80s but it hasn't been until recently that we've been able to observe first hand the amazing results possible.

AlphaGo in 2016 beat the world Champion in Go. AIs playing video games like Doom and Super Mario. Self-driving cars (uber) etc. Law of accelerating returns dictate that this progress is only going to continue to increase exponentially. Reinforcement Learning opens up a whole new world. Reinforcement Learning paradigm is more different from supervised and unsupervised learning than they are from each other. 

Reinforcement Learning has led to new and amazing insights both in behavioral psychology and neuroscience. Many analogous processes when it comes to teaching an agent and teaching an animal or human. Closest thing to a true general artificial intelligence.

What's in this repo?
- Multi-armed bandit probelm and the explore-exploit dilemma
- Ways to calculate means and moving averages and their relationship to stochastic gradient descent
- Markov Decision Processes (MDPs)
- Dynamic Programming
- Monte Carlo
- Temporal Difference (TD) Learning
- Approximation Methods (How to plug in a deep neural network or other differentiable model into RL algorithm)

Reinforcement Learning
- Huge gap between theory and what you do during programming
- Theory is super abstract so continuously important to think about how it applies to AI tasks like controlling a robot or playing a game
- We'll explore some games first:
  - Slot machines (Picks up where Bayesian ML A/B left off)
    - Bandit problem - explore-exploit dilemma
    - techniques for making trade-offs between exploration and exploitation
    - epsilon-greedy method, UCB1, Bayesian Online Machine Learning technqiues
    - A/B testing the reward is a click on advertisement or a conversion in e-commerce store
    - game can be any game, rewards can be anything (walking and high score)
    - Reinforcement Learning is all about trying to maximize some kind of goals, rewards
  - Tic-tac-toe
    - How would you code an agent to play tic-tac-toe as a first-year comp-sci student?
    - Introduce RL way of doing things
    - Only a small number of rules in tic-tac-toe to never lose
    - code an agent that will train itself to play tic-tac-toe
  - Markov Decision Process (MDP) - central framework for solving RL problems
    - MDPs allow us to formalize and abstract all the concepts we learned about in tic-tac-toe so that they can be applied to any game or scenario in the real world
    - Introduce three seperate but related techniques for solving MDPs
      - Dynamic Programming (DP)
      - Monte Carlo (MC)
      - Temporal Difference Learning (TD)
    - All three techniques look veyr similar. Hard part is differentiating these three
  - Approximation Methods
    - Teaser into Deep Reinforcement Learning
    - Disadvantage to the previous three solutions to Reinforcement Learning is that they don't scale to large state spaces, or in other words, environments where you can find yourself in a large number of different states
    - Solution is to use approximation methods => where Deep Learning comes to play
    - Neural Networks are very good function approximators
    - Without the theory, doing something like Deep Reinforcement Learning wouldn't make much sense
  - Understand the framework of reinforcement learning, how three solutions work, differences between each one, and how to use approximation methods to scale them up. Plug-in Deep Neural Networks, where we talk about Deep RL we'll pick up where we were originally. 
