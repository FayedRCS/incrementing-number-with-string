# incrementing-number-with-string
Wanted to see if I could write out a string multiple times, with a number next to it counting each increment
-------------------

I was writing a detailed new years resolution(I know, this should be done before the actual new years), When i strumbled upon an issue. In my Google Docs document, I wanted to keep track of each week in 2023 and put a checkbox next to it to mark off if I hit the goal for the select weeek. I was manually writing "Week 1:", "Week 2:",
"Week 3:", etc. When it occured to me, that I definitely could find an easier way to do this. Instead of writing the same string 52 times, I decided that I probably could write a loop in JavaScript to do this for me

At first glance I tought this would quite easy, but it turned out to be a little tricky. I tried to write the code completely by myself and find the best method to do this, without the need of extrenal help. I did read some documentation to remind me of the the syntax in JavaScript, along with some other methods.
# After trying a few different methods, I decided that I was confident enough to use a while loop and came up with the following code:

    var howManyLoops = 0;
    var initNum = 1 //The value of 1 can be changed depending on what the starting number should be

        var loops = function(){

            while(howManyLoops < 52){ //Number in here decides amount of times to print out
    
                console.log ("Week " + initNum + ": "); //Can edit the string inside here. 
                howManyLoops++;
                num++;
               }
        };
    
    loops();


## Happy to see i could solve a real life issue, using just the small amount of JavaScript knowledge I had obtained recently.

🦊🦊🦊

