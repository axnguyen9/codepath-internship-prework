# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Anna Nguyen**

Time spent: **3** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com/edit/#!/florentine-local-slug)

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
- [ ] Playback speeds up on each turn
- [x] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [x] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] Added cursor styling to buttons for better user interface

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://cdn.glitch.com/e57cd769-c547-475b-9e83-a39f4f1dcbdf%2Fezgif.com-gif-maker.gif?v=1616645393597)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.
   * N/A

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
   * I think one challenge was differentiating between the `progress`and `guessCounter` variables while writing the `guess` function. Because they both needed to reach the pattern length in order to satisfy the win condition of the game, I got confused between which variable stood for what while running through the logic of this function. I solved this issue by not only writing a small note to myself to differentiate between the variables, but also walking myself through the logic by talking out loud. It helped to think about how `progress` incremented one step ahead than `guessCounter`, which presented the user playing state, while `progress` represented the game state.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)
   * How much does time efficiency play into web development code and are there ways that web development could lead to slow efficiency? 
   * How could you test the user interface or client-facing website on different devices, such as mobile phones? 
   * I have seen people use jQuery before. What are the benefits of jQuery over JavaScript? How do you know what to use over the other?
   

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
   * I would try to clean up the styling to create a more pleasing user interface and implement dynamic user interaction in order to make the game more personable. Particularly, I would want to implement an initial question prompting the user to enter the max number of tones they want to hear in the pattern. Additionally, I would want to think about the time complexity of some my functions, especially where arrays are being iterated or initialized, and try to reduce the time complexity by using JS library functions or simplfying the code further. I think it would also be cool to make the game unique perhaps by adding another game element after each correctly-guessed patterned – maybe a trivia quetsion to spice it up?

## License

    Copyright Anna Nguyen

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
