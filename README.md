# Pre-work - simon! An Interactive Light and Sound Memory Game

simon! is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: Eduardo Burga Donovan

Time spent: 14 hours spent in total

Link to project: https://glitch.com/edit/#!/warm-plume-moat

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
- [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
- [x] More than 4 functional game buttons
- [x] Playback speeds up on each turn
- [x] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

WinGame: ![](https://i.imgur.com/kgcOr03.gif)

LoseGame: ![](https://i.imgur.com/fQ6MKXB.gif)

DifferentPatterns: ![](https://i.imgur.com/1iEtHdB.gif)


## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

My knowledge of HTML and CSS was able to carry me for a lot of this project, but I knew wiring those to Javascript would be where I lacked.
The wiring instructions on the Pre-work sheet helped immensely and even made me remember a lot of Javascript that was tucked in the back of memory.
When I didn't know specific syntax for something, I used StackOverflow and CodeLab. StackOverflow was most effective since other developers upload their work for reference.

I used Google fonts to see how I could use the "Orbitron" font since that was closest to the original Simon font.

I also used "Web Dev Junkie" on YouTube since he has a lot of solid tutorials and courses for wiring Javascript to HTML.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

The challenges I faced during this project were mainly just styling errors, with one challenge occuring when trying to implement an "optional" feature. Originally, I had thought my challenges were going to be with wiring since I started not knowing exactly how to do it, but quickly grew to figure those issues out.

The first challenge was finding a font that would fit the aesthetic for the game. I tried to keep my design as similar to the original SIMON game as possible, so finding a font was difficult. I googled which font the SIMON game used, and found a similar font called "Obritron" on Google fonts. It gave the code needed to create the font, and implemented that into my game.

The next challenge involved a styling error. I was trying to get the buttons lined up correctly and able to move with the page resizing. I overcame this with the "display: inline-block" line, and I broke up the buttons into rows. The top row's 2 buttons are inline and the bottom row's 2 buttons are inline and they fit together with a final inline statement calling on all the "blocks".
I had little to no difficulties with the rest of the project, except when I was trying to implement an optional feature.

One of the optional features was to create a pattern that would change each time the game is played. I knew I had to use the Math.random() function, I just didn't know exactly how to implement it. So, I went to StackOverflow. I found the syntax for an array filled with random numbers each time the game starts.
There was a problem with the code from StackOverflow, however. It used the indeces from 0-3. This is not what I needed, so I knew I had to change it so that it read "Math.random() \* 4 + 1 )" which eliminated the possibility of a zero.
Overall, I did not encounter too many challenges in developing this project. It was a great refresher back into HTML, CSS, and Javascript after studying Java, C, and C++ for classes at SDSU. I found a lot of similarities between the languages, and I am excited to see the more difficult side of the Big 3 Web-design languages.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

After completing this challenge, my questions are mainly on the Javascript wiring. 
I immediately started thinking of all the real-life applications that could come from this simple introduction to the big 3 web-design languages.

I "Inspect"-ed quite a few of my favorite webpages to see the HTML for YouTube, Instagram, and the Google page when "CodePath" was searched. I found many commonalities between the HTML on those pages and mine in this project.
The main difference was definitely the complexity of information being displayed. While taking Codepath's Cybersecurity course with SDSU, I knew I could search for many of the security defenses set in place for many of these websites for privacy. Being able to see and implement these are a huge curiosity of mine.

In addition, I wondered how I would attach a Paypal or another form of payment to a website. Being able to make money off of a product or service increases the value of a website, so I am very curious to be able to set up a website for a shop or something of that nature.

There are a lot of other questions I could ask a professional, but it all seems to stem from a curiosity of the more complex side of web-design. I am incredibly eager to start learning and getting real world experience.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)

If given a few more hours to work on this project, I would spend the time adding more styling elements to the game.
When I finished the base project, I looked into the optional features that I could include in the game. A lot of them seem very interesting to learn and fun to implement in another game, but to be completely honest, I like the design and layout of the original SIMON game.
I didn't want to bombard the user with wonky graphics replacing the colors, or sounds that seem out of the ordinary for an attention based game.
That being said, if I were to stray away from my own idea of the design, I would implement those features and include a counter to see how many patterns the player got correct. I think that this could be a fun take on an original game.
Staying true to the original design of the SIMON game was a huge goal for me, and I achieved that.

## License

    Copyright Eduardo Burga Donovan

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
