# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for Salesforce's Futureforce Tech Launchpad Program. 

Submitted by: **Noah Romo**

Time spent: **8** hours spent in total

Link to project: https://glitch.com/edit/#!/light-and-sound-memorygame

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

Example of start, stop, and game buttons:

![](https://cdn.glitch.global/2a09befe-459a-4c1c-b16e-eb43fb503908/partOne.gif?v=1650263797709)

Example of user losing game:

![](https://cdn.glitch.global/2a09befe-459a-4c1c-b16e-eb43fb503908/partTwo.gif?v=1650263802331)

Example of user winning game:

![](https://cdn.glitch.global/2a09befe-459a-4c1c-b16e-eb43fb503908/partThree.gif?v=1650263808124)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I used https://html-color.codes/ for css colors and https://www.w3schools.com/howto/howto_css_round_buttons.asp to create the round buttons.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
The main challenge I had on this project was programming in HTML, javascript, and CSS. I haven't ever programmed in these languages before so it was interesting to learn as I build. I have a strong understanding of fundamental programming concepts from my experience in C++, which definitely helped me in taking on these new languages. The new syntax can be confusing to look at, but I made sure to read all the syntax helpers in the instructions and google any syntax questions I still had. I also have found that when I write syntax notes down, it helps me remember better and also acts as my quick reference guide. Once I got passed learning the basic syntax for the project, the rest felt pretty easy. I saw HTML as the language I had to use to declare web objects in the DOM. Then after that, I just had to style the elements using CSS properties and call the functions I wrote in javascript to change the state of the HTML objects. It definitely is going to take a few more projects before I feel more comfortable with the syntax, but I am ready to continue practicing and learning. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I have a few questions on my mind. My first question would be how would a player's information, such as a username, be stored? Also, how would you create a login page for a user? It would be cool to learn more about how to prompt users to input information and how to store it after. My first thought would be to store user information in some sort of data structure such as a hashtable, but I don't know where I'd store this container. How do web developers store this data? How can I create multiple pages? And I still have a lot more questions about what makes up the front-end and back-end of a website or application.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had some more time to work on this project, I would probably work on two things. First, design-wise I'd try to reshape the buttons and make them look as similar as possible to the old Simon Says game. Figuring out how to design the buttons to look like four pieces of a circle would be really cool. I used to play that game a lot as a kid. Second, when it comes to the gameplay, I would work on the playClueSequence() function to make the game speed up after each clue is revealed. This would probably be done by changing the constant time variables to regular variables in order for me to decrease the time as progress is increased. A faster version of the game would definitely be more fun. And after that, if I really had the time, I'd look into how to implement some music into the game. Maybe played from the button, or just background music when you first open the game. A little music is always a great feature.



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright [Noah Romo]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
