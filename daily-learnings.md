
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
2. I learnt about the `box-sizing` property today. I usually see it in people's code but I never really knew what it was about until today. When you have a box model, if you use the `width` property an element, the element actually becomes bigger than you intended for it to be. To solve this problem, `box-sizing` was introduced. I know I have encountered this problem many times so getting to understand this concept was awesome today. I used [this](http://learnlayout.com/box-model.html)  
**Feeling**: I kind of feel overwhelmed at the numerous things that I do not understand yet. It feels like a herculian task but I will continue going a step at a time, a day at a time. By June, I would really love to access myself and see how far I have come from the beginning of the year. My main objective for this year; **Move from the damn beginner level to Intermediate level**

##Day 11: January 11 2017
**Task**: Read about Self similarity, Linear recursion, rest params in JavaScript Allonge.  
**Learnings**: Understood when and how recursive functions are applied. They follow the divide and conquer pattern of solving problems. Take a part of it, solve that part and stick it back into the solution. Another thing is that tail call functions are functions where the last thing that the function does is to call a single function, nothing more.  


##Day 12: January 12 2017
**Task**: Worked through a Udemy course on HTML5 & CSS3. Did so where I could find internet that would support watching videos online without being so noticable to the data amount.  
**Feeling**: Being having some things in my personal life distracting me so I didnt watch for more than an hour like I would have.

##January 13-14 2017
**I didnt know anything, I just read but I still wont count it. For this reason, I have decided to deduct a day from my progress which is day 12 and redo it**

##Day 12: January 15 2017
**Task**: Redo the google mail sign in page with pure HTML and CSS.  [Here is the code](https://github.com/Chiamaka/HTML-CSS-challenge/tree/master/Google%20SignIn)
**Learnings**: Been reading [Ire's Blog](https://bitsofco.de). I have learnt alot about meta tags, charset, viewport, css font sizes. So I decided to willingly incorporate what I have learnt from reading the blog into my code. I made use of `rem` units which is better than `em` because it uses the base font that you specified in the `html` tag. Its very great for controlling font sizes in responsive modes. I also used `flexbox` to arrange the elements on the page further consolidating my understanding of it. It really is fun and easy to use.
**Feeling**: I feel really good. I want to up my HTML and CSS game and I believe I'm on the right track. It might seem like its trivial but repetition and continuity makes perfect.

## January 16-17 2017
I was indisposed. I traveled.

##Day 13: January 18 2017
**Task**: I continued practising my HTML and CSS. I am recreating the GoDaddy Sign In page.
**Learnings**: I didnt get to finish today but I continued to use practises like `rem`, `flexbox`, html first; creating all the elements then using css to make it beautiful. This might not seem like anything now but I know that I am consciously beefing up my HTML & CSS skills which is a main requirement for being a front-end developer.
**Feeling**: I was feeling a bit frustrated with positioning some elements on the page but I decided to skip over it and come back to it later. Woah, I have really improved in my touch typing skills. Mad!! I am thinking of doing a 10 day/30 day challenge just doing HTML and CSS recreations. I dont know if 30 days is too much or naa.

## Day 14: January 19-20 2017
I'll be grouping these two days together because I dont feel like I did enough stuff. I continued on the GoDaddy Sign In page. I actually finished it. Also styled for mobile view. It was tough but damn, it was fun. [Here is the code](https://github.com/Chiamaka/HTML-CSS-challenge/tree/master/GoDaddy)

## Day 15-16: January 21-22 2017
I continued with my Udemy course on HTML5 and CSS3. Learnt a few new Bracket tricks using `Ctrl + E` on a tag in the html file to seamlessly add CSS rules and using the same `Ctrl + E` on a color to bring up the color picker. I really am enjoying using Brackets for html and css coding.  
**Learnings**:  
1. To center a div with CSS, you set the `margin-left` and `margin-right` to `auto`.  
### Typography  
2. Use a `font-size` between 15 and 25 pixels for body text.  
3. Use really big font sizes for headlines. When using a very big font size, drop the font weight.  
4. Use line spacing of 120%-150% of the font size.  
5. 45 to 90 characters per line is optimal and aids reading.  
6. Use only one font.  

### Colors  
1. Use only one base color. Tools: [FlatUIColors](https://flatuicolors.com/), [Different Shades of a color](http://www.0to255.com/)  
2. Use a tool like [Adobe Color CC](https://color.adobe.com/) if you want to have multiple colors on your site  
3. Never use the color black.  
4. Use color to draw attention.  

### Images  
1. Overlay the image with a color if both the image and the photo are bright.  
2. Put text in a box makes texts on images easy to read. The box should be opaque so that the image can still be seen underneath.  
3. Blur the image underneath the text and make sure the text stays on the blurred part on all text resolutions.  
4. Floor fade. Here, the images fades to black at the bottom where the text will be.  

### Icons  
1. Use icons to show features of your site/product OR steps to achieve something.  
2. Use icons for actions and links. Rules to be followed are; Icons should be immediately recognizable & Label the icons.  
3. Icons should not take center stage in your design. They should instead play a supporting role.  
4. Use icon fonts i.e Vector icons.  

### Spacing and layout  
1. Put whitespace between elements, group of elements, website's sections BUT do not exaggerate cos that can lead to a loss of relationship.  
2. Define Hierarchy => Define where you want your users to look first. Establish a flow that corresponds to the content's message. Use whitespace to build that flow.  

### User Experience  
UI is the presentation of a product, the look and feel. UX is the overall experience a user has with a product.
When you see a site you think is beautifully built, ask these 3 questions.  
1. Why do this site look good?  
2. What does this have in common with other good looking sites.  
3. How is it built in HTML & CSS.  

### 7 real-world steps to a fully functional site
1. Define your project  
  * Define the goal of your project eg building your portfolio site  
  * Define your audience eg. Who is the typical user that will visit my site  
  * Design with your goal in audience in mind  
2. Plan out everything    
  * Plan your content carefully: text, images, videos, icons, fonts  
  * Start thinking about visual hierarchy  
  * Define the navigation  
  * Define the site structure if its a bigger project  
3. Sketch your ideas before you begin designing  
  * Get inspired and think about your design  
  * Get the ideas out of your head: sketch your ideas before you start designing  
  * Make as many sketches as you want but dont waste time trying to make them perfect.
  * Never start designing without having an idea of what you want to build.  
4. Design and Develop your website  
  * Design your site using all the tips and technique mentioned above.  
  * Do your design in the browser using HTML & CSS.   
  * Use sketches, content and planning decisions you've made in steps 1, 2, 3.  
5. Optimization  
  * Optimize performance: site speed.  
  * Search engine Optimization(SEO)  
6. Launch your masterpiece  
  * All you need is a webserver that will host your website and deliver it to the world.  
7. Site Maintenance  
  * Launching is not the end of the journey  
  * Monitor your users behaviour and make changes to your site if/when necessary  
  * Update your content regularly: blog  

##Day 17: January 23 2017
**Task**: Started and completed the Instagram Page for the HTML & CSS challenge  
**Learnings**: Today was actually alot of fun. I started and finished the challenge today. I learnt further about fonts in css. The `rem` factor tho. So, my browser is set to 20px because of my eyes. Reading tiny text affects me. The default font size in almost all broswers is 16px. I have been coding with 16px as my base font not knowing that when you are using `rem`, the `r` means root and that root font comes from the broswers font setting. As a front-end dev, you arent in control of that so I'll try something out now and come back and tell you how it went. BRB...
Ok, Im back. What I tried actually worked. So scratch what I said before about you not being in control of the base font. You are. LOL. So why it was rendering different font sizes was because on the root element `html`, I set `font-size: 62.5%`. `font-size:100%` computes to the font-size of your browser. So if the font size of your browser i.e the default font-size is 16px, then `font-size:100% === font-size:16px`. And the same goes for if your browser's font-size is 20px or whatever it is. It will be equal to `font-size:100%`.
So, to make your font-sizes the same regardless of whether a user increased their font-size due to bad eyesight like me or whatever the reason may be, people are real weird.  All you need to do is set `font-size: [number]px` on the `html` element. Substitute [number] for any number you think you wanna use. As for me, I'ld be using 10px cos its way way easier to reason about. I've always wanted to use that in a sentence. LOL.
This [article](https://webdesign.tutsplus.com/tutorials/comprehensive-guide-when-to-use-em-vs-rem--cms-23984) helped me really understand what was going on with my browser rendering different font-size from what I set.
This [code snippet](http://codepen.io/mcnitt/pen/ubjHk?editors=0010) helped me write the JS code to loop through the images on the phone layout infinitely. If you notice, it never stops. The cycling of the images. I think I would write a blog post about that.
See you tomorrow. Ciao.
