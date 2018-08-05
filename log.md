# 100 Days Of Code - Log

### Day 1: June 21, Thursday

**Today's Progress**: I've been working on a VueJS project in which I will be making some simple applications in order to test things, or simply practice. I've started this project for a couple days before, but let's call this day 1. Today I implemented font-awesome as some other visual improvements, I've uploaded the code to github, and deployed the project to a web hosting.

**Thoughts**: Finding the right icon to the right action takes time.

**Link(s) to work**
1. [PinVue's Hub](http://pinguino.sonet.cl/pinvues-hub/)

### Day 2: June 22, Friday

**Today's Progress**: I played a lot with transition effects, added transition to router-view in Content component, the transition which is applied is dynamic depending if its going back to root or not.

**Thoughts**: Choosing the right animation takes time.
I am thinking in creating a breadcrumbs component and replace the back button on the apps.
Github is warning about a security vulnerability in package-lock.json, I have to check it out.

### Day 3: June 23, Saturday

**Today's Progress**: Worked on a vuejs app in which the user has to type the same characters of a random generated string as fast as possible.

### Day 4: June 24, Sunday

**Today's Progress**: I worked on the random string app that I started yesterday, I'm calling it Fastype. I wrote some tests for it using Jest.

**Thoughts**: I'm new to tests, but I'm already liking this tests thing. I'm thinking on giving test driven development a try.

### Day 5: June 25, Monday

**Today's Progress**: Worked on Fastype, made it friendlier to mobile, had to change the keypress event to input event, re-wrote some tests, and pushed it to github.

**Thoughts**: I should try mobile first approach.

**Link(s) to work**
1. [PinVue's Hub](http://pinguino.sonet.cl/pinvues-hub/#/apps/fastype)
2. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/f77b7607a9c35ba76d00dd32706be1815ff8d66c)

### Day 6: June 26, Tuesday

**Today's Progress**: I started to work on a Sudoku generator, trying the test driven development approach. It surprises me how I have tons of tests, some functions and 0 user interface yet.

**Thoughts**: I don't know if I'm doing this right though, maybe I should read more on how TDD works.

### Day 7: June 27, Wednesday

**Today's Progress**: I kept working on the Sudoku generator. I'm trying to generate a completed Sudoku and then remove some random numbers. The algorithm is failing while filling the matrix, it gets to a point where there is no valid number to fill the position.

**Thoughts**: It seems that I should use a recursive function to fill the sudoku matrix, so when it gets to a point where there are no more valid numbers, it should go back and re-fill the positions with new number combinations. But in order to implement a recursive function, before I should refactor the randon number generator, because right now it is just brute force, it generates a random number between 1 to 9, and if it doesn't fits the requirements (sudoku rules) it generates a new number, and keeps doing that until it generates a one which fits, so the recursive function would probably get stuck if it keeps getting the same numbers.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/1e6634655ff504f669a893c9d4de6859495f6647)

### Day 8: June 28, Thursday

**Today's Progress**: I kept working on the Sudoku generator. I refactored some functions, It's recursive now, but it is still not working.

**Thoughts**: It is 4:35 am, I'm tired, I was going to code for an hour, ended coding for 4 hours, and the thing is still not working >:(.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/e5026299ccf6a071419b69c681611e78a67ea6af)

### Day 9: June 29, Friday

**Today's Progress**: Finished the core functionalities of the Sudoku, it now displays a random generated puzzle.

**Thoughts**: I had to google to get help with the puzzle generation algorithm, my mind was melting, the code was still not working, I didn't know why, it seemed ok to me, so I started to refactor it for better readability, and then it suddenly started to work. The spaghetti was keeping me to see the bug.

**Link(s) to work**
1. [Commit 1](https://github.com/pinguinosod/pinvues-hub/commit/11f2b4b1f8d5a10d108e99c78f9ffa3f351a1080)
2. [Commit 2](https://github.com/pinguinosod/pinvues-hub/commit/f9ffc8b65d9d59503ae35cf4852f1a4e93e949bf)
3. [Commit 3](https://github.com/pinguinosod/pinvues-hub/commit/74d9f760bf2f52dc15cd89f0c84510aa091f417e)

### Day 10: July 1, Sunday

**Today's Progress**: Started to work on a Cryptocurrency app. It's retrieving data from CMC's API and it's showing the top 100 cryptos.

**Thoughts**: I want to make a candlestick chart for a selected crypto, but I will need a different source of data, maybe Binance's API.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/2d0ca4348560c40decea7cbbd51a8a40fa7cf3c6)

### Day 11: July 2, Monday

**Today's Progress**: I generated a candlestick chart for cryptocurrencies, it is consuming Binance's API. (I replaced what I had).

**Thoughts**: The UI/UX sucks, I have to work on that, and it lacks tests, I have to write them. But the biggest step is already done.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/efa2e3c145f1d09f278cf5fcc0c3fad75eec576c)

### Day 12: July 3, Tuesday

**Today's Progress**: I wrote tests. I found and corrected an error on a function.

**Thoughts**: I wouldn't notice the error if I hadn't wrote tests.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/6112b98321968690209f7621a1012eda6a382d01)

### Day 13: July 4, Wednesday

**Today's Progress**: I kept working on the Cryptocurrency thing, I gave it an UI/UX Upgrade (nothing fancy though, it's still ugly).

#HireMeBinance 😆

**Thoughts**: I copied Binance's layout to select a pair, somewhere I read that you shouldn't innovate unless your solution is way better, people are used to design patterns, you shouldn't make things harder for them.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/a54485b07e772f391dd14aef8b4c2b4f26c534c3)

### Day 14: July 5, Thursday

**Today's Progress**: Worked on the pinvue's hub website, took the animations from the apps and merged them in one file, so now the common animations should go there. Tried to change the colors for hours, ended up with the same colors. Added github link and about link.

**Thoughts**: I am bad at picking colors.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/cdf38ae21a70f571f78b467880c5f7c5ee45ba02)
2. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/c0c78527f80298c245fe7092f4027db693d1374b)

### Day 15: July 8, Sunday

**Today's Progress**: Kept working on the cryptocurrency thing, it looks a little better now, the time interval is now selectable.

**Thoughts**: I lost two days because I decided to go out for some social interaction, also I had to work on an assignment for a job oportunity, but now I am back on track.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/4a57be67275989149ccd3f59e4ab46b32780f3f0)

### Day 16: July 9, Monday

**Today's Progress**: Still working on the cryptocurrency chart, I added the price on the Y axis of the candlestick chart.

**Thoughts**: I should add a line indicating the current price, and then add the volume at the bottom, and then get hired by tradingview or something 😅.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/55b70e643706ecf0f0d79f937cc205874911a557)

### Day 17: July 10, Tuesday

**Today's Progress**: Still working on the crypto chart, I added the current price indicator.

**Thoughts**: Next thing: the volume.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/ebaf7c618abff7c8959718171d0249b99f3c44f5)

### Day 18: July 11, Wednesday

**Today's Progress**: Still working on the crypto chart, I added the volume, and gave it a little visual improvement.

**Thoughts**: The last things I have added doesn't have tests, I have to write tests.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/f4ac3d4405a5faf15b4761574aee326b5e637c49)
2. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/0ef00bf083956ca11f949189b131e26304a27589)

### Day 19: July 12, Tuesday

**Today's Progress**: Today I contributed to https://github.com/cryptoluka on their peer map. I'ts online here: http://peers.cryptoluka.cl/ 

It's funny because after being the whole afternoon working on a solution, I ended up noticing I just had to modify like 3 lines. But it was a good learning experience.

**Thoughts**: I had to work with NodeJS which I'm not very familiar with, learned about working with cache, which is very useful.

**Link(s) to work**
1. [Commit](https://github.com/cryptoluka/lukapeersbackend/commit/0b36de40fe28441a2df7d62921f45105403d65c3)

### Day 20: July 13, Friday

**Today's Progress**: Today I wrote more tests on the cryptocurrency charts app.

**Thoughts**: I think I should leave the cryptocurrency charts app for now and start working on something else.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/91d196d627aa123475b53aa04136f69358e947dd)

### Day 21: July 14, Saturday

**Today's Progress**: Today I came back to PHP, worked on OOP stuff. 🙃

**Thoughts**: I feel like keep doing more PHP stuff, because I'm very rusty.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/simple-portfolio-class/commit/fbcff5c469aed27a4238ba51185601bf4c3a3222)

### Day 22: July 15, Sunday

**Today's Progress**: Today I started working on a very simple text based fantasy RPG game. It's called Storm at the Mountains. I just started building it as a prototype, if its good I might start working on a bigger version.

**Thoughts**: I'm still getting used to TDD.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/276eaa26befd2b59d4cfd5db1c5c1e2bf8ee795e)

### Day 23: July 16, Monday

**Today's Progress**: Today I kept working on SATM.

**Thoughts**: Tests first, code later. I was so used to run the app and interact with it in order to test it, it is very cool to test it from console and know it will work if its passing the tests.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/a037ea8bc838bea5c66efab605d97d33c5943812)

### Day 24: July 17, Tuesday

**Today's Progress**: Started to work on the battle functionalities of SATM.

**Thoughts**: Being tired makes coding harder.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/ef2dd47001f007d946fe250be1b1bf5cb448a10b)

### Day 25: July 18, Wednesday

**Today's Progress**: SATM: Code refactoring. The code certainly looks better now, I moved the encounters array to a JSON file.

**Thoughts**: So I'm at 25% of the challenge, it has been a good journey so far, I haven't do anything fancy yet, but I've been training muscle memory on VueJS. Also I started using tests and I'm trying to get used to it.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/b776e105a48ec8b90f6bc2dddb4f9f4cfcadcfb0)

### Day 26: July 19, Thursday

**Today's Progress**: SATM: Completed the core structure.

**Thoughts**: I have to make it harder, better, faster, stronger..

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/286428bc78b31f7fdabd60303c8ca1a5eb2ac3ad)

### Day 27: July 20, Friday

**Today's Progress**: SATM: Visual upgrade.

**Thoughts**: I sucks at UI.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/3ca3e926d2c2b1b700bda06e3d2e0e2e22ba1115)

### Day 28: July 21, Saturday

**Today's Progress**: SATM: Upgrade battle system, add initiative, enemies fight back.

**Thoughts**: I spent 50% of the time debugging a bug.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/28612e1857d7a3e27872b64959c86e2af9b7e999)

### Day 29: July 22, Sunday

**Today's Progress**: SATM: Implement combat log. ⚔️

**Thoughts**: I spent quite some time making the animation of adding a new entry to the list.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/bb0b704afc3f90f1345d009b4157850c07fa3973)

### Day 30: July 23, Monday

**Today's Progress**: SATM: Implement experience points and level up. Add some minor features and fix minor bugs.

**Thoughts**: I've been working for 9 days on SATM, its looks better than I thought It would look at first, I feel like working on it for a couple more days and then jump to another thing.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/0447bcdd385c87d0ffad59f59703fce165f246aa)
2. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/baff8c7309321d03627dd7c4dc96b5cc1de3074c)
3. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/bb7c2eb04e53f5584dfcf060a2e9732394141edc)
4. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/57e682890428e906766535ea65c2a18539d5b805)
5. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/214c1e33a7e98812d1e5640fc590572a262212e6)

### Day 31: July 25, Wednesday

**Today's Progress**: SATM: Implement i18n.

**Thoughts**: I took a day off yesterday, but I'm back on track now.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/e7456445ee79f241ff72f8de5b23648e95fb0bd0)

### Day 32: July 26, Thursday

**Today's Progress**: I kept working on i18n of SATM, I made like 80% of the text translatable, and did the spanish translation.

**Thoughts**: There are couple challenges on i18n that I still don't know how to address.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/6f5f21a63ac9f440cb8610f13f7e2483d0980451)
2. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/8778bf53d6c9e53cc1b2ac6f0acd27e2726020c1)

### Day 33: July 28, Saturday

**Today's Progress**: Completed i18n of SATM, and got it fully translated to spanish. I learned how to deploy to gh-pages, the thing is now hosted here: https://pinguinosod.github.io/pinvues-hub/ 

**Thoughts**: The cryptocurrency app isn't working because the endpoint is not https, I will upload it to somewhere else later.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/360330fe363580a5bb917cf164378d2fcb2a65d5)
2. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/129415b6f8677fe979dd23688d1722c5ab770356)
3. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/145ac382161d2ea6fea80594043b331e33713547)

### Day 34: July 29, Sunday

**Today's Progress**: Figured out how heroku and composer works. Uploaded the cryptocurrency backend to heroku, now it works again. https://pinguinosod.github.io/pinvues-hub/#/apps/cryptocurrency

**Thoughts**: The way I deploy to gh-pages is pretty lame, I messed up node_modules folder while doing it 🤣

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/pinvues-hub/commit/c95cc3ba1be701e1daf45905e1c0bd89fda736e1)

### Day 35: July 30, Monday

**Today's Progress**: Didn't really code much today. I installed VS Code to try it out (I was using Atom), and kept messing around with deploying to heroku.

I made this thing in PHP which generates 3 random numbers (stats) between 7 and 16:
https://phpinguino.herokuapp.com/rpg/generateRandomHero.php?name=Pinguino

**Thoughts**: I'm going to stop with VueJS, and start doing things with PHP or Angular, I still can't decide which (I want to get better at both).

### Day 36: July 31, Tuesday

**Today's Progress**: Started to work on a tic-tac-toe on PHP.

**Thoughts**: Not directly related to code but I went to a PHP meetup today, there was a presentation about querying in laravel and I was pretty lost because I haven't used laravel, but I got some knowledge and exposure to how things work. Also is great to meet new people who code.
And I watched some videos about the new features of PHP 7 (I hadn't use PHP 7 before).

### Day 37: August 01, Wednesday

**Today's Progress**: Completed the core functionalities of Tic-tac-toe, pretty simple, computer is dumb, but it works. 

**Thoughts**: I plan to make a frontend for this on angular, in order to learn/practice angular.

**Link(s) to work**
1. [Hosted here](https://phpinguino.herokuapp.com/tictactoe/)
2. [Commit](https://github.com/pinguinosod/tictactoe-backend/commit/44a44bd825f64b1d68ba8adc3d253a4812376073)

### Day 38: August 02, Thursday

**Today's Progress**: Implemented difficulty levels on Tic-tac-toe. Difficulty 1 and 2 are too easy, difficulty 3 is not done yet. 

**Thoughts**: As soon as I finish difficulty 3, I'll start working on an Angular Frontend.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/tictactoe-backend/commit/e3d4a239bede328f8bbe4631fcb8ad3ff058ca72)
2. [Commit](https://github.com/pinguinosod/tictactoe-backend/commit/722b06bf1fcf7d1b1c46e091585bcff5a86342e3)

### Day 39: August 03, Friday

**Today's Progress**: Advanced on the difficulty level 3 of Tic-tac-toe.

**Thoughts**: I just noticed I don't know how to write tests on PHP. So before jumping into Angular, I will learn how to use PHPUnit.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/tictactoe-backend/commit/3fcac41a82a4555242a72c04636814a6261aa2a4)

### Day 40: August 04, Saturday

**Today's Progress**: Installed PHPUnit and wrote some test. Also refactored the code.

**Thoughts**: I bought an Angular course on udemy, I'll be doing that tomorrow.

**Link(s) to work**
1. [Commit](https://github.com/pinguinosod/tictactoe-backend/commit/34422b856f263c2fc0057d7cb07bf37a0bd61243)
2. [Commit](https://github.com/pinguinosod/tictactoe-backend/commit/be0812d4600b21ad50db7b89d479a0dcb7b33970)

