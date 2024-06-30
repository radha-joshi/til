# HTML elements have an opening and closing tag with content in between. 

  Example Code
  ```html
  <openingTag>content</closingTag>
  ```

# > h1 element

  The first element you will learn about is the h1 element. The h1 element is a heading element and is used for the main heading of a webpage.

  Example Code:
  ```html
  <h1>This is a main heading</h1>
  ```

  Output:
   <h1>This is a main heading</h1>


# > All heading elements

  The h1 through h6 heading elements are used to signify the importance of content below them. The lower the number, the higher the importance, so h2 elements have less importance than h1 elements.

  Example Code:
  ```html
  <h1>most important heading element</h1>
  <h2>second most important heading element</h2>
  <h3>third most important heading element</h3>
  <h4>fourth most important heading element</h4>
  <h5>fifth most important heading element</h5>
  <h6>least important heading element</h6>
  ```
  Output:
  <h1>most important heading element</h1>
  <h2>second most important heading element</h2>
  <h3>third most important heading element</h3>
  <h4>fourth most important heading element</h4>
  <h5>fifth most important heading element</h5>
  <h6>least important heading element</h6>


# > Paragraph element

  The p element is used to create a paragraph of text on websites.
  
  ```html
  <p></p>
  ```

# > Commenting

  Commenting allows you to leave messages without affecting the browser display. It also allows you to make code inactive. A comment in HTML starts and ends with 
  ```html
  <!-- stuff --> 
   ```
   and can contain any no of lines of text.


# > Main

  The main element is used to represent the main content of the body of an HTML document. Content inside the main element should be unique to the document and should not be repeated in other parts of the document.

  Example Code:
  ```html
  <main>
    <h1>Most important content of the document</h1>
    <p>Some more important content...</p>
  </main>
  ```
  Output:
  <main>
    <h1>Most important content of the document</h1>
    <p>Some more important content...</p>
  </main>


# > Nesting

  When you put the h1, h2, comment, and p elements inside the main element. This is called nesting. Nested elements should be placed two spaces further to the right of the element they are nested in. This spacing is called indentation and it is used to make HTML easier to read.

  Here is an example of nesting and indentation:

  Example Code:
  ```html
  <main>
    <h1>Most important content of the document</h1>
    <p>Some more important content...</p>
  </main>
  ```
  Output:
  <main>
    <h1>Most important content of the document</h1>
    <p>Some more important content...</p>
  </main>


# > Img

  You can add images to your website by using the img element. img elements have an opening tag without a closing tag. A tag for an element without a closing tag is known as a self-closing tag.

  ```html
  <img>
  ```

# > Src attribute
  
  HTML attributes are special words used inside the opening tag of an element to control the element's behavior. The src attribute in an img element specifies the image's URL (where the image is located).

  Here is an example of an img element with a src attribute pointing to the freeCodeCamp logo:

  Example Code
  ```html
  <img src="https://cdn.freecodecamp.org/platform/universal/fcc_secondary.svg">
  ```
  Output:
  <img src="https://cdn.freecodecamp.org/platform/universal/fcc_secondary.svg">


# > Alt attribute
  
  All img elements should have an alt attribute. The alt attribute's text is used for screen readers to improve accessibility and is displayed if the image fails to load.

  Here is an example of an img element with an alt attribute:

  Example Code:
  ```html
  <img src="cat.jpg" alt="A cat">
  ```
  Output:
  <img src="cat.jpg" alt="A cat">
  

# > Anchor element (a href)

  You can link to another page with the anchor (a) element.

  Here is an example linking to https://www.freecodecamp.org:

  Example Code:
  ```html
  <a href="https://www.freecodecamp.org"></a>
  ```
  Output:
  <a href="https://www.freecodecamp.org"></a>


# > Linking with a href

  A link's text must be placed between the opening and closing tags of an anchor (a) element.

  Here is an example of a link with the text click here to go to freeCodeCamp.org:

  Example Code:
  ```html
  <a href="https://www.freecodecamp.org">click here to go to freeCodeCamp.org</a>
  ```
  Output:
  <a href="https://www.freecodecamp.org">click here to go to freeCodeCamp.org</a>


# > Text as link

  You can turn any text into a link, such as the text inside of a p element.

  Example Code:
  ```html
  <p>I think <a href="https://www.freecodecamp.org">freeCodeCamp</a> is great.</p>
  ```
  Output:
  <p>I think <a href="https://www.freecodecamp.org">freeCodeCamp</a> is great.</p>


# > Opening links in a new tab

  To open links in a new tab, you can use the target attribute on the anchor (a) element.

  The target attribute specifies where to open the linked document. target="_blank" opens the linked document in a new tab or window.

  Here is the basic syntax for an a element with a target attribute:

  Example Code:
  ```html
  <a href="https://www.freecodecamp.org" target="_blank">freeCodeCamp</a>
  ```
  Output:
  <a href="https://www.freecodecamp.org" target="_blank">freeCodeCamp</a>

# > Image as link

  In previous steps you used an anchor element to turn text into a link. Other types of content can also be turned into a link by wrapping it in anchor tags.

  Here is an example of turning an image into a link:

  Example Code:
  ```html
  <a href="https://www.freecodecamp.org">
    <img src="https://cdn.freecodecamp.org/platform/universal/fcc_secondary.svg">
  </a>
  ```
  Output:
  <a href="https://www.freecodecamp.org">
    <img src="https://cdn.freecodecamp.org/platform/universal/fcc_secondary.svg">
  </a>


# > Sections

  Before adding any new content, you should make use of a section element to separate the cat photos content from the future content.

  The section element is used to define sections in a document, such as chapters, headers, footers, or any other sections of the document. It is a semantic element that helps with SEO and accessibility.

  Example Code:
  ```html
  <section>
    <h2>Section Title</h2>
    <p>Section content...</p>
  </section>
  ```
  Output:
  <section>
    <h2>Section Title</h2>
    <p>Section content...</p>
  </section>


# When you add a lower rank heading element to the page, it's implied that you're starting a new subsection.


# > Unordered list

  To create an unordered list of items, you can use the ul element.


# > li element

  The li element is used to create a list item in an ordered or unordered list.

  Here is an example of list items in an unordered list:

  Example Code:
  ```html
  <ul>
    <li>milk</li>
    <li>cheese</li>
  </ul> 
  ```
  Output: 
  <ul>
    <li>milk</li>
    <li>cheese</li>
  </ul> 


# > Figure element

  The figure element represents self-contained content and will allow you to associate an image with a caption.


# > Figure caption

  A figure caption (figcaption) element is used to add a caption to describe the image contained within the figure element.

  Here is an example of a figcaption element with the caption of A cute cat:

  Example Code:
  ```html
  <figure>
    <img src="image.jpg" alt="A description of the image">
    <figcaption>A cute cat</figcaption>
  </figure>
  ```
  Output:
  <figure>
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTfK2TpU94R0wOqvt-fSY7ucmsKWUK7UDC8fQ&s" alt="A description of the image">
    <figcaption>A cute cat</figcaption>
  </figure>

# > Em element

  To place emphasis on a specific word or phrase, you can use the em element.

  Example code:
  ```html
  <h3>cats <em>love</em> lasagna.</h3>
  ```
  Output:
  <h3>cats <em>love</em> lasagna.</h3>


# > Ordered list

  The code for an ordered list (ol) is similar to an unordered list, but list items in an ordered list are numbered when displayed.

  Example code:
  ```html
  <ol>
    <li>milk</li>
    <li>cheese</li>
  </ol> 
  ```
  Output: 
  <ol>
    <li>milk</li>
    <li>cheese</li>
  </ol> 


# > Strong element

  The strong element is used to indicate that some text is of strong importance or urgent.

  Example code:
  ```html
  <h3>cats <strong>hate</strong> other cats.</h3>
  ```
  Output:
  <h3>cats <strong>hate</strong> other cats.</h3>


# > Form element

  The form element is used to get information from a user like their name, email, and other details.


# > Action attribute

  The action attribute indicates where form data should be sent.

Here is an example of a form element with an action attribute:

Example Code:
```html
<form action="/submit-url"></form>
```
In the example, action="/submit-url" tells the browser that the form data should be sent to the path /submit-url.




