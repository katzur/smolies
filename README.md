![SMOLIES](/images/banner.gif)

# **Smolies** - classic 90s pet game
## *by Katarzyna Zurawska*

### [Click here to play the game](https://smolies.herokuapp.com/)
### [Click here to view the repository](https://github.com/katzur/smolies)

# Table of Contents:
1. [Introduction](#introduction)
2. [UX](#ux)
    * [Target Audience](#target-audience)
    * [Strategy and Goals](#strategy-and-goals)
    * [Scope - Features & Future Fearures](#scope-features-&-future-features)
    * [Structure - Flow Chart](#structure)
3. [Testing](#testing)
    * [PEP8](#pep8)
    * [Manual Testing](#manual-testing)
    * [Function tests](#function-test)
4. [Bugs and Fixes](#bugs-and-fixes)
5. [Deployment](#deployment)
6. [Used technologies and credits](#used-technologies-and-credits)
    * [Used technologies](#used-technologies)
    * [Media](#media)
    * [Other technologies](#other-technologies)
    * [Content and credits](#content-and-credits)

# Introduction
*Smolies* is a fun, simple text based game created fully in Python.
It was inspired by popular in the 90s pet games called *Tamagotchi*, where player was resposible for keeping their virtual pet happy and alive.
As *Smolies* is not trying to be a copy of it, it still brings the 90s nostalgia back!

# UX
## Target Audience
* Younger users - play fun, involving pet game, learn the concept of owning a pet and need of caring for it
* CLI games enthusiasts
* Users looking for quick entertainment game
* Mature users - nostalgia for the past games created in 80s and 90s

## Strategy and goals
The main goal was to create a simple, fun game based on Command Line Interface concept (terminal). 
The game page provides consistent styling, bringing back the memory of popular in 90s *Tamagotchi*. 
Game's terminal runs without any issues, and prompts users with bolded, colored mesages in response to their inputs. 
Button on the top of the terminal is clearly visible and allows the user to start/ restart the game at any time. 
Created code is easy to navigate thanks to numerous docstrings and comments, and allows implementation of future features.

## Scope - Features & Future Features
The scope of *Smolies - pet game* is currently defined by the following features:
* Functioning terminal based pet style game, inspred by 90s *Tamagotchi*.
* Visual banners and ASCII art graphics for more pleasant user experience.
* User can choose 1 of the 5 following types of animals: cat, dog, hamster, fish, bird.
* User can create a name for their chosen pet.
* Game allows the player to take one of the 6 following actions: 
    - give food to the pet
    - play with the pet
    - get new toys for the pet
    - teach new words to the pet
    - talk with the pet
    - quit the game
* Game has an inbuild timer that runs pet's age, hunger, and happiness levels in the background of each turn.
* Player needs to keep pet happy and well fed in order to keep it alive.
* Player can decide what words should the pet learn and talk with the pet, to check if the virtual pet remembers it (randomly chosen each time out of all learned words).
* Player can get new toys for the pet. Toys are unique for each type of animal.
* User can feed the pet and lower its hunger.
* User can play with the pet and raise the level of its joy.
* Player can quit the game at any time.
* In case of pet starving or reaching old age - pet can naturally pass away - like in original Tamagotchi games.

Features that are to be considered for future releases:
* Different types of ASCII arts based on chosen type of animal - for now more generic ones are in use.
* More changing background statistics.
* Mood function based on animal level of happiness and hunger - prompting user with messages.
* Additional game functions - care for animals hygene, sleep, etc.

## Structure
The structure of *Smolies* on the visual page level has been using gif animation in the background on the right side of the page, and
the game terminal on the left side. Above the terminal there's a clearly visible button, that allows the player to start/ restart the game.
It all provides an easy and intuitive access to the game itself and good user experience thanks to minimalistic, bold design. 


On the deeper level the game structure required planning the logic of game's functions flow, in order to provide clear and easy to navigate product.
Flow chart was used to secure game's natural logic and avoid unnecessary errors.
## [CLICK TO VIEW THE FLOW CHART](/images/flowchart.png)

