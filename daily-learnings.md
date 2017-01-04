
##Day 1: December 31 2016
**Today's Update**: Flexbox working using [Flexbox Patterns](http://www.flexboxpatterns.com/home) and some vanilla JavaScript for interaction.

##Day 2: January 1 2017
**Task**: Read JavaScript Allonge for 1 hour.  
**Learnings**:  
1.  Arrays are reference types so  
    ```const a = [], b = x;
        a === b
    ``` will return `true` AND
    ```
        const a = [1,1+1], b = [1,2];
        a===b
    ``` will return `false`  
2.  New way to extract elements from an array. **Destructuring**. Its a reversal of the usual array literal creation method. Place the template on the left and the array to be picked apart as the value on the right.  
3.  Extracting arrays from arrays is known as gathering. Using `...` to destructure is gathering, using it in a literal to insert elements is called spreading.  
    ```
        const array = [1,2,3,4,5]
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
