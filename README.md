# Reflection on cooKING Game Design
### Xiang Ni

## Motivation
When designing **cooKING**, I created this casual cooking game because of both my enthusiasm for pixel art aesthetics and my interest in exploring Vue's data management and component structures. In the game, the player would have to successfully cook 9 required dishes with the provided ingredients to become the cooKING.

## Game Logic and Mechanics
The game logic itself is simple, yet encourages exploration. Each of the ten ingredients has a unique ID that clearly distinguishes between required and optional ingredients for each dish. To successfully create a particular dish, players must include all required ingredients and cannot add any ingredients other than those listed as either required or optional. Throughout the game, players were able to experiment by combining ingredients and discovering recipes through a relaxed "try and see" approach.

## Component Structure
Since the game consists of a start screen and a main gameplay screen, I structured the start screen as a separate component and controlled the appearance of the main gameplay by emitting a custom `"game-start"` event. Upon completing all nine dishes, players are rewarded with a celebratory pop-up.
