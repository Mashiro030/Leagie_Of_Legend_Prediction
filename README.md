# Leagie_Of_Legend_Prediction

## Context
League of Legends is a MOBA (multiplayer online battle arena) where 2 teams (blue and red) face off. There are 3 lanes, a jungle, and 5 roles. The goal is to take down the enemy Nexus to win the game.

## Context
League of Legends is a MOBA (multiplayer online battle arena) where 2 teams (blue and red) face off. There are 3 lanes, a jungle, and 5 roles. The goal is to take down the enemy Nexus to win the game.

## Content
This dataset contains the first 10min. stats of approx. 10k ranked games (SOLO QUEUE) from a high ELO (DIAMOND I to MASTER). Players have roughly the same level.<br>

Each game is unique. The gameId can help you to fetch more attributes from the Riot API.<br>

There are 19 features per team (38 in total) collected after 10min in-game. This includes kills, deaths, gold, experience, level… It's up to you to do some feature engineering to get more insights.<br>

The column blueWins is the target value (the value we are trying to predict). A value of 1 means the blue team has won. 0 otherwise.<br>

So far I know, there is no missing value.<br>

## Glossary
Warding totem: An item that a player can put on the map to reveal the nearby area. Very useful for map/objectives control.<br>
Minions: NPC that belong to both teams. They give gold when killed by players.<br>
Jungle minions: NPC that belong to NO TEAM. They give gold and buffs when killed by players.<br>
Elite monsters: Monsters with high hp/damage that give a massive bonus (gold/XP/stats) when killed by a team.<br>
Dragons: Elite monster which gives team bonus when killed. The 4th dragon killed by a team gives a massive stats bonus. The 5th dragon (Elder Dragon) offers a huge advantage to the team.<br>
Herald: Elite monster which gives stats bonus when killed by the player. It helps to push a lane and destroys structures.<br>
Towers: Structures you have to destroy to reach the enemy Nexus. They give gold.<br>
Level: Champion level. Start at 1. Max is 18.<br>

source:https://www.kaggle.com/datasets/bobbyscience/league-of-legends-diamond-ranked-games-10-min<br>
結果分別參照html檔
