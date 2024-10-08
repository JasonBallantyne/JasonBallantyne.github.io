---
layout: post
title: Java Games System
subtitle: Three games written in Java, complete with points and a leaderboard
cover-img: /assets/img/Game3.jpg
thumbnail-img: /assets/img/java.png
gh-repo: JasonBallantyne/SimpleGamesSystem
gh-badge: [star, fork, follow]
tags: [java, object-oriented-programming]
---


This project implements three simple games: a *lottery game*, a *coin flip game* and a game of *rock-paper-scissors*. The program allocates points to a victorious player and stores these points on a leaderboard. 

{: .box-note}
**Github Link:** Full repository can be found [here](https://github.com/JasonBallantyne/SimpleGamesSystem)

The program is ran using “App.java” and allows the user to select between being 1. New Player 2. New VIP Player or 3. Quit. The program then prompts the new player to enter his/her name before allowing the player to choose to play one of the games we alluded to earlier.

As the players are created, their names and points are stored in a text file that is created as “leaderboard.txt” and displayed upon exit of the application.
Users are encouraged to have multiple interactions with the games as the number of times users can play the games are infinite.

After the game has been completed, the player has an option to select another game or enter -1 to return to the main menu. 
When the player quits from the main menu, the program displays all the players who have played and their points on a leaderboard, sorted by their point total. 
If a play has chosen to be VIP Player, they will receive special bonuses. These bonuses include the inclusion of “(VIP)” to the player’s name on the leaderboard and the addition of 2 bonus rounds for each of the games.
