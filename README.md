# Snake

[View The Game Here](https://sophiedeakin.github.io/Snake/)

![Image of Snake Game](https://github.com/sophiedeakin/Snake/blob/main/assets/Read%20Me%20assets/Snake%20Game.png)

# Introduction 

The Snake game is a web-based game inspired by the popular classic game called "Snake", where players move the snake's head around the board to eat the fruit, and the snake's body progressively gets longer. Every fruit that is eaten counts towards their score. Snake regained popularity in 1997 when Taneli Armanto programmed the game to be published by Nokia for their monochrome phones. It was first introduced on the Nokia 6110. 

The website comprises a single page which includes the logo, the game board with the user's current score and high scores, and the button controls for mobile and tablet users. 

## Target Audience 

The game was built to target individuals who love classic arcade-style games, and gamers who enjoy playing games on either PC, tablet, or mobile. 

## Business Goals 

The business goals of the game are: 

1. Provide users with nostalgia from when they were young playing this game or similar games.
2. Provide endless entertainment to users who love classic games and enjoy creating high scores and trying to beat them.
3. Making the game playable across different devices from Android, iOS, and PC.
4. Create a community among the players.

## User Goals 

The user goals of the game are: 

1. As a first-time visitor, I want the game to be playable without experiencing any bugs or errors.
2. As a first-time visitor, I want the game to be entertaining and allow me to create a high score to try and beat.
3. As a first-time visitor, I want to be able to play the game on various devices.
4. As a first-time visitor, I want the game to be easy to understand and have a simple layout.

---

# UX

## Strategy 

When thinking of the strategy of the game I considered who are the target audience and what features the users would be looking for. For the target audience, I did some research on arcade-style games and what kind of players are attracted to playing them, during my research I found easy-to-play games are more appealing to casual gamers. Casual gamers are players who play games to pass the time, be entertained, and may not care about the genre of the game. The most important research I found that shaped the way I am designing the game is smartphones are popularly used to play casual games and 18-35-year-olds with an even gender split of 50% Males and 50% Females play causal games on their phones, it's because they are relatively easy to pick up and addicting. Finally, for the features users would be looking for I found information on how to design an arcade game to make it appealing to the target audience, for example, it should have beautiful art, a simple layout, nice colours, and fonts that are easy to read.

After conducting the research I have created a list of areas to focus on to reach the target audience and add features that users are looking for. 

Here's the list of the main features I want to focus on: 

1. Responsiveness: After learning smartphones are widely used to play casual games, my primary focus is making sure when coding the game it responds to different mobile phone sizes. To help me with this area I will be using Device Mode in Google Developer Tools, this feature simulates various mobile devices and allows you to see how your page looks and performs.
2. Button controls: This feature is next on my importance list because without it mobile and tablet users won't be able to play the game. For the first step I will be creating the buttons, I have chosen to use Canva as I have used this online graphic tool before. After designing the buttons I will add them to the game and make sure they are working correctly, additionally, I will make sure the buttons are also responsive to the mobile and tablet sizes.
3. Current score and high score: The next feature I will focus on is the current score and high score, this is important because it keeps players engaged and entertained. For the current score, I will be adding code to that every time the snake's head (yellow block) hits the fruit (red block) it adds 1 to the score. Finally, for the high score, I will be adding code that every time the snake's head collides with its body or the wall the game will stop and the total score from that gameplay will be shown next to the score.

## Scope 

To accomplish the business goals and the user goals the features I will be adding in this release are the following:

1. Logo: At the top of the page will be the logo that has a simple design and will be memorable.
2. Score and high score: Located at the top of the game board which shows users their current score and high score.
3. Arrow buttons: Located under the game board which allows users to play on different mobile and tablet devices.
4. Game board: The main gameplay area will have the snake, fruit, and collision detection.

### Future planned releases

For the first update, I am planning to add the following features: 

1. Sign Up/Login: This feature will allow users to create an account to keep track of their high scores and stats, this feature will be available on PC, tablet and mobile.
2. Settings tab and themes: For this feature, I will be creating a Setting tab that will have different theme options allowing users to pick what kind of theme they want their game to look like.
     - Background colour or images
     - Font colour
     - Game board colour
3. Hard Level: For this feature, I will be building another snake game but make it harder by adding obstacles. This feature will keep users playing the game and add a challenge, the aim of this hard level is similar to the classic snake game but there are obstacles placed around the board and if the snake's head hits the obstacle it's game over.

For the second update, I am planning to add the following features:

1. Leaderboard: For this feature, I will be creating a leaderboard where players across the world can compete to be at the top of the leaderboard.
2. More games: Create more classic games like Tic-Tac-Toe, Tetris, etc. These games will added to create a free games website which will bring more users and keep current users.

For the third update, I am planning to add the following feature:

The third update will consist of turning the free games website into an app and making it available to all users on PC, Mobile and Tablet via Google Play, Apple App Store and Microsoft Store. 

## Structure 

During the structure planning I will be referring back to the [User Goals](#user-goals) in order to meet their expectations with the game. 

Looking at the third user goal ("As a first-time visitor, I want to be able to play the game on various devices") it's important the game is not overloaded with features as it will make it look messy and overwhelming when users are playing, especially on mobile devices as the screen sizes are smaller than tablet and PC. To tackle this I will be limiting the amount of content there is, the page will have 4 main sections the logo, game board, arrow buttons and the information popup. 
