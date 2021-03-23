# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: Elizabeth Tran

Time spent: 4.5 hours spent in total

Link to project: https://knowledgeable-everlasting-layer.glitch.me

## Required Functionality

The following **required** functionality is complete:

- [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [ ] "Start" button toggles between "Start" and "Stop" when clicked.
- [ ] Game buttons each light up and play a sound when clicked.
- [ ] Computer plays back sequence of clues including sound and visual cue for each button
- [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [ ] User wins the game after guessing a complete pattern
- [ ] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
- [ ] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [ ] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] I added an image of a dog to each of the different buttons.

## Video Walkthrough

Here's a walkthrough of implemented user stories:

![](https://i.imgur.com/Nbitbzu.gif)

![](https://i.imgur.com/6ft2I2i.gif)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. -https://www.w3schools.com/cssref/css_colors.asp (change color scheme of app) -https://stackoverflow.com/questions/8818543/how-to-give-html-button-tag-an-image/8818584 (used to learn how to add images)

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
   After learning a little bit about creating this game, I was inspired and motivated to make it more creative and personal to me. As a result, I wanted to add an image of a dog to the different colored buttons specifically. However, being new to HTML and CSS, this was a challenge itself and I had no clue how to approach this problem. After researching and learning more about the <img> tag in HTML, I learned how to use the link of an image and add it to the app. On my first attempt, the image of a dog did appear on the screen but it was not on the button since the section I added the image in was part of the background. From this mistake, I learned that I need to specifically add the image to the different buttons in my HTML code or else the image could be a background image. While the image did pop up on the screen, the size was out of range and was way too big for each of the colored buttons. Knowing that I had to adjust the image size to fit into the button frames, through trial and error, I changed the width and height of each image until I got my desired size.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)
   After learning how to create this game, I am interested in learning more about web development’s role in the development of applications along with gaming websites. For example, when creating an app for online shopping or social media, how do we make applications more interactive for the users. In the apps we use today, is CSS, HTML, and Javascript the core fundamentals that are used to build these applications? While I was watching the tutorial for this project, I was intimidated because I did not know what step to do first. Therefore, my next question is how do web developers figure out and determine what step to take first in creating their project. During the process of creating this game, we jumped back and forth a lot between different functions and adding new details and variables. Is this a normal process in web development? If so, how do we keep track of what task to tackle next to make sure everything comes together in the end.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
   If I had a few more hours to work on this project, I would create a big explosion as seen in cartoons that pops up in the center of the screen when the player chooses the incorrect button. After the explosion, the words “Loser” will appear on the screen as the audio in the background says “You lost!” On the other hand, if the player wins the game, I would create a drop down banner that says “Congratulations” with an audio in the background that says “You won!” If I am able to accomplish this, my next goal would be to increase the difficulty of the game by adding a second level. In the second level, all the colors and sounds corresponding to each button will be the same. The purpose behind this idea is meant to make the game a little bit trickier and more confusing for the player as it is harder to differentiate if there is no difference between the blocks.

## License

    Copyright Elizabeth Tran

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
