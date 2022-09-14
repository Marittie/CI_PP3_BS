# Battleship
(Developer: Mario Castaldo)

![Intro](docs/intro/intro-img.png)

[Live webpage](https://battleship-pp3-ci.herokuapp.com/)

## Table of Content

1. [Project Goals](#project-goals)
    1. [User Goals](#user-goals)
    2. [Site Owner Goals](#site-owner-goals)
2. [User Experience](#user-experience)
    1. [Target Audience](#target-audience)
    2. [User Requirements and Expectations](#user-requirements-and-expectations)
    3. [User Stories](#user-stories)
    4. [Site Owner Stories](#site-owner-stories)
3. [Technologies Used](#technologies-used)
    1. [Languages](#languages)
    2. [Frameworks & Tools](#frameworks-&-tools)
4. [Features](#features)
5. [Testing](#validation)
    1. [PEP8 validation](#pep8-validation)
    2. [Testing user stories](#testing-user-stories)
6. [Bugs](#Bugs)
7. [Deployment](#deployment)
8. [Credits](#credits)
9. [Acknowledgments](#acknowledgments)

## Project Goals
Battleship is a strategy type guessing game for two players. It is played on ruled grids on which each player's fleet of warships are marked. The locations of the fleets are concealed from the other player. Players alternate turns calling "shots" at the other player's ships, and the objective of the game is to destroy the opposing player's fleet.
[Wikipedia](https://en.wikipedia.org/wiki/Battleship_(game))

### User Goals
- Play the famous Battleship game on grids.

### Site Owner Goals
- Providing users with a logical game that is well presented grafically.

## User Experience

### Target Audience
- Children, Teenagers and Adults that share the interest of playing the Battleship game.

### User Requirements and Expectations
- Easy setup
- Easy to use

### User Stories
1. As a user, I want to be able to add my name.
2. As a user, I want to be able to place the ships on the board on the slots selected.
3. As a user, I want to be able to see my fleet on the board.
4. As a user, I want to be able to see on the board when I hit or miss the computer fleet.
5. As a user, I want to be able to see the computer choice and result.
6. As a user, I want to be able to see how many ships are remaining after every turn.
7. As a user, I want to be able to see who won the game.

### Site Owner Stories
8. As a site owner, I want the user to get feedback in case of wrong input when placing the fleet.
9. As a site owner, I want the user to get feedback in case of wrong input during the battle.
10. As a site owner, I want the user to see the board filled in with hits and miss.
11. As a site owner, I want the user to be able to play again without refreshing the page at the end of the game.

## Technologies Used

### Languages
- Python 3

### Frameworks & Tools
- gitHub
- Gitpod
- Git

### Welcome Message
- Shows a welcome message to the user

<details><summary>Welcome message</summary>
<img src="docs/features/intro-game.png">
</details>

### Enter your Name
- The User is able to enter the name that will be displaied in the game.
- User stories covered: 1

<details><summary>Enter your Name</summary>
<img src="docs/features/name-user.png">
</details>

### Place the fleet
- The user is able to place 5 ships on the board.
- User stories covered: 2

<details><summary>Place the fleet</summary>
<img src="docs/features/fleet-input.png">
</details>

### Display user's fleet
- Displays the user's fleet on the selected slots.
- User stories covered: 3

<details><summary>Display user's fleet</summary>
<img src="docs/features/user-fleet-board.png">
</details>

### User Turn
- The user selects a slot on the board trying to guess where the computer fleet is.
- Displays a message to the user as a result of the turn.
- Displays the board with an '0' for missing the ship and an 'X' for destroying one.
- User stories covered: 4, 10

<details><summary>User Turn</summary>
<img src="docs/features/hit-miss-board.png">
</details>

### Remaining ships
- Displays the remaining ships after every turn
- User stories covered: 5, 6

<details><summary>Remaining ships</summary>
<img src="docs/features/score.png">
</details>

### Computer Turn
- Displays the guess made by the computer.
- Displays a message with the result of the guess made by the computer.
- Displays the result after the computer turn.
- User stories covered: 5

<details><summary>Computer Turn</summary>
<img src="docs/features/computer-turn.png">
</details>

### Final Result
- Displays a message with the winner of the battle once one of the player has destroyed the fleet of the other player.
- User stories covered: 7

<details><summary>Final Result</summary>
<img src="docs/features/end-game.png">
</details>

### Restart game 
- Asks the user to play again or to end the game.
- User can decide to play again ot to end the game.
- Restart the game
- User stories covered: 11

<details><summary>Restart game</summary>
<img src="docs/features/play-again.png">
</details>

### User Input Validation
- Displays a message to the user for a wrong input.
- User stories covered: 8, 9

<details><summary>User Input Validation</summary>
<img src="docs/features/wrong-fleet-input.png">
<img src="docs/features/wrong-guess-input.png">
</details>

## Validation

### PEP8 validation
PEP8 online was used to check the code for PEP8 requirements.
All the code passes with no errors and no warnings to show.

<details><summary>run.py</summary>
<img src="docs/validation/pep8-validation.png">
</details>

### Testing user stories

1. As a user, I want to be able to add my name.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Enter your name | Type in your name when asked to do so | The name of the user will be displayed during the game | Works as expected |

2. As a user, I want to be able to place the ships on the board on the slots selected.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Place the fleet | Place 5 ships on the board | The user is able to place 5 ships on the board on the preferred slots | Works as expected |

3. As a user, I want to be able to see my fleet on the board.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Display user's fleet | The ships positioned on the preferred slots by the user will be displayed on the board | The user is able to see the 5 ships on the board | Works as expected |

4. As a user, I want to be able to see on the board when I hit or miss the computer fleet.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| User Turn | The user selects a slot on the board trying to guess where the computer fleet is | Displays a message to the user as a result of the turn | Works as expected |

5. As a user, I want to be able to see the computer choice and result.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Computer Turn | The computer chooses randomly a slot on the board to guess where the user fleet is | Displays the guess made by the computer, and the result | Works as expected |

6. As a user, I want to be able to see how many ships are remaining after every turn.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Remaining ships | Displays the remaining ships after every turn | Displays the remaining ships after every turn | Works as expected |

7. As a user, I want to be able to see who won the game.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Final Result | The user or the computer has destroyed the last ship from the opponent | Displays a message with the winner of the battle once one of the player has destroyed the fleet of the other player. | Works as expected |

8. As a site owner, I want the user to get feedback in case of wrong input when placing the fleet.
9. As a site owner, I want the user to get feedback in case of wrong input during the battle.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| User Input Validation | Getting an error message for an input that is not in the options of the game | Displays a message to the user for a wrong input. | Works as expected |

10. As a site owner, I want the user to see the board filled in with hits and miss.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| User Turn | The user selects a slot on the board trying to guess where the computer fleet is | Displays a message to the user as a result of the turn | Works as expected |

11. As a site owner, I want the user to be able to play again without refreshing the page at the end of the game.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Restart game | Asks the user to play again or to end the game | I will start the game again from the beginning | Works as expected |

## Bugs

When I deployed the game to Heroku the game was showing an error when the code random.sample() was running. Thanks to the help of Christine from student support I have changed the Heroku stack to Heroku 20 and created a runtime.txt file to tell the project to use Python 3.8. The error was then fixed.

## Deployment
The website was deployed using Heroku by following these steps:

1. Go to the Heroku account
2. Click the "new" button in the upper right corner and select "create new app"
3. Choose an app name and your region and click "Create app"
4. Go to the "settings" tab, add a Config Var, The key is PORT and the value is 8000
5. Go to the "settings" tab, add the python build pack and then the node.js build pack in this order
6. Go to the "deploy" tab and pick GitHub as a deployment method
7. Search for a repository to connect to
8. Click enable automatic deploys and then deploy branch
9. Wait for the app to build and then click on the "View" link

You can fork the repository by following these steps:
1. Go to the GitHub repository
2. Click on the Fork button in the upper right-hand corner

You can clone the repository by following these steps:
1. Go to the GitHub repository 
2. Locate the Code button above the list of files and click it 
3. Select if you prefer to clone using HTTPS, SSH, or Github CLI and click the copy button to copy the URL to your clipboard
4. Open Git Bash
5. Change the current working directory to the one where you want the cloned directory
6. Type git clone and paste the URL from the clipboard ($ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY)
7. Press Enter to create your local clone.

## Credits

### Code

- Student Support for the inputs and tips about the functionality of the battleship_game function on line 97.
- Stack Overflow on how to create 3 boards to display the different inputs.
- Ascii Art for the Battleship ASCII art


## Acknowledgments
I would like to thank:
- My girfriend for supporting me and being so motivating
- My friends for feedback and support
- Student Support with their tips, knowledge and kindness





