# HTML Links, JS Functions, and Intro to CSS Layout

[Learn HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML)

[Creating Hyperlinks](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)

**To create a basic link, we wrap text or other content inside what element?**

Basic links are wrapped inside an [`<a>` or anchor element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a).
Combined with it's `href` attribute the <a> tag creates a hyperlink.

**The `href` attribute contains what information?**
  
The `href` attribute contains the URL that the hyperlink points to. This can be
  - another webpage
  - a particular section of the same or another webpage
  -media files
  -contact information such as an email or telephone number
  
**What are some ways we can ensure links on our pages are accessible to all readers?**
  
Making sure links are obvious helps users to undersatnd what they can expect when clicking in your link. 
Rather than turning the words `click here` into a link you can wrap the descritpion of the link destination in the anchor tag making it clear what will happen when the link is clicked, e.g.
  

```
  <p>
  Learn more about our products <a href="/products">here</a>.
</p>
Strong link text

Luckily, this is an easy fix, and it's actually shorter than the inaccessible version!

<p>
  Learn more <a href="/products">about our products</a>.
</p>
```
  
# [CSS Layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout)
  
**What is meant by [“normal flow”?](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow)**
  
Normal flow is the defult layout of how block and inline elements are displayed on a webpage before being altered with css.  
  
**What are a few differences between block-level and inline elements?**
  
A [Block-level element](https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements) occupies the entire horizontal space of its parent element (container), and vertical space equal to the height of its contents, thereby creating a "block".

Browsers typically display the block-level element with a newline both before and after the element. You can visualize them as a stack of boxes.
  
Where as [Inline elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Inline_elements) are those which only occupy the space bounded by the tags defining the element, instead of breaking the flow of the content.
  
***[Static positioning](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning#static_positioning)*** **is the default for every html element.**
  
See link for details  
  
**Name a few advantages to using absolute positioning on an element.**  
  
Advanatges of [absolute positioning](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning#absolute_positioning) include:

-independance from the normal flow positioning.
-Greater control over the positionong of each element in the context of its parent container.

  
**What is a key difference between fixed positioning and absolute positioning?**  
  
[Fixed positioning](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning#fixed_positioning) fixes the position of an element in the context of the devices viewport (the section of the document visible on the screen at any one time. ensuring the element can still be seen as the content is scrolled through.   
  

