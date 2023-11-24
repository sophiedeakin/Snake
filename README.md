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

Looking at the third user goal ("As a first-time visitor, I want to be able to play the game on various devices") it's important the game is not overloaded with features as it will make it look messy and users will feel overwhelmed, especially on mobile devices as the screen sizes are smaller than tablet and PC. To tackle this I will be limiting the amount of content there is, the page will have four main sections the logo, game board, arrow buttons and the information popup. Additionally, looking at the fourth user goal ("As a first-time visitor, I want the game to be easy to understand and have a simple layout.") I will be making sure the placement of all the features is consistent when playing the game on different devices, this will be done by keeping the same layout, colours/theme and font. In addition, to make the game easy to understand for users I will be creating a pop-up which pops onto the user's screen when the page loads, the pop-up will include instructions on how to play the game.

## Skeleton 

### Wireframes 

![Snake Wireframes](https://github.com/sophiedeakin/Snake/blob/main/Wireframes/Snake%20Wireframes.png)

The wireframes shown above are my original idea of how I wanted the game to look, the only change I made was the addition of the popup feature which welcomes the users and tells them how to play the game. 

### Prototype 

![Snake Prototype](https://github.com/sophiedeakin/Snake/blob/main/Wireframes/Snake%20Prototype.png)

The prototype above shows what the game would look like with the colours/themes and font I have chosen. The prototype has a simple layout which meets the user goals and I will be sticking to this layout when building the game. 

## Surface

### Colours

When choosing the colours for the game I didn't want to choose colours that were too bright, especially with the game board since the snake is Yellow and the fruit is Red. I have added an image below of what the colour looks like. 

The colours I have chosen are: 

- #E2E2E2 - Platinum
- #B8B8B9 - Silver
- #B8C6DC - Powder Blue
- #242C3D - Gunmetal
- #191F29 - Raisin Black

![Snake Colour Palette](https://github.com/sophiedeakin/Snake/blob/main/assets/Read%20Me%20assets/Snake%20colour%20palette.png)

### Typography

To accomplish the user goals by making the game easy to understand I made sure to choose a font that is easy to read and is consistent throughout the game, the font I chose was "Lato" from the Google Fonts website. The image below shows what the font looks like. 

![Snake Typography](https://github.com/sophiedeakin/Snake/blob/main/assets/Read%20Me%20assets/Snake%20Typography.png)

---

## Features

### Snake Logo 
![Snake Logo](https://github.com/sophiedeakin/Snake/blob/main/assets/snake%20logo.png)
The Snake logo is positioned at the top-middle of the game and was designed using Canva. Using the resources provided by Canva I was able to design the logo by using a snake cartoon image and a text box with the name of the game, I made sure to choose the same font ("Lato") as the rest of the game so that it's consistent and easy to read. I also chose the text colour to be Black to make it easier to read since the background colour of the game is Silver. Finally, I used background remover which made the background of the logo transparent this saved me time from trying to make sure the background colour matched perfectly.

### Popup 
![Snake Game Popup](https://github.com/sophiedeakin/Snake/blob/main/assets/Read%20Me%20assets/Popup%20feature.png)
The pop-up was made using HTML, CSS and JavaScript. The pop-up pops up when the game loads, the pop-up consists of the snake logo at the top, text welcoming the users and providing them with instructions on how to play the game, and at the bottom is a button which says "Play" when users click on the button the pop-up closes and they are able to play the game. When building the pop-up I used the same font and used Black as the font colour to match. 

### Game Board 
![Snake Game Board](https://github.com/sophiedeakin/Snake/blob/main/assets/Read%20Me%20assets/Game%20board%20feature.png)
The gameboard contains the scoring system and the main gameplay area which allows users to see the snake head move and the fruit which they need to collect. Starting from the top of the game board I used a different background colour (#191F29) compared to the rest of the board because I wanted it to stand out since it contains the score and high score, for the scoring system I used the same "Lato" font and used a brighter font (#B8C6DC) so users can easily see their scores. Next is the main gameplay area which has a lighter background colour (#242C3D) and is a different colour from the snake and fruit.

### Arrow Buttons 
![Snake Arrow Buttons](https://github.com/sophiedeakin/Snake/blob/main/assets/Read%20Me%20assets/Arrow%20buttons%20feature.png)
The arrow buttons are positioned at the bottom of the game under the game board, this allows mobile phone and tablet users to press the buttons to move the snake and see the gameplay. I also used Canva to create the buttons instead of using Font Awesome because I wanted the buttons to have a retro style and Canva provided those resources for me. The arrows are made up of triangles with arrows inside of them which allow users to understand which button to press in order to move the snake's head in that direction. Finally, I used background remover which makes the background of the arrow buttons transparent this saved me time from trying to make sure the background colour matched perfectly.

---

## Technologies Used 

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
  * Used for the basic building block for the project and to structure the content.

- [CSS](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)
  * Used for styling all the web content across the project.

- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
  * Used for giving elements inside web page interactiveness which engages the user.

- [Google Fonts](https://fonts.google.com/)
  * Used for obtaining the font used through the project, the font used was Lato.

- [Google Developer Tools](https://developer.chrome.com/docs/devtools/)
  * Used for identifying any bugs and responsiveness.

- [GitHub](https://github.com/)
  * Used for storing code for the project after being pushed.

- [Git](https://git-scm.com/)
  * Used for version control by utilising the VS Code terminal to commit to Git and Push to GitHub.

- [Visual Studio Code](https://code.visualstudio.com/)
  * Free Open Source software used to code the project.

- [Figma](https://www.figma.com/)
  * Used for creating the wireframes for the project.

- [Framer](https://www.framer.com/)
  * Used for creating the prototypes for the project.

- [Grammarly](https://www.grammarly.com/)
  * Used for checking grammar and spelling mistakes throughout the project.

- [Coloors](https://coolors.co/)
  * Used for creating the colour palette for the project.

- [Canva](https://www.canva.com/)
  * Used for designing and editing the logo and the arrow buttons for the project.

- [Background Remover](https://www.remove.bg/)
  * Used for removing the background around the logo and arrow buttons making them transparent.

- [Keycodes](https://www.toptal.com/developers/keycode)
  * Used for finding the key codes for keys on a keyboard.

--- 

## Testing 

### User Stories 

1. As a first-time visitor, I want the game to be playable without experiencing any bugs or errors.

When entering the game the user will immediately see the pop-up and when clicking play they can start playing the game, this is because when building the game I consistently used Google Developer Tools to check if the game was responsive to the different screen sizes and also checking for any bugs or errors along the way. 

![User Story 1](https://github.com/sophiedeakin/Snake/blob/main/assets/Read%20Me%20assets/User%20goals%201.png)

2. As a first-time visitor, I want the game to be entertaining and allow me to create a high score to try and beat.

When entering the game you can see at the top of the game board there is a scoring system that shows your current score and your high score, as you play the game your score (on the left) will go up every time the snake eats the red fruit but when the snake either hits it own body or collides with the wall it's game over and the score for that round will be shown as your high score (on the right). The high score will only change when you successfully get a higher score than your previous game. 

![User Story 2](https://github.com/sophiedeakin/Snake/blob/main/assets/Read%20Me%20assets/User%20goals%202.png)

3. As a first-time visitor, I want to be able to play the game on various devices.

When entering the game on mobile, tablet or PC the game responds to the size of the device making the game playable, you are still able to see your score and high score, use the arrow buttons, logo and most importantly the gameplay. 

![User Story 3](https://github.com/sophiedeakin/Snake/blob/main/assets/Read%20Me%20assets/User%20goals%203.png)

4. As a first-time visitor, I want the game to be easy to understand and have a simple layout.

When entering the game it has a simple layout with a limited number of features making the game not feel overwhelming. Additionally, when first loading into the game there is a pop-up that welcomes you and provides you with instructions on how to play the game. 

![User Story 4](https://github.com/sophiedeakin/Snake/blob/main/assets/Read%20Me%20assets/User%20goals%204.png)

### Lighthouse

Lighthouse is a feature in Google Developer Tools which is used for improving the quality of web pages. It has audits for performance, accessibility, progressive web pages, SEO, and more. When first running Lighthouse I achieved a low score for accessibility and SEO, reference the image below:

![Lighthouse Result](https://github.com/sophiedeakin/Snake/blob/main/assets/Read%20Me%20assets/Snake%20Lighthouse%201.png)

When looking at the recommendations to improve the accessibility of the game it recommends adding the "[alt]" for the Snake logo, this is something I forgot to add when coding the project. Additionally, it recommends adding a meta description to the HTML file to improve the SEO. After completing the recommendations and running Lighthouse again you can see those changes made have been effective and have improved my accessibility and SEO score a lot. Reference image below:

![Lighthouse Results After Recommendations](https://github.com/sophiedeakin/Snake/blob/main/assets/Read%20Me%20assets/Lighthouse%20Results%20after.png)

### Google Developer Tools

Google Developer Tools is a set of web developer tools built directly into Google Chrome, this tool helps you edit pages and diagnose problems quickly which makes your website looker better and build them faster.

When testing the game I consistently used Google Developer Tools which allowed me to identify any bugs and test the responsiveness when viewing the game on different devices. 

![Google Developer Tools](https://github.com/sophiedeakin/Snake/blob/main/assets/Read%20Me%20assets/User%20goals%203.png)

Referencing back to the [Strategy](#strategy) of the game I made a list of features/areas I wanted to focus on. The primary focus on that list was responsiveness and Google Developer Tools allows me to do this by providing simulated devices which allow you to see what your website would look like when viewing on either Mobile, Tablet or PC. The devices I used were:

- Galaxy S9+
- Galaxy Tab S4
- iPhone SE
- iPhone XR
- iPhone 12 Pro
- iPhone 14 Pro Max
- Pixel 7
- Samsung Galaxy S8+
- Samsung Galaxy S20 Ultra
- iPad Mini
- iPad Air
- iPad Pro
- Surface Pro 7
- Surface Duo
- Galaxy Fold
- Samsung Galaxy A51/71
- Nest Hub
- Nest Hub Max
- iPhone 4
- iPhone 5/SE
- iPhone 6/7/8
- iPhone 6/7/8 Plus
- iPhone X
- iPad

### Known Bugs and Fixes 

When testing the game I wanted to make sure any interactive features were working properly and overall the game was playable. When testing out the game in Google Developer Tools I noticed when using the arrow keys to move the snake head it was causing the scroll bar to move as well. I flagged this bug as important to fix because if were to push this game out it would cause users to get frustrated and leave. The image below shows the bug:

![Scroll Bar Bug](https://github.com/sophiedeakin/Snake/blob/main/assets/Read%20Me%20assets/Scroll%20Bar%20Bug.png)

After doing some research on this bug I found a [website](https://www.w3schools.com/howto/howto_css_hide_scrollbars.asp) which gave me the CSS code to hide the scrollbar "overflow-y: hidden;", this code will also prevent the page from moving when the arrow keys are pressed. The image below shows the bug has been fixed and when interacting with the game by pressing the arrow keys the page no longer moves and the scrollbar is hidden.  

![Scroll Bar Bug Fixed](https://github.com/sophiedeakin/Snake/blob/main/assets/Read%20Me%20assets/Scroll%20Bar%20Bug%20Fixed.png)

When continuing my testing I found another bug that was important to fix, I noticed the arrow button controls were too big when viewing the game from a mobile phone perspective. The image below shows the bug I have found: 

![Arrow Buttons Bug](https://github.com/sophiedeakin/Snake/blob/main/assets/Read%20Me%20assets/Controls%20Bug.png)

I first tried changing the width of the controls div but it didn't work, so I did some research on how to make the div fit the width of the screen without affecting any of the images and found this [website](https://www.w3schools.com/css/css3_2dtransforms.asp). The website I used gave me guidance on the best CSS code to use to decrease the size of an element, I used "transform: scale();". From the image below you can see the bug has been fixed allowing users to clearly see all the arrow button controls and easily interact with them. 

![Arrow Button Bug Fixed](https://github.com/sophiedeakin/Snake/blob/main/assets/Read%20Me%20assets/Controls%20Bug%20Fixed.png)

---

# Deployment 

The Space Museum website was deployed using Gitpages and followed the steps below:

**GitHub Pages Deployment**

1. Log into your GitHub
2. On the left-hand side select the *Repository* you want to deploy.
3. At the top of the page there is a menu, find and click on *Settings*.
4. On the right-hand side there is a vertical menu, under the *Code and automation* section click on *Pages*.
5. Under *Build and deployment* there is a sub-section called *Branch*, select *None* and change it to *Main*.
6. The page will refresh and at the top of the page will be a message, "Your site is live at (Link to your GitHub page web address)"
**It can take some time for the link to be active.**

**Forking the GitHub Repository**

Forking your GitHub repository allows you to make a copy of your original repository and make any changes without overwriting your original repository. 

1. Select the Repository you want to fork.
2. Under the menu and your account, click on the *Fork* button.
3. Your repository is now forked and the copy is available to use.

**Cloning GitHub Repository**

1. Log into your GitHub and select the repository you want to clone.
2. Above the list of your file click on *<> Code*.
3. Copy the URL.
4. In *VS Code* change the current directory to the location of where you want the cloned directory.
5. In the terminal type in *"git clone"* and paste in the link from **Step 3**.
6. Press *Enter* and a local clone has been created.

---

# Credits

I have used various types of resources whilst designing and building this project. Any code that I have found and used from any sources has been commented on within the HTML, CSS and JavaScript files. 

**Guidance and Research**

The websites/articles below have been used for guidance and research:

- [Scroll Bar Bug](https://www.w3schools.com/howto/howto_css_hide_scrollbars.asp)
  * The following resource was used to fix the scrolling bug when the arrow keys are pressed.

- [Arrow Buttons Bug](https://www.w3schools.com/css/css3_2dtransforms.asp)
  * The following resource was used to help fix the visual issue with the controls not fitting the screen properly.

- [Media Queries](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/)
  * The following website was used to get the media queries for different types of devices.

- [Research on the original Snake game](https://en.wikipedia.org/wiki/Snake_(video_game_genre)
  * The following resource was used to gain information about the original game.

- [Stategy](https://asoworld.com/blog/how-to-promote-your-mobile-arcade-game/)
  * The following resource was used to help plan the strategy of the game.

- [Strategy](https://www.adexchanger.com/gaming/a-marketers-guide-to-breaking-down-stereotypes-in-the-gaming-audience/#:~:text=Casual%20mobile%20games%3A%20Casual%20games,players%20between%2018%20and%2035.)
  * The following resource was also used to help plan the strategy of the game.

**Media** 

The websites below were used for selecting and editing media for the game:

- [Canva](https://www.canva.com/)
  * Used for designing and editing the logo and the arrow buttons for the project.

- [Background Remover](https://www.remove.bg/)
  * Used for removing the background around the logo and arrow buttons making them transparent.

**Code**

The resources below were used to help code the game: 

- [Snake Game](https://www.youtube.com/watch?v=K8Rh5x3c9Pw)
  * The following resource was used to help design and build the game but changed some variables to make it my own style.

- [Popup Feature](https://www.youtube.com/watch?v=sEJB7FtBoug)
  * The following resource was used to help me build the popup that automatically pops up when the page loads. 
