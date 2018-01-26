# Ultimate Tic-Tac-Toe AI
An Artificial Intelligence Bot that plays Ultimate Tic-Tac-Toe game on www.theaigames.com competition.

Description
===
Alpha–beta pruning is a search algorithm that seeks to decrease the number of nodes that are evaluated by the minimax algorithm in its search tree. You can visit https://en.wikipedia.org/wiki/Alpha%E2%80%93beta_pruning for more details about the algorithm. 

Improvements
===
First, calculate the number of nodes that can be evaluated in a small amount of time which is insignificant, like 10 ms. After that, we can estimate the number of nodes that we can calculate in the remaining time and consider this number when simulating the game. This is very important because the game have a limited amount of response time and the bot should come with a valid move before the time is up.
We will check if we are under preasure and instead doing alpha-beta we will select a greedy move for the next move.

Performance
===
With the improvements above we will have a variable depth which will help us come with the best solution in the remaining time. This is a school project and we reached the 5th place out of 146 teams.

Download
===
You can download the archive as zip and upload it on the website.
