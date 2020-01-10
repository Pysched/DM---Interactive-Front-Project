# Interactive Front End Development Project - Snap Card Game

This project consists of designing an interactive game, snap. Snap is a card game where by the user is presented with a number of cards, 16 to start with, which are faced down. The aim of the game is to match pairs of cards. There are 3 levels to the game. The first level is play cards to be matched, by number and by suit, hearts, clubs, spades and diamonds. The second level is shapes, this will be similar shapes, with subtle differences to increase the difficulty. THe 3rd level will be patterns, all the same colour but again with more sublte diffferences.

How to play: The player selects a card, which animates flipping over to reveal what it is, the user then selects another card, which performs the same action. If the cards match they stay facing up to the user and are added to a counter that indicates how many pairs the user has found. If they do not match, then then both flip back down and the user carries on until they match a pair.

To add to the difficulty the user is faced with a count down timer. All matches must be completed within a given time (to be determined through play through and assessment of difficulty). The user is also rated against how many attempts that they have made, A live scale beside the attempts counter will indicate from green to red how effective the player is. 

The timer is constantly displayed on screen as is the flip attempts counts and a rating of attempts very a pre determined rating. Example: if there are 16 cards, thats 8 pairs, if it takes the user 12 attempts, then that is a ratings of green, if it takes 16 attempts then it is a rating of amber, 18+ attempts it is a red rating and the player needs to replay the game. 

THe player will also have the option from the start of selecting the difficulty level, this will be differentiated by the number of cards. Example: Start with 16, 20 or 24 cards, with different time amounts for the game to be completed in. 

At the start of the game the player will be asked to enter there name, this can then be passed to the endgame overview where the players name and results are displayed. Based on how the player scored, different images, graphics and commentary will be provided based on time, score, effeciency and how many pairs are matched.

As each level of the game is completed the user is brought to the next level of difficulty. Example: if the player wins the 16 cards level of difficulty they are progressed to the 20 card round etc..

After 3 rounds or by winning the hardest level, 24 cards, the player is then presented with the next level of thegame , level 2 has shapes inside the cards instead of numbers, Successfuly winning this level progresses the player to the 3rd level, patterns. Each time all 3 levels of difficulty are finished the player is brought to the next level;

Level 1: Palying cards
Level 2: Shapes
Level 3: Patterns

Successful completion of each level presents the player with a summary screen that shows the results of the round; Time completedd in, attempts taken, effectiveness ratings.

 
## UX


Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:
- As a user type, I want to perform an action, so that I can achieve a goal.

This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.
 
### Existing Features
- Feature 1 - allows users X to achieve Y, by having them fill out Z
- ...

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement
- Another feature idea

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.


## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X
