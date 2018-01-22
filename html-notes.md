1. The &lt;div&gt; tag defines a division or a section in an HTML document.

   The &lt;div&gt; tag is used to group block-elements to format them with CSS.  
   Tip: The &lt;div&gt; element is very often used together with CSS, to layout a web page.

   Note: By default, browsers always place a line break before and after the &lt;div&gt; element. However, this can be changed with CSS.

2. HTML elements are usually either "block-level" elements or "inline" elements.  
   A block-level element occupies the entire space of its parent element \(container\), thereby creating a "block".  
   Inline elements are those which only occupy the space bounded by the tags defining the element, instead of breaking the flow of the content. &lt;b&gt;, &lt;td&gt;, &lt;a&gt;, &lt;img&gt;, &lt;span&gt;  
   **Formatting**

   By default, block-level elements begin on new lines, but inline elements can start anywhere in a line.

   **Content model**

   Generally, block-level elements may contain inline elements and other block-level elements. Inherent in this structural distinction is the idea that block elements create "larger" structures than inline elements.

3. **Question:**What is doctype? Why do u need it?

   **Answer:**doctype is an instruction to the browser to inform about the version of html document and how browser should render it.

   It ensures how element should be displayed on the page by most of the browser. And it also makes browser's life easier. otherwise, browser will guess and will go to[quirks mode](http://en.wikipedia.org/wiki/Quirks_mode). Moreover, doctype is required to[validate markup](http://validator.w3.org/).

4. **Question:**What are optional closing tag? and why would u use it?

   **Answer:**p, li, td, tr, th, html, body, etc. you don't have to provide end tag. Whenever browser hits a new tag it automatically ends the previous tag. However, you have to be careful to escape it.

   **reason:**you can save some byte and reduce bytes needs to be downloaded in a html file.

5. **Question:**What is the difference between span and div?

   **Answer:**div is a block element and span is inline element.

   **Extra:**It is illegal to put block element inside inline element. div can have a p tag and a p tag can have a span. However, span can't have a div or p tag inside.

6. **Question:**Difference between standard/ strict mode and quirks mode?

   **Answer:**quirks mode in browser allows u to render page for as old browsers. This is for backward compatibility.

7. **Question:**What is semantic HTML?

   **Answer:**Semantic HTML, or "semantically-correct HTML", is HTML where the tags used to structure content are selected and applied appropriately to the meaning of the content.

   for example, &lt;b&gt;&lt;/b&gt; \(for bold\), and &lt;i&gt;&lt;/i&gt; \(for italic\) should never be used, because they’re to do with formatting, not with the meaning or structure of the content. Instead, use the replacements &lt;strong&gt;&lt;/strong&gt; and &lt;em&gt;&lt;/em&gt; \(meaning emphasis\), which by default will turn text bold and italic \(but don’t have to do so in all browsers\), while adding meaning to the structure of the content.

   **Question:**Why you would like to use semantic tag?

   **Answer:**Search Engine Optimization, accessibility, repurposing, light code.

   Many visually impaired person rely on browser speech and semantic tag helps to interpret page content clearly.

   Search engine needs to understand page content to rank and semantic tag helps.

   ref:[why important](http://www.adobe.com/devnet/html5/articles/semantic-markup.html#articlecontentAdobe_numberedheader_0),[Wiki: semantic HTML](http://en.wikipedia.org/wiki/Semantic_HTML)

   **Question:**What does “semantically correct” mean?

   **Answer:**read it in [Stackoverflow](http://stackoverflow.com/questions/1294493/what-does-semantically-correct-mean/1294512#1294512)

8. 


