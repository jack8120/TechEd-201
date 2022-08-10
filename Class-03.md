# Read 03







# Lab 03

**Q1**
*As a user, I would like to view a series of data related to the site owners interest so that the I can quickly view more information about them.
Create a “Top Ten” at the bottom of your HTML page as an ordered list in HTML.*

  Added "Top ten favourite guitar solos" as an ordered list at bottom of html page. as e.g. below but for ten items.
  
  ```
   <ol>
       <li>All Along the Watchtower - Jimi Hendirx</li>
       <li>Beat it - Eddie Van Halen (Michael Jackson)</li>
       
   </ol> 
   
   ```


*Convert your work experience and education summary into an unordered list using HTML.*

   Education summary was aleady an <ul> so converted work experience paragraph into an <ul> by dividing paragraph into sentences and displaying as a list. 
  
  
**Q2**  
*As a user, I would like to be guided to an answer through a series of feedback responses so that I can learn more about the site owner.
Add a 6th question to the guessing game that takes in a numeric input by prompting the user to guess a number.*
  
   Added a prompt requesting a numerical input - "Guess my lucky number between 1 - 100" and presented as a button. 
   Input box in prompt outputs a string so we used parseInt to convert the string input into an integer. 
  
     ```
     let favnum = prompt("Enter a number between 1-100");
           let favnumguess = parseInt(favnum);
     ```
  
*Indicates through an alert if the guess is “too high” or “too low”.*
  
  Assigned lucky nimber to 'answer' variable. Alerts triggered using if statement conditions. 
  
  ``` 
           let answer = 67;
    
           if(favnumguess === answer){
            alert("WINNER !!");
           }   

           else if(favnumguess > answer){
            alert("Too High !");
           }

           else{
           alert("Too Low !");}
  ```
  
*It should give the user exactly four opportunities to get the correct answer.*
  
*After all attempts have been exhausted, tell the user the correct answer. Consider using a loop of some sort.*
  
  
#Learn HTML  
  
**When should you use an unordered list in your HTML document?**
  
  
**How do you change the bullet style of unordered list items?**
  
  
**When should you use an ordered list vs an unorder list in your HTML document?**
  
**Describe two ways you can change the numbers on list items provided by an ordered list?**
  
  
#Learn CSS

##The Box Model.

**Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?**
  
  
**List and describe the four parts of an HTML elements box as referred to by the box model.**
  
  
#Learn JS

##Arrays. Operators and Expressions. Conditionals. Loops.

**What data types can you store inside of an Array?**
  
**Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?**


`const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];`
  
**List five shorthand operators for assignment in javascript and describe what they do.**
  
  
  
**Read the code below and evaluate the last expression and explain what the result would be and why.**
```
 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;
  ```
  
  
**Describe a real world example of when a conditional statement should be used in a JavaScript program.**
  
**Give an example of when a Loop is useful in JavaScript.**  
