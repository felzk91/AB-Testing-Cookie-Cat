# AB-Testing-Cookie-Cat

## Introduction
Cookie Cat is a mobile puzzle game developed by Tactile Entertainment. To enhance player engagement and drive in-app purchases, Cookie cats introduces gates at certain levels. The gates require players to either wait or pay to progress in the game. The main intention is to allow the players to have a break, which may enhance their overall enjoyment and extend their playtime.

For this project, an A/B test is conducted where the placement of the first gate is shifted from level 30 to level 40. The study focus on evaluating the impact of this change on player retention and the total number of game rounds played by the players.

## Dataset
The data consists of over 90,000 observations with the following variables:
userid - unique identifier of each player
version - the version of the game the player is playing (gate at 30 levels or 40 levels)
sum_gamerounds - The number of game rounds played by the player during the first 14 days.
retention_1 - binary. 1 = player returns 1 day after installing. 0 = player did not return 1 day after installing.
retention 7 - binary. 1 = player returns 7 days after installing. 0 = players did not return 7 days after installing.
