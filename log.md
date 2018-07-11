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


