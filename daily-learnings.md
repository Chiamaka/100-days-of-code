
##Day 1: December 31 2016
**Today's Update**: Flexbox working using [Flexbox Patterns](http://www.flexboxpatterns.com/home) and some vanilla JavaScript for interaction.

##Day 2: January 1 2017
**Task**: Read JavaScript Allonge for 1 hour.  
**Learnings**:  
1.  Arrays are reference types so  
    ```
    const a = [], b = x;
    a === b
    ```
    will return `true` AND
    ```const a = [1,1+1], b = [1,2];
        a===b
    ``` will return `false`  
2.  New way to extract elements from an array. **Destructuring**. Its a reversal of the usual array literal creation method. Place the template on the left and the array to be picked apart as the value on the right.   
3.  Extracting arrays from arrays is known as gathering. Using `...` to destructure is gathering, using it in a literal to insert elements is called spreading.  
    ```const array = [1,2,3,4,5]
        const [a, ...rest] = array; //gathering
        const spread = ['0', ...array]; //spreading
    ```  
4.  Recursive algorithms follow the 'divide and conquer' strategy for problem solving.  
5.  Note to self; think of `...` in spreading as removing the [] from the passed array to reveal its true nature.   

##Day 3: January 2 2017
**Task**: Worked through Day 07 and Day 09 of JavaScript 30. I couldn't do Day 6 cos I dont have internet connection. I am in my village, lol


**Learnings**:  
1.  `Array.prototype.some()` returns `true` if at least one element in the array meets the condition set.  
2. `console.log` can take a `{}` and it'll print out the result as an object. You can also use `console.table` takes an array of objects and prints it out in a tabular form.  
3. `Array.prototype.every()` returns `true` if all the elements in an array meets the condition set else it returns `false`  
4. `Array.prototype.find()` returns the 1st element in an array to meet the condition.  
5. `Array.prototype.findIndex()` returns the index of the 1st element that meets the specified condition  
6. `Array.prototype.splice()` can be used to delete an element from an array.  
7. `console.assert` takes the condition and the string to be displayed if and only if the condition is wrong/false. eg `console.assert(1===2, 'That is very wrong')`. This fires only when it is false. If it is true, nothing happens  
8. `console.dir` prints all the properties and methods on a selected DOM Element  

##Day 4: January 3 2017
**Task**: Worked through Day 06 of JavaScript 30.  
**Learnings**:  
1. `fetch` api. It returns a promise with a blob of data. Because its a promise, you have to use `.then` to get the results.  
2. Template literal in ES6 can be used to create an html structure to be injected into a selected area. eg  
    ```
         return `<li>${band}</li>`;
    ```  
3. Regular expressions and template string literals are very powerful!  

##Day 5: January 4 2017
**Task**: Solved an advanced algorithm in FCC, Symmetric Difference  
**Learning**:  
It was hard as fuck at first. The style I wanted to use in solving it was crazy so after 30 minutes of banging my head against a brick wall, I decided to search for help.
I found a link to a codepen solution, copied it and went through it line for line to understand the logic behind the solution. After getting a basic understanding of it,
I went to work on my own. I crafted two different solutions. [Symmetric Difference 1](https://github.com/Chiamaka/Freecodecamp/blob/master/advancedAlgos/Symmetric%20Difference.js) [Symmetric Difference 2](https://github.com/Chiamaka/Freecodecamp/blob/master/advancedAlgos/Symmetric%20Difference%202.js)
I also went past an hour today. I really wanted to have this in the bag. I spent 2+ hours solving this.
Until tomorrow. Kisses  
**Feeling**: My confidence level is growing really well. I'm excited about that

##January 5 2017
**Update**: I traveled back to Lagos. Plus I am sick. I did try to put in an hour but I physically and mentally couldn't. I remember opening my book(where I think) and opening the challenge on FCC and sleeping less than 2 minutes later. LOL. I tweeted that I couldn't do it due to my sickness.

##Day 6: January 6 2017
**Task**: Tried to solve the Exact Change challenge on FCC. I had no idea what the question was asking me to do so I posted about it in my slack group chat and moved on to the next challenge which was [Inventory Change](https://github.com/Chiamaka/Freecodecamp/blob/master/advancedAlgos/Inventory%20Update.js).   
**Learnings**:  
I have no particular learnings per say. The most important thing today was that I solved the challenge in a functional style. I used functional programming precepts in JS and tackled the problem. I wanted to do something different from my normal imperative programming style. It wasn't easy to wrap my head around but ooh boy, my code is so much compact and cleaner after taking this approach. Best part is my boyfriend said the shit was impressive. Hahaha. He is a really good programmer too. We learn from each other.  
**Feeling**: I feel like I'm on cloud 9. I am elated. It feels good to conquer and do so in style.

##Day 7: January 7 2017
**Task**: Did the Fun with Canvas of #JavaScript30.  
**Learnings**: I learnt about the `canvas`, context `cxt` which is where the drawing on the canvas happens, [hsl color range](http://mothereffinghsl.com/). Honestly, I wasn't into today's exercise. It was boring to me but I pulled through so he is cheers to me!!  

##Day 8: January 8 2017
**Task**: Read more on functional programming in JavaScript using this [slide deck](http://scott.sauyet.com/Javascript/Talk/FunctionalProgramming/)  
**Learnings**: Functional programming is a declarative form of coding. It helps you focus on the problem domain and it's easier and more concise to read and debug.  
**Materials**: [Gentle Intro to Funtional Javascript](http://jrsinclair.com/articles/2016/gentle-introduction-to-functional-javascript-intro/)

##Day 9: January 9 2017
**Task**: Lesson 10 of #JavaScript30. Hold Shift to check multiple checkboxes.  
**Learnings**: I was so exhausted yesterday. I really didnt want to do anything but I decided against it. This is a habit building exercise not a when you feel like it exercise so I turned on the tutorials and buckled down. I learnt about the `e.shiftKey`, I learnt about how to check a box dynamically using JS. I didnt really understand how the exercise achieved what it did i.e checking all the rows in between the first checked box and the second checkbox + the shift key pressed down. I fucked with it but still didnt really understand it. I was too tired so I left it. Sorry :(  

##Day 10: January 10 2017
**Task**: No predefined task today. I just did alot of HTML and CSS.  
**Learnings**: Today, I realised that my HTML and CSS skills were not as bouyant as I thought they were. I have always relied on CSS frameworks like bootstrap and Semantic UI to help me out when I'm in a rot but just like when I decided to do everything with vanilla JS, I decided against using a CSS Framework and guys, it was hell. I was so upset and how little I knew CSS to be exact. It fucking sucks. In anger and pure determination, I decided to buy a course on Udemy. A course that thoroughly explains HTML5 and CSS3. This was my first time buying a course on Udemy and it cost $10 cos of the udemy promo that is ongoing. I intend to use that course to sharpen my design skills and take my frontend career to the next fucking level. No more beginner shit.  
1. I did a lot of flexbox stuff today. Watched alot of the [What the Flexbox](https://flexbox.io) videos.
2. I learnt about the `box-sizing` property today. I usually see it in people's code but I never really knew what it was about until today. When you have a box model, if you use the `width` property an element, the element actually becomes bigger than you intended for it to be. To solve this problem, `box-sizing` was introduced. I know I have encountered this problem many times so getting to understand this concept was awesome today. I used [this]('http://learnlayout.com/box-model.html')  
**Feeling**: I kind of feel overwhelmed at the numerous things that I do not understand yet. It feels like a herculian task but I will continue going a step at a time, a day at a time. By June, I would really love to access myself and see how far I have come from the beginning of the year. My main objective for this year; **Move from the damn beginner level to Intermediate level**
