# Pre-work - *Memory Game*

Galactic Hopper is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Aidan McSpadden

Time spent: 2.5 hours spent in total

Link to project: https://glitch.com/edit/#!/spice-puzzle-mall

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
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
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
![x] http://g.recordit.co/6t0NSthacQ.gif


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
 https://www.w3schools.com/css//css_font_websafe.asp
 https://www.w3schools.com/js/js_random.asp

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

   A good portion of my effort was spent attempting to randomize the sequence. I nearly got it down but decided to submit it without the code as 
 there was a lot of debugging to do. I have never coded in javascript before so understanding the basics and trying to relate it to C++ was quite
 difficult and took some time. I didn't want to just copy-paste the code given in the instructions so I manually typed it out to try and get a grasp
 on what exactly the code was doing. This helped a lot, however, it still took me a significant amount of time to analyze and figure out. A
 particular spot that was difficult was creating the actual nested loops(if-else statements) required to make the game actually run. I honestly
 had a lot of fun(though I did struggle a little) trying it out. If i had no prior C++ experience this would have been a nightmare! Other than the
 actual code itself, wrapping my mind around the concept was quite difficult. Specifically the nested if-else statments. Trying to imagine and
 play out the different scenarios in my head took a little bit of time and hard thinking/problem solving. Overall the experience was honestly
 really fun, I only just recently got into coding but I have loved every minute of it and this project was my very first using javascript and HTML.
 I especially had fun comparing and differences and similarities between javascript and C++(the for loop was almost identical!). 
 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
 
   After doing this project I realize that web development, and specifically, code that runs on webpages require a LOT of code to work. Something
 that seems simple might have taken hours upon hours to create. My questions would be how do people implement different code languages into webpages.
 I understand the answer is probably really simple but I never understood the complexities behind running different code languages through a single
 compiler. Does it use different compilers or does it use some special one that can handle different languages. Perhaps you use a indicator? I suppose
 this is not the best question but it was always something I thought about when playing web-based games or seeing animations.
   One other question I always thought about was how much work is required to create webpages that animate as you scroll(think apple.com iphone page:
  apple.com/iphone-12-pro/) These seem INCREDIBLY complex and difficult to create. The number of factors required(scroll speed, page zoom, even monitor
  size) to be taken into consideration is mind boggling. All i can really do is give my respect to those computer scientists and engineers who make
  webpages like that(and really any webpages at all). 
 
 
4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

  I might come back to this but I really want to convert the buttons into one giant picture of a galaxy, where each of the four buttons represents
  a quadrant of said galaxy. Then I could set it up to be like identifying which region of the galaxy the sound came from! I would also like to add 
  a center-button(think a 2x2 layout with a 5th button in the middle) and make the outer 4 buttons(of the 2x2 grid) rounded off on the out corner
  and center(in order to fit a circular 5th button) This way I could make it so theres 5 total areas where the sound could come from and you have to 
  guess/remember which region. Lastly, I could take away the lighting up aspect and make it purely audio-based after a set number of rounds(maybe 10?) 
  which would severely up the difficulty. Maybe even make it so the round it switches to purely audio is based off how fast the user clicks/inputs
  the correct answer after each turn.



## License

    Copyright Aidan McSpadden

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.