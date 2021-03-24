# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Alice Wang

Time spent: 3 hours spent in total

Link to project: https://debonair-generated-macadamia.glitch.me/

## Required Functionality

The following **required** functionality is complete:

* [ x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ x] Game buttons each light up and play a sound when clicked. 
* [ x] Computer plays back sequence of clues including sound and visual cue for each button
* [ x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ x] User wins the game after guessing a complete pattern
* [ x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](your-link-here)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
w3schools.com and StackOverflow 


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
At first, I had trouble getting the start and the stop buttons to switch. Once I compared my code to the example code that was provided it turns out that I misplaced the code outside of the function. I used console.log to help debug. There was no sound when I went inactive for a while so I inspect the page. I went over to the console and saw, "The AudioContext was not allowed to start. It must be resumed (or created) after a user gesture on the page."  I searched on the internet to find a solution by copying the error message on Google along with the name of the program. I browsed through a few links to try to debug the error or to see if it had been already documented on the internet. I read through the comments to try to find a solution but when I went back to reopen the page it worked again. Turns out a simple refresh solves the problem. Every time I debugged, I used the "inspect element" option on Chrome to view console.log printouts which took me to a specific error on the webpage's HTML code. Then I search to see If this error had been encountered before. 
3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
How do I plan out a page layout from scratch and user flow diagrams?
What are some helpful HTML good practices that are helpful to know?
How security is implemented?
How do web developers market their sites?
How do I place ads on my site?
How do I get a customized hostname?
Are there any other debugging tips and tricks?


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
I would like to make it mobile-friendly. I noticed when I resize the window the layout of my webpage is compressed. The buttons are no longer in the pattern that I had started out with. Thus, I would like to rescale depending on the screen. Aesthetics-wise, I want to create a better user interface so it would to accessible to anyone. I would experiment with different color themes as there is a wide range of RGB values. I would just go from there instead of using hard-coded names. Functionality-wise, I would add a leadership word so it'll be more competitive. It would depict a user and their high score. That would mean I would have to implement a database to keep track of all the users which is a nice challenge to take on.




## License

    Copyright Alice Wang

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.