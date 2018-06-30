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

