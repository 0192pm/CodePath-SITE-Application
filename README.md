# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: Keisha Maru Benauro

Time spent: **#** hours spent in total

Link to project: [https://satisfying-grandiose-agreement.glitch.me](https://satisfying-grandiose-agreement.glitch.me/)

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [x] Buttons use a pitch (frequency) other than the ones in the tutorial
- [x] More than 4 functional game buttons
- [x] Playback speeds up on each turn
- [x] Computer picks a different pattern each time the game is played
- [x] Player only loses after 3 mistakes (instead of on the first mistake)
- [x] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] Add moving alien icon
- [x] Blur game buttons when clicked
- [x] Alert with a count of total mistakes made
- [x] A round of appalause is played after winning the game
- [x] An alert saying to refresh page after winning the game

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](http://g.recordit.co/A9fAaXHwKv.gif)
![](http://g.recordit.co/rcz6bDrETJ.gif)

* NOTE: Sound of the buttons and round of applause cannot be heard from the gif. Also, when the same button is pressed twice, sometimes it is not captured by RecordIt in the Gif.

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

- Customize Outline Button Color: [https://www.w3schools.com/howto/howto_css_outline_buttons.asp](https://www.w3schools.com/howto/howto_css_outline_buttons.asp)
- Add Custom Font: [https://stackoverflow.com/questions/12144000/using-custom-fonts-using-css](https://stackoverflow.com/questions/12144000/using-custom-fonts-using-css);
- Font Website: [https://fonts.google.com/](https://fonts.google.com/)
- Fonts used: Trispace 400, Staatliches
- Add Glow to Colored Buttons: [https://www.codingnepalweb.com/cool-glowing-effect-on-buttons-html-css/](https://www.codingnepalweb.com/cool-glowing-effect-on-buttons-html-css/)
- Up-Down Alien Animation: [https://codepen.io/jaabert/pen/gObMGBV](https://codepen.io/jaabert/pen/gObMGBV)
- JavaScript’s Random Number: [https://stackoverflow.com/questions/5836833/create-an-array-with-random-values](https://stackoverflow.com/questions/5836833/create-an-array-with-random-values)
- JavaScript Random Number Not Starting at Zero: [https://stackoverflow.com/questions/6702146/generating-random-integer-in-range-that-doesnt-start-at-zero](https://stackoverflow.com/questions/6702146/generating-random-integer-in-range-that-doesnt-start-at-zero)
- Image on HTML Button: [https://www.delftstack.com/howto/html/html-button-with-image/](https://www.delftstack.com/howto/html/html-button-with-image/)
- Play Audio in JavaScript: [https://www.delftstack.com/howto/javascript/play-audio-javascript/#:~:text=Use%20.-,play()%20to%20Play%20Audio%20Files%20in%20JavaScript,play()%20function.](https://www.delftstack.com/howto/javascript/play-audio-javascript/#:~:text=Use%20.-,play()%20to%20Play%20Audio%20Files%20in%20JavaScript,play()%20function.)
2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

    This was my first time integrating several features into one project. Because of the relatively lengthy code compared to my previously smaller in-class projects, I encountered a few challenges along the way, specifically when it came to functions in the required steps of Task 1: the **_startGame()_** and **_stopGame()_** functions failed to run and the **_lightButton()_** function was not lighting up during the actual gameplay (which resulted in a Sound Memory Game instead). Initially, I looked through each step against my code to find any discrepancies between the two. Luckily, this fixed the issue with the **_lightButton()_** function as I had simply overlooked the _#button4.lit_ selector on CSS.

    As someone who is most comfortable with Python, I had difficulties creating a random sequence using JavaScript syntax. Luckily, I found resources _f_ and _g_ to help me create an array that generated a list of 8 random numbers from 1-6, which corresponded to each button. I repeatedly played the game and tested out different button combinations each time (ex. purposely making a mistake every other turn). It was a bit tedious at first but was eventually worth the time when I found several errors. 

    In addition to the required and optional steps, I wanted to create an outer space theme because I thought it matched the lights and alien-like sounds produced by the buttons. Despite it being my first time using CSS I was determined to execute my design plans so I worked around my skillset and used resources online to style the website to my liking:

      - I used the free fonts provided by Google for my personal use.

      - Because it is a “Light and Sound” memory game, I wanted the six colored buttons to light up to match the name. There were several tutorials on this and I decided to use the _filter: blur()_ declaration because achieves a nice simple and subtle effect.

      - To fit the space theme, I created the button and alien icons on After Effects. I wanted to challenge myself by moving the icon using CSS instead of uploading a gif using After Effects which, to my surprise was fairly straightforward and only required tweaking values.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

    - What other tools and software can be used in addition to HTML, JavaScript, and CSS to add more features into a web application?
    - What tips can be used to integrate better UI/UX to a project?
    - How often should one check that their web application is at peak performance?
    - What are ways to gain and establish credibility when a website collects more sensitive data from its users?
    - How often do front-end and back-end developers talk to each other?
    - What are ways to make websites and web applications more accessible everybody especially to those who are blind or deaf?
    - How do you take inspiration from other developers' code, especially in front-end development?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
   
   With a few more hours, I would dive deeper into the CSS and HTML aspect even more to incorporate more dynamic into my website with a moving background and more button animation.
   
   In terms of functions and features, I would add levels to the game where the number of turns would get longer after each level has been completed. For example, in Level 1, there would be 8 turns (what we have right now). In Level 2, there would be 10 turns. And so forth.
   
   For those who are up for the challenge, I would include the option to increase the game intensity by changing the position of the colored buttons in each turn. For example, the green button (1st position) would be in the 3rd position (pink button) while the yellow button (4th position) would be in the 5th position (orange button). In the second turn, the green button is in the 2nd position, and so forth with the rest of the colored buttons following a similar pattern.
   
   Instead of the alert in the **_loseGame()_** and **_winGame()_** functions, I would replace them with the words "GAME OVER" and "YOU WON", respectively, and gradually increase its font size across the webpage.

## Interview Recording URL Link

[https://www.youtube.com/watch?v=ihvFfZ612S0](https://www.youtube.com/watch?v=ihvFfZ612S0)

## License

    Copyright Keisha Maru Benauro

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
