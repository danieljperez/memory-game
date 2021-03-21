# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Daniel Perez**

Time spent: **9** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

## Required Functionality

The following **required** functionality is complete:

* [✓] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [✓] "Start" button toggles between "Start" and "Stop" when clicked. 
* [✓] Game buttons each light up and play a sound when clicked. 
* [✓] Computer plays back sequence of clues including sound and visual cue for each button
* [✓] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [✓] User wins the game after guessing a complete pattern
* [✓] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [✓] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [✓] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![http://g.recordit.co/HV1vujhOD6.gif](http://g.recordit.co/HV1vujhOD6.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

[https://www.w3schools.com/js/js_htmldom_html.asp : I used this website to help better understand the commands I used to implement the three-strike system.]]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

[A challenge that I encountered when creating this submission was that when I would run the game, once a game button would flash to the darker color, it would not revert back to the lighter color. The game would continue on if you pressed the right buttons, but they would stay shaded in, so it basically gave away which button was next. For some reason, the browser I was using did not work, so I had to switch to another browser which solved my issue. I also had some complications trying to add my three-strike system. When adding a visible counter, the counter wouldn’t update when it was supposed to and would only update after someone finally guessed the right button or when the next part of the pattern was shown to the player. This was an issue because if someone guessed the same step wrong 2 times, they would only have one more try, but the counter would still say the player had made 0 mistakes so far. I fixed this by looking at w3schools and adding an extra line of “document.getElementById("mistakes").innerHTML = mistakes;” in my code. After finding where this line was needed, my code began to function as needed.]]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

[After completing my project submission, I am still confused on how audio works with JavaScript. I was confused on the part with the AudioContext library. I read through the instructions a few times, and also watched some YouTube videos to try and clear things up, but I am still confused on how exactly it works. Specifically, I didn’t understand the o and g variables and how the different lines functioned exactly. Sometimes when I would run my program, the audio wouldn’t work even though I didn’t change any code. After rerunning the code, it would work, but it left me confused as to what was wrong.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

[If I had a few more hours to work on this project, I would start by refactoring my strike system to look and function better. I would try to put it next to the start/stop button rather than below in order to save some space. I didn’t know too much about the way this function worked, so I would do more extensive research into it to make it work better. Once I complete this, I would work on some of the optional/additional features that I wanted to add originally. I wanted to try to implement the secret pattern and the ticking clock before submission, but I was struggling and couldn’t figure it out on my own. I tried watching some YouTube videos and looking at stack overflow, but I couldn’t grasp the concepts. Lastly, I would add on the rest of the optional features. I feel that sprucing up buttons and speeding up the game would make the game more enjoyable to the player.]



## License

    Copyright Daniel Perez

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
