# BackAlleyDiceGame

This is a C# back alley dice Console Game inspired by the movie Tenacious D.

To play the game, you can clone the repo, compile, and run the project in Visual Studio. 

This game is a dice-throwing game in which the player will have to bet for a number from 1 to 24. Each number represents a expected output for the dice
that the player is betting for and has a different reward depending on the chances of said occurance. 

```
**Nuber of Bet**        **Bet Type**              **Bet Amount**                                                                                    **Odds**
1                        Big                     The sum of the dice is between 11 and 17 (inclusive) with the exception of a triple               1 to 1
2                        Small                   The sum of the dice is between 4 and 10 (inclusive) with the exception of a triple                1 to 1
3                        Odd                     The sum of the dice is an ODD number with the exception of a triple                               1 to 1
4                        Even                    The sum of the dice is an EVEN number with the exception of a triple                              1 to 1
5                        All 1's                 Tripple of 1                                                                                      180 to 1
6                        All 2's                 Tripple of 2                                                                                      180 to 1
7                        All 3's                 Tripple of 3                                                                                      180 to 1                                                                                         
8                        All 4's                 Tripple of 4                                                                                      180 to 1
9                        All 5's                 Tripple of 5                                                                                      180 to 1
10                       All 6's                 Tripple of 6                                                                                      180 to 1
11                       Double 1's              Double 1's (No tripple)                                                                           10 to 1
12                       Double 2's              Double 2's (No tripple)                                                                           10 to 1
13                       Double 3's              Double 3's (No tripple)                                                                           10 to 1
14                       Double 4's              Double 4's (No tripple)                                                                           10 to 1
15                       Double 5's              Double 5's (No tripple)                                                                           10 to 1
16                       Double 6's              Double 6's (No tripple)                                                                           10 to 1
17                       Any Tripples            Any triples are rolled                                                                            30 to 1        
18                       Three Total             The sum of the dice is 4 or 17                                                                    60 to 1
19                       Three Total             The sum of the dice is 5 or 16                                                                    30 to 1
20                       Three Total             The sum of the dice is 6 or 15                                                                    18 to 1
21                       Three Total             The sum of the dice is 7 or 14                                                                    12 to 1
22                       Three Total             The sum of the dice is 8 or 13                                                                    8 to 1
23                       Three Total             The sum of the dice is 9 or 12                                                                    7 to 1
24                       Three Total             The sum of the dice is 10 or 11                                                                   6 to 1
```

**How to play**
Once you run the game in Visual Studio, you can press Y to Skip the Intro or any other key to see the intro.
The user will be promted to choose which bet they want to place and how much money they want to bet.
The initial credit of the player is 200, the game ends whenever the player looses all their money, or if the player already won over 100,000 credits. 

Enjoy!

