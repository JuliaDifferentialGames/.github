# DifferentialGames: Modeling and Solving Differential Games in Julia

***

This is a new organization that is very much a work in progress for adding methods to define and solve differential games in the Julia language. The following are currently planned:

- A generalized method to define many differne ttypes of differential games including:
  - N vs. M player games,
  - Linear/nonlinear/hybrid dynamics, and
  - Various information conditions
- Implement common solvers for differential games: RRT*, viscostiy methods, level set methods, MPC, etc.
- Create plugins to use other Julia libraries that can be applied to differential games: AlphaZero.jl, ReinforcementLearning.jl, InfiniteOpt.jl, iLQGames.jl, etc.
