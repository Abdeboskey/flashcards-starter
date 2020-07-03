# Flash Cards

Flash cards is a flash-card simulation program that is played through the command line. It allows a user to see questions, make guesses, and see their final score when they have reached the end of the deck.

This was the first solo project during Mod 2 in the 2006 inning of Turing School of Software and Design's Front-End Engeneering program. It was designed to help students learn:

* How to use Test-Driven-Development (TDD) to drive implementation of their code.
* Implementation of ES6 classes and other ES6 syntax.
* How to write modular, reusable, DRY code that follows SRP.
* How to follow specs to make a working application.
* Further the understanding of Object-Oriented Programming in JavaScript.

## Application in Action
![flash cards in action gif](./assets/flashCards.gif)
## Install/Setup

* Clone down this repo from the command line with the command:

```bash
 git clone git@github.com:Abdeboskey/flashcards-starter.git 
```

* Once you have cloned the repo, change into the directory and install the library dependencies. Run:

```bash
npm install
```

#### Gameplay

* Running `node index.js` from the root of this directory should result in the start of a new round with the following message being displayed in your terminal: 

```bash
Node server running on port 3000
Welcome to FlashCards! You are playing with 30 cards.
-----------------------------------------------------------------------
```
* A question and 3 possible answers will be displayed.    

* Use the `arrow keys` or type the numbers `1`, `2` or `3` to select an answer, and then press `return` to make a guess.    

* If your guess is correct, you will see:   
 `Your answer of [answer selected] is correct!`   

* If your guess is incorrect, you will see:   
 `Your answer of [answer selected] is incorrect!`   

* When you have gone through all of the cards, you will see:   
 `** Round over! ** You have answered [percentage]% of the questions correctly!`   

* The game will automatically end, and your command line prompt will reappear.