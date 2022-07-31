# How the Web Works and Introduction to HTML, CSS and Javascript

Hot the web works - what happens when you search for something on a browser?

[How the web works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)

[Website Design and Process](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)

[Javascript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)


*Compose a short poem describing how HTTP sends data between computers.*

## The after taste of progress

*peruses the menu... 
"I'll have the twitter website please" the waiter (TCP/IP) rolls his eyes  
"That order comes with either existential threat or cats?" he says  
"I'll take the cats"  
"and what pronouns would you like with that?"  
The order is assigned a number and sent to the kitchen, the "chef" (DNS) sneers at the choices made and barks orders at the kitchen staff  
piece by piece the ingredients are found and assembled by HTML, CSS Deals with the presentation,   
"SERVICE" (200 OK) Screams the chef.   
the waiter delivers the order.  
condiments are chosen, temperatures are tested (JS) and content is consumed.*  


*Describe how HTML, CSS, and JS files are “parsed” in the browser.*

HTML is parsed first so the browser can find any links or script tags calling external style sheets and Javascript files from the server. 
Browser generates...
  - In Memory DOM tree is generated 
  - In Memory CSSOM tree is generated 

Compiles and executes parsed javascript. A visaul representatio of he site is displayed on the screen. 

*How can you find images to add to a Website?*

Search using Google images. be aware of copywrite restrictions. 

*How do you create a String vs a Number in JavaScript?*

A string has quotation marks around it a number does not. 

*What is a Variable and why are they important in JavaScript?*

A variable is a container which can be assigned a value using let or const. (var was used until 2015 but is now defunct)  
These values can then be called for use in other parts of teh program such as functions.



# Introduction to HTML


*What is an HTML attribute?*

An attribute contains extra information that will not appear in the content but will effect it in some way.  
e.g. a class attribute can be used to apply styling to an element. 

An attribute should have:

- A space between it and the element name. (For an element with more than one attribute, the attributes should be separated by spaces too.)
- The attribute name, followed by an equal sign.
- An attribute value, wrapped with opening and closing quote marks.

*Describe the Anatomy of an HTMl element.*

![HTML Element Anatomy](https://github.com/jack8120/TechEd-201/blob/main/htmlElementAnat.png)

The anatomy of our element is:

- The opening tag: This consists of the name of the element (in this example, p for paragraph), wrapped in opening and closing angle brackets. This opening tag marks where the element begins or starts to take effect. In this example, it precedes the start of the paragraph text.
- The content: This is the content of the element. In this example, it is the paragraph text.
- The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This marks where the element ends. Failing to include a closing tag is a common beginner error that can produce peculiar results.  

The element is the opening tag, followed by content, followed by the closing tag.


*What is the Difference between `<article>` and `<section>` element tags?*
  
` The <section> tag: `
  
The section tag defines sections in a document, such as chapters, headers, footers, or any other sections of the document.  
  
` The <article> tag: `

The article tag specifies independent, self-contained content.

An article should make sense on its own and it should be possible to distribute it independently from the rest of the site.

Potential sources for the article element:

- Forum post
- Blog post
- News story
- Comment  
  
    
*What Elements does a “typical” website include?*

HTML elements of a typical webpage;
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>My test page</title>
  </head>
  <body>
    <p>This is my page</p>
  </body>
</html> 
```
`<!DOCTYPE html>:` The doctype is a historical artifact that needs to be included for everything else to work right.   

`<html></html>:` The `<html>` element. This element wraps all the content on the page. It is sometimes known as the root element.

`<head></head>:` The `<head>` element. This element acts as a container for everything you want to include on the HTML page including keywords and a page description that would appear in search results, CSS to style content, character set declarations.

`<meta charset="utf-8">:` The `<meta>` element. This element represents metadata that cannot be represented by other HTML meta-related elements, like `<base>, <link>, <script>, <style> or <title>.` The charset attributes sets the character set for your document to UTF-8, which includes most characters from the vast majority of human written languages. 

`<title></title>:` The `<title>` element. This sets the title of the page, which is the title that appears in the browser tab the page is loaded in. The page title is also used to describe the page when it is bookmarked.

`<body></body>:` The `<body>` element. This contains all the content that displays on the page, including text, images, videos, games, playable audio tracks, or whatever else.


How does metadata influence Search Engine Optimization?
How is the <meta> HTML tag used when specifying metadata?
Miscellaneous

How to start to design a Website.

What is the first step to designing a Website?
What is the most important question to answer when designing a Website?
Semantics.

Why should you use an <h1> element over a <span> element to display a top level heading?
What are the benefits of using semantic tags in our HTML?
What is JavaScript?

Describe 2 things that require JavaScript in the Browser?
How can you add JavaScript to an HTML document?
If you have any questions or comments from the readings, record them in your Reading Notes!
  
