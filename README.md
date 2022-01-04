# ClockWise
![title]

### Concept
ClockWise is a school project produced during one month in a team of 10 students. The objective was to create a 2D board game.
The game is a card board game for two players that is played locally in versus, using the same keyboard.


### Rules
Players' pawn start on the first case of the clock-shaped board, where each hour interval correspond to one case. The goal is to reach the last case first (complete a full clock tour) or cause your opponent's death.

The game has a turn-based gameplay loop where each player chose his card to use to move forward his pawn or against his opponent, next they are played at the same time, where they can conteract each other. Every two rounds, the clock-shaped board hand move on one hour angle, killing everyone on its way.

Cards are drawn every time one player's deck is empty. The cards of both players are visible only at every draw, letting them remember the few cards each one has.
In order to offer a fast game, the rounds and draws are limited in time, causing the players to quickly remember the cards at draw, and quickly chosing the one they'll play.


### Programming
Made with SFML using C language through a functional programming, compiled with MSVC on Visual Studio.


## My part

It was the very first project I made in a team, like for everyone too in the team. We were 4 programmers and 6 graphic artists.
I made some parts of the game state machine like my three other programmer coworkers, but I mainly was in charge of the cards animations in 2D.
Since the animations were a sprite with a succession of its textures, I saved some memory footprint with changing scales over time for the card's animations.
- card draw : 

![card_draw]
- card flip :

![card_flip]

## Credits

Thanks to the school [Creajeux](https://www.creajeux.fr/) (Nîmes, France) where this poject was carried out with my 9 other coworkers :

#### Graphic artists
- Thomas DAO
- Clement ROMERA
- Marie SMRCKA
- Corentin Valez
- Aude VERQUIN

#### Programmers
- Michael ARNAUD
- Renald DURET (me)
- Jason ESPINASSE
- Maxence VALVASON


<!-- MEDIA FILES -------------------------------------------------------------------------------------------->
[title]: ClockWise_title.JPG
[card_draw]: ClockWise_card_draw.gif
[card_flip]: ClockWise_card_flip.gif

