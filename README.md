# Game-of-Stones


Two players called P1 and P2 are playing a game with a starting number of stones. Player 1 always plays first, and the two players move in alternating turns. The game's rules are as follows:

In a single move, a player can remove either 2, 3, or 5 stones from the game board.
If a player is unable to make a move, that player loses the game.
Given the starting number of stones, find and print the name of the winner. P1 is named First and P2 is named Second. Each player plays optimally, meaning they will not make a move that causes them to lose the game if a winning move exists.

For example, if n =4, P1  can make the following moves:

P1 removes 2 stones leaving 2. P2 will then remove 2 stones and win.
P1 removes 3 stones leaving 1. P2 cannot move and loses.
P1 would make the second play and win the game.

Function Description

Complete the gameOfStones function in the editor below. It should return a string, either First or Second.

gameOfStones has the following parameter(s):

n: an integer that represents the starting number of stones
Input Format

The first line contains an integer t , the number of test cases.
Each of the next t lines contains an integer , n the number of stones in a test case.


Output Format

On a new line for each test case, print First if the first player is the winner. Otherwise print Second.

Sample Input

8
1
2
3
4
5
6
7
10

Sample Output

Second
First
First
First
First
First
Second
First
