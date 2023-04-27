# Rock-Paper-Scissors

Hyperskill Java Backend Developer project

![Alt text](readme.jpeg?raw=true "rock-paper-scissors")

The game would first ask user name, and then the list of options for the game (options are separated by comma). If users input an empty line, the game starts with default options: rock, paper, and scissors.

The game would first read from the rating list and set the initial score for the user.

For each draw, add 50 points to the score. For each user's win, add 100 to the score. In case of a loss, don't change the score;

The first half of the options following the chosen options would beat the chosen option, while the second half would be defeated, considering the options list as a cycle.

Other commands:

- `!exit`: stop the game
- `!rating`: display user's current rating
