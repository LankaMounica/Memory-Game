# Memory Game Project

To run this project, try running index.html project in updated and latest browsers with working internet connection for downloading required libraries.

## Table of Contents

-   [Instructions](#instructions)
-   [How to run the game](#howtorunthegame)
-   [How I constructed the Game](#howiconstructedthegame)
-   [ How does it Work](#howdoesitworks)
-   [Contribution](#contribution)

## Instructions

The starter project has some HTML and CSS styling to display a static version of the Memory Game project. You'll need to convert this project from a static project to an interactive one. This will require modifying the HTML and CSS files, but primarily the JavaScript file.

To get started, open `js/app.js` and start building out the app's functionality

For specific, detailed instructions, look at the project instructions in the [Udacity Classroom](https://classroom.udacity.com/me).

## How to run the game!

You can download the starter code through either:

-   Memory Game project repository on GitHUB: <https://github.com/udacity/fend-project-memory-game>
-   The Zipped File : <https://github.com/udacity/fend-project-memory-game/archive/master.zip>

## How I constructed the  Game!

The Memory Game Project is all about demonstrating your mastery of HTML, CSS, and JavaScript. This is constructed in responsive designing too. Steps followed to construct the game are as follows:

-   create an index.html file
-   img folder to store images
-   js folder to construct the functionality of the game
-   css folder to allocate the respective styles required

The game was constructed by performing the DOM manipulations

-   A deck of cards were created and shuffle when the game was refreshed
-   A timer and counter were created to know about the duration of the    game played and count the moves performed by the player
-   added some functions to cards when they got match and unmatched
-   created a pop-up modal box when player wins the game

## How does it Work!

If you're new to the game, the task to be performed is very simple; flip over two cards at a time to locate the ones that match!
The deck contains of sixteen cards arranged randomly in a grid. The deck is made up of eight different pairs of cards, each with different symbols on one side. Each turn:

-   A player flips one card over to reveal its underlying symbol
-   The player then turns over another card, trying to find the corresponding card with the same symbol
-   If the cards match, both cards stay flipped over
-   If the cards do not match, both cards are returned to their initial hidden state
-   The game ends once all cards have been correctly matched.

## Contribution

This repository is the starter code for _all_ Udacity students. Therefore, we most likely will not accept pull requests.

For details, check out [CONTRIBUTING.md](CONTRIBUTING.md).
