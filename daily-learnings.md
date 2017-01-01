
##Day 1: December 31 2016
**Today's Update**: Flexbox working using [Flexbox Patterns](http://www.flexboxpatterns.com/home) and some vanilla JavaScript for interaction.

##Day 2: January 1 2017

**Learnings**:
1. Arrays are reference types so 
    ```const a = [], b = x;
        a === b
    ``` will return true AND
    ```
        const a = [1,1+1], b = [1,2];
        a===b
    ``` will return false
2. New way to extract elements from an array. **Destructuring**. Its a reversal of the usual array literal creation method. Place the template on the left and the array to be picked apart as the value on the right.
3. Extracting arrays from arrays is known as gathering. Using `...` to destructure is gathering, using it in a literal to insert elements is called spreading.
```
    const array = [1,2,3,4,5]
    const [a, ...rest] = array; //gathering
    const spread = ['0', ...array]; //spreading
```
4. Recursive algorithms follow the 'divide and conquer' strategy for problem solving.
5. Note to self; think of `...` in spreading as removing the [] from the passed array to reveal its true nature.
    