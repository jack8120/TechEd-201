# Read 03







# Lab 03

**Q1**
As a user, I would like to view a series of data related to the site owners interest so that the I can quickly view more information about them.
Create a “Top Ten” at the bottom of your HTML page as an ordered list in HTML. 

  Added "Top ten favourite guitar solos" as an ordered list at bottom of html page. as e.g. below but for ten items.
  
  ```
   <ol>
       <li>All Along the Watchtower - Jimi Hendirx</li>
       <li>Beat it - Eddie Van Halen (Michael Jackson)</li>
       
   </ol> 
   
   ```


Convert your work experience and education summary into an unordered list using HTML.

Education summary was aleady an <ul> so converted work experience paragraph into an <ul> by dividing paragraph into sentences and displaying as a list. 
  
  
**Q2**  
*As a user, I would like to be guided to an answer through a series of feedback responses so that I can learn more about the site owner.
Add a 6th question to the guessing game that takes in a numeric input by prompting the user to guess a number.*
  
Added a prompt requesting a numerical input - "Guess my lucky number between 1 - 100" and presented as a button. Input box in prompt outputs a string so 
  we used parseInt to convert the string input into an integer. 
  
  ```
  let favnum = prompt("Enter a number between 1-100");
        let favnumguess = parseInt(favnum);
  ```
  
Indicates through an alert if the guess is “too high” or “too low”.
  

  
It should give the user exactly four opportunities to get the correct answer.
After all attempts have been exhausted, tell the user the correct answer. Consider using a loop of some sort.
