---
name: 'Black jackgame'
description: 'Create Your very own blackjack game using python'
author: '@jared'
---
# blackjack

In this workshop you going to build your very own fun game of blackjack using python you can play with your friend. The game it self really seem complex to make but dont't worry this game will use as liitle as ±180 lines of code.

## Getting started
We going to be using repl.it code editor to create our game. If you don't have an account yet go over to [repl.it](https://repl.it/signup) to create an account. Then to create an new repl.it project in python just click over [here](https://repl.it/languages/python3) and rename your project to whatever you prefer.


## 1)Importing modules

Now that you have created your project let to write some code 😎. 
We will start of by calling the random library which will be used to generate our cards.
to do that on your first line write the code
```python 
   import random
```
 Now let create the class name `game` where all our code will be stored(reason).
 
## 2)Declaring our variables
Let's start by creating our ```__init__``` function with the paramaters of self and ** kwargs.
Now let's make an empty list for the dealer and player's deck and variables for the balance, bet placed, and a boolean to check if it's the end of the game in your ```__init__``` function, add the following lines:
```self.player_hand = []
   self.dealer_hand = []
```
Lets start of with a balance of 500 credits and a way to keep track of our bets
```self.balance = 500
self.bet_placed = 0
```
We also need a way to check if the game has ended, we can do this by adding a boolean variable
```self.end_game= False```
Here's our code so far:
```
class Game:
   def __init__(self, **kwargs):
      self.player_hand = []
      self.dealer_hand = [] 
      self.balance = 500
      self.bet_placed = 0
      self.end_game= False
```

## 3)Bet Placement
# Challenge 


