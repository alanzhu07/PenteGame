# PenteGame
This is a game called Pente. Built in Java and Programmed by Alan Zhu and Luc Coté, St.Mark's School 2016-2017 Java II Class, instructed by Chistopher Roche.

Here is some info about Pente and its rules from Wikipedia:

    "Pente is a strategy board game for two or more players, created in 1977 by Gary Gabrel, a dishwasher at Hideaway Pizza, in Stillwater,  Oklahoma. Pente is based on the Japanese game ninuki-renju, a variant of renju or gomoku that is played on a Go board of 19x19 intersections with white and black stones."
    
    "Rules: The players alternate in placing stones of their color on free intersections, with White always assuming the opening move. The players aim to align five stones of the same color in vertical, horizontal or diagonal lines. Captures are obtained by flanking pairs of an opponent's stones in any same direction. Captures must consist of exactly two stones; flanking a single stone or three stones does not result in a capture. For example, if the stones are XOO- and you place your stone so it becomes XOOX, then your opponents stones are removed from the board, leaving X--X. A stone may legally be placed on any empty intersection, even if it forms a pair between two enemy stones. For example, if the stones are XO-X you may place your stone so it becomes XOOX. Your stones are NOT captured in this case. A player wins by scoring five stones in a row, or capturing five pairs of opponent stones. Pente can also be played by four people, with pairs of two acting as partners."

This program allows players to play with each other, using automatic pairing and online database (firebase by Google), or play with the computer (we call the AI "Ralph").
To start, open the program (.jar, .app or.exe), there will be a panel allowing you to choose play with Ralph (the AI) or not. 
If you choose to play with Ralph, then you can select your color (Black or White). Once you select your color, click on the grid where you want to place your stone. (If you choose black, you should click anywhere on the board to start the game) Ralph will place a stone, then you can place your stone.
If you choose not to play with Ralph, then you are choosing to play with someone online. There is a chance that you will get in a game without waiting, and you will be noticed your color, and you can start playing the game. If there is currently no one playing the game, you will be shown the panel "Waiting for Opponent", and when someone joins the game, you will start playing. Once both players are playing, they have to make a move within one minute. You will get a warning if you do not move within 30 seconds, and if you do not move within one minute, you will automatically quit, and your opponent will win.

Have fun!
