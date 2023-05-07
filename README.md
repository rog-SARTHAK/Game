# Snake Game AI

Subject: Train an AI to play Snake Game with Reinforcement Learning, Deep Q Learning, Pytorch

Dependencies:

Pip install pygame
Pip install matplotlib
Pip install IPython
Pycharm IDE

Reinforcement Learning
Reinforcement Learning is an area of machine learning concerned with how software agents ought to take actions in an environment in order to maximize the notion of cumulative reward.

Reward:
Eat food: +10
Game over: -10
Else: 0

Action:
[1, 0, 0] -> straight
[0, 1, 0] -> right turn
[0, 0, 1] -> left turn

State – 11 values:
[danger straight, danger right, danger left,

Direction left, direction right, direction up, direction down,

Food left, food right, food up, food down]

We will use a feed forward neural network with an input layer, a hidden layer and an output layer.
As Input we get states with 11 values, 2nd is hidden layer, 3rd is of 3 layers eg max [1, 0, 0]

Goal: To increase the Q value or Quality of action (Deep Q Learning)

We will use Bellman Equation to update the Q value

Instructions to run:

1)	Import the folder Snake_Game_AI from Github repo link and open all files with Pycharm IDE
2)	In your IDE Terminal, install the given libraries
3)	Command “python agent.py” in IDE Terminal to run the game
