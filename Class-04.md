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
Rather than turning the words `click here` into a link you can wrap the descritpion of the link destination in the anchor tag making it clear what will happen when the link is clicked. 
  
  A sadly common mistake is to only link the words "click here" or "here":

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

