# RL-to-play-TicTacToe
Build an RL agent (using Q-learning) that learns to play Numerical Tic-Tac-Toe with odd numbers. The environment is playing randomly with the agent, i.e. its strategy is to put an even number randomly in an empty cell

The following is the layout of the notebook and the Goals:

* Define the Tic Tac Toe environment in a Python file
* Defining epsilon-greedy strategy
* Tracking state-action pairs for convergence
* Define hyperparameters for the Q-learning algorithm
* Generating episode and applying Q-update equation
* Checking convergence in Q-values

This is one of the most popular and enduring games of all time called **Tic-Tac-Toe**. Because of its familiarity, this game is often used as a starting example to mathematically analyze a decision-making process. Its brevity makes it a perfect game to illustrate the rewards of thinking ahead and learning the consequence of each decision.

Rules of the Game:

- The game will be played on a 3x3 grid (9 cells) using numbers from 1 to 9. Each number can be used exactly once in the entire grid.
- There are two players: one is the Reinforcement Learning (RL) agent and other is the environment.
- The RL agent is given odd numbers {1, 3, 5, 7, 9} and the environment is given the even numbers {2, 4, 6, 8}
- Each of them takes a turn. The player with odd numbers always goes first.
- At each round, a player puts one unused number on a blank spot.
- The objective is to make 15 points in a row, column or a diagonal. The player can use the opponent's numbers in the grid to make 15.
- The game terminates when any one of the players makes 15.
