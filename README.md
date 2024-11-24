# Magical Arena

## Description
"Magical Arena" is a simple Java console game where two players, Player A and Player B, battle using predefined health, strength, and attack stats. Players take turns rolling dice to attack and defend, aiming to reduce their opponent's health to zero. The game ends when one player's health reaches zero.

## Getting Started
1. Download the zip file from the provided directory.
2. Extract the contents of the zip file to a folder on your computer.
3. Make sure Java is installed on your machine.
4. Open a terminal or command prompt.
5. Navigate to the folder where you extracted the zip file.

## Compile and Run the Game
1. Compile the Java file using this command:  
   bash
   javac MagicalArena.java
   
2. Run the game using this command:  
   bash
   java MagicalArena
   

## How to Play
1. When you run the game, the stats for both players (Player A and Player B) are already set:
   - *Player A*: Health = 50, Strength = 5, Attack = 10
   - *Player B*: Health = 70, Strength = 10, Attack = 5
2. The game will automatically simulate the battle between the two players.
3. The player with lower health will attack first.
4. Each turn, the attacker rolls a dice, and the damage dealt is based on:
   - The attacker’s attack value multiplied by the dice roll.
   - The defender’s strength value multiplied by their dice roll to reduce the damage.
5. Any leftover damage after the defender’s defense reduces their health.
6. Players will continue attacking in turns until one player's health reaches zero.
7. The game will announce the winner based on which player's health reaches zero first.
