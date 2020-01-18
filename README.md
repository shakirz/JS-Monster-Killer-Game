# Monster Killer Browser Game (JavaScript)

## Description

An in-browser game where the player tries to kill a monster.

## Game logic and features

* Before the game starts player is prompted to enter a starting life value. It will be applied to both the player and the monster. If no value (or invalid value) is entered, then both have a starting life value of 100.

* The player and the monster attack each other in turns. The attack value for both is ranomized. Inflicted damage is displayed by the healthbar changes. 

* Player has a choice between a regular and a strong attack.

* Player has an ability to heal.

* When player's life reaches 0, they can be saved once by a bonus life that will be used automatically.

* All turns and event values (such as inflicted damage or healing amount) are logged and can be desplayed on a button click.

* The game finishes when ether the monster's or the player's (or both - draw) healthbar reaches 0. A message with the result is then displyed.