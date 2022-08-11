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
  
  Assigned lucky number to 'answer' variable. Alerts triggered using if statement conditions. 
  
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
  
**It should give the user exactly four opportunities to get the correct answer.**
**After all attempts have been exhausted, tell the user the correct answer. Consider using a loop of some sort.**
  
  ```
  function sixth() {

        for(let i = 0; i<4; i++){

        let favnum = prompt("Enter a number between 1-100");
        let favnumguess = parseInt(favnum);
        let answer = 67;
    
           if(favnumguess === answer){
            alert("WINNER !!");
           }   

           else if(favnumguess > answer){
            alert("Too High !");
           }

           else{
           alert("Too Low !");}

           document.getElementById("favnum").innerHTML = "My lucky number = " + answer;
        }
        
        }
  ```
  

  
  
#Learn HTML  
  
**When should you use an unordered list in your HTML document?**
  
When you want to create a bulletted list which is not numbered. 
  
**How do you change the bullet style of unordered list items?**
  
The bullet style can be changed using the type attribute. 
  
  
**When should you use an ordered list vs an unorder list in your HTML document?**
  
When you want the list items displayed in a specific order.
  
**Describe two ways you can change the numbers on list items provided by an ordered list?**
  
Using the type attribute you can apply different numerals to the entire list. You can also set diffrerent type attributers for each `<li>` element. 

Common numerals include: 

1 a for lowercase letters
2 A for uppercase letters
3 i for lowercase Roman numerals
4 I for uppercase Roman numerals
5 for numbers (default)

  
  
#Learn CSS

##The Box Model.

**Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?**
  
Padding takes care of the space between the content and the border while margin sets the amount of space around the border of the element.  
  
**List and describe the four parts of an HTML elements box as referred to by the box model.**
  
  1 Content
  2 Padding
  3 Border
  4 Margin
  
  
#Learn JS

##Arrays. Operators and Expressions. Conditionals. Loops.

**What data types can you store inside of an Array?**
  
You can store any data type in an array.
  
**Is the people array below a valid JavaScript array? If so, how can I access the values stored? If not, why?**

`const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];`
  
The people array is not valid because it has 2 square brackets at the beginnig where there should be only 1. If it did have only one square bracket the values stored could be accessed using bracket notation and the index as shown below. 
  
```  
const shopping = ['bread', 'milk', 'cheese', 'hummus', 'noodles'];
console.log(shopping[0]);
// returns "bread"  
```
  
**List five shorthand operators for assignment in javascript and describe what they do.**
 
|Name	|Shorthand operator	| Meaning
|------|------------------|------------|
|Assignment|	x = f()	| x = f() |
|Addition assignment	| x += f() |	x = x + f() |
|Subtraction assignment	| x -= f()	| x = x - f() |
|Multiplication assignment |	x *= f() |	x = x * f() |
|Division assignment	| x /= f() |	x = x / f() |
|Remainder assignment	| x %= f()	| x = x % f() |
|Exponentiation assignment |	x **= f()	| x = x ** f()  |
  
  
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
