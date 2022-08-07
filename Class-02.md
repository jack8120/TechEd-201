# Reviewing basics of HTML, CSS and Javascript.


## Introduction to HTML. 

Reviewing HTML basics before moving on to more advanced concepts. 

**Links for reference** 

[Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)

[HTML text fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)

[Advanced text formatting](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)

**Why is it important to use semantic elements in our HTML?**

Semantic elements carry predefined meaning, function or apearence that help organise your document and provide identifying information to screen readers and serach engines.  

**How many levels of headings are there in HTML?**

There are 6 levels of heading H1 to H6 - to represent main headings (H1) sub headings and sub-sub headings etc. 

**What are some uses for the `<sup> and <sub>` elements?**


  
  
**When using the `<abbr>` element, what attribute must be added to provide the full expansion of the term?**

The title attribute must be added.

```
<p>We use <abbr>HTML</abbr>, Hypertext Markup Language, to structure our web documents.</p>

<p>I think <abbr title="Reverend">Rev.</abbr> Green did it in the kitchen with the chainsaw.</p>
```

#Learn CSS

**What are ways we can apply CSS to our HTML?**

CSS can be applies in 3 ways;

  *inline* - means to add the css to the element with the html being effected. This is only really used for small examples and should be avoided.
  
  An *Internal* style sheet is applieed inside a style tag in the head of the html document as seen below. Can be useful for adding to css while using 
  CMS and are blocked from modifying the external css files. 
  
  ```
   <head>
    <meta charset="utf-8">
    <title>My CSS experiment</title>
    <style>
      h1 {
        color: blue;
        background-color: yellow;
        border: 1px solid black;
      }

      p {
        color: red;
      }
    </style>
  </head>
  <body>
    <h1>Hello World!</h1>
  ```
  
  An *External* style sheet is the best practice approach to applying CSS. this keeps the CSS all together in a file seperate to the html making it easier to read and edit. 
  ```
   <head>
    <meta charset="utf-8">
    <title>My CSS experiment</title>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <h1>Hello World!</h1>
  ```

**Review the block of code below and answer the following questions:**

**What is representing the selector?**
  The H2
**Which components are the CSS declarations?**
  The key value pairs - color:black; and padding: 5px;
**Which components are considered properties?**
  color and padding
 ```
 h2 {
     color: black;
     padding: 5px;
   }
```

#Learn JavaScript

**What data type is a sequence of text enclosed in single quote marks?**

A string

**List 4 types of JavaScript operators.**

plus + 
minus - 
Modulus %
assignment =

**Describe a real world Problem you could solve with a Function.**

simple maths. working out change / shop till.

**Making Decisions In Your Code – Conditionals.**

**An if statement checks a *condition* and if it evaluates to *true*, then the code block will execute.**

**What is the use of an else if?**
  to give the computer instructions on what to do if and if statement is not true.

**List 3 different types of comparison operators.**

== means equal to
=== means equal value and equal type
!= means not equal. 

**What is the difference between the logical operator && and ||?**

  Like logic gates in electronics. 
  && is an AND operator.
  || is an OR operator. 
