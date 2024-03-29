# Determine The Winner

Arpa and Dishant are playing a game with a pile of N cards. Both the players taketheir turns alternately starting from Arpa. In each turn, a player can remove at least 1 and at most K cards from the pile. If a player cannot make the next move, then the player loses the game. If both the players play optimally, your task is to determine the winner. You need to determine the winners for T independent games.

Input format

First line: T denoting the number of test cases 
First and only line of each test case: A single line containing two space-separated integers N and K.

Output format

For each test case, considering that both the players play optimally, print "Arpa" (without quotes) if he wins the game else print "Dishant" (without quotes) in a new line.


SAMPLE INPUT

2

5 2

2 1

SAMPLE OUTPUT 

Arpa

Dishant

Explanation
For the first test case, Arpa chooses 2 cards. Now there are 3 cards left in the pile. It does not matter how many cards Dishant chooses from the pile, he'll always lose. 

For the second test case, both the players need to choose exactly 1 card from the pile. Hence, Dishant wins this game!
