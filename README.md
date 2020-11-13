# Play-Connect-Four-vs-AI
Connect four of your checkers in a row while preventing your opponent from doing the same. But, look out -- your opponent can sneak up on you and win the game!

Connect Four (also known as Four Up, Plot Four, Find Four, Four in a Row, Four in a Line, Drop Four, and Gravitrips in the Soviet Union) is a two-player connection board game, in which the players choose a color and then take turns dropping colored discs into a seven-column, six-row vertically suspended grid. The pieces fall straight down, occupying the lowest available space within the column. The objective of the game is to be the first to form a horizontal, vertical, or diagonal line of four of one's own discs.

![alt text](https://github.com/Kalpit-Vadnerkar/Play-Connect-Four-vs-AI/blob/main/pasted%20image%200%20(1).png?raw=true)

To play Connect Four on your machine, download the project and type in the command line:

# python connect4.py

A GUI similar to the image above will be generated. Using the options provided, you can play the game with you friend. For us loners there are three different kinds of AI agents to play against. These agents use one of the 3 algorithms namely, MiniMax, MiniMax with alpha-beta pruning, and ExpectiMax. To make things more interesting, you can have both the players to be AI agents and see who wins. If you think you can beat the AI agent, you can try to play against stronger agents by increasing the depth (dificulty).
Have fun!


When an agent needs to make its next move, it runs an adversarial search as a MAX player and its opponent is considered to be a MIN (or a CHANCE) player depending on the search algorithm that you run. A random player simply makes a random valid move. The minimax algorithm always considers that the adversary tries to minimize the score of the MAX player that initiated the game search. The adversary never considers its own score at all during this process. Therefore, when evaluating the utilities of the nodes at the maximum tree depth, the evaluation should always be made from MAX's point of view.
