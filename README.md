# Card-Game-Object-Oriented-Programming
### Fun with OOP & Python

## This repository contains a jupyter notebook that builds out a classic card game of war using python and object oriented programming. 

## Game Play Overview:

The game begins with a 52 card deck, shuffled and divided between two players. Without viewing cards, the players battle one card at a time - highest card wins.

* The winner keeps the cards

A tie results in a 'war'

* The players battle with an additional single card
* Winner keeps all the cards

The first player to run out of cards loses the game. A copy of the rules can be found at the following linked [Wikipedia page.](https://en.wikipedia.org/wiki/War_(card_game)) 

## Classes

**Four classes were created; Card, Deck, Player, Game Logic**

### Card Class

Creating:

* Suit ('Hearts','Diamonds','Spades','Clubs')
* Rank ('Two' - 'Ace')
* Value (Numeric value per card)

### Deck Class

Creating:

* 52 card objects
* shuffle function
* 'dealing' function (draw/remove)

### Player Class

Creating:

* Two players
* Top card use (per player)
* Adding cards to deck (for winner/round)

### Game Logic Class

Creating:

* Player ability to win
* Result of round
* Game play for war scenario
* Ending Game

**In our final simulation, player one won after 57 rounds.** Our jupyter notebook is listed in the repository as [OOP_WarCardGame.](./OOP_WarCardGame.ipynb)

## Source Cited

**The main OOP code and layout is available in Udemy Course '2021 Complete Python Bootcamp From Zero to Hero in Python' by Jose Portilla**