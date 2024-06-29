# HTML elements have an opening and closing tag with content in between. 

  Example Code
  ```html
  <openingTag>content</closingTag>
  ```

# STEP 1

  The first element you will learn about is the h1 element. The h1 element is a heading element and is used for the main heading of a webpage.

  Example Code:
  ```html
  <h1>This is a main heading</h1>
  ```

  Output:
   <h1>This is a main heading</h1>


# STEP 2

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


# STEP 3

  The p element is used to create a paragraph of text on websites.
  
  ```html
  <p></p>
  ```

# STEP 4

  Commenting allows you to leave messages without affecting the browser display. It also allows you to make code inactive. A comment in HTML starts and ends with 
  ```html
  <!-- stuff --> 
   ```
   and can contain any no of lines of text.


# STEP 5

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


# STEP 6

  In the previous step, you put the h1, h2, comment, and p elements inside the main element. This is called nesting. Nested elements should be placed two spaces further to the right of the element they are nested in. This spacing is called indentation and it is used to make HTML easier to read.

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


# STEP 7

  You can add images to your website by using the img element. img elements have an opening tag without a closing tag. A tag for an element without a closing tag is known as a self-closing tag.

  ```html
  <img>
  ```

# STEP 8
  
  HTML attributes are special words used inside the opening tag of an element to control the element's behavior. The src attribute in an img element specifies the image's URL (where the image is located).

  Here is an example of an img element with a src attribute pointing to the freeCodeCamp logo:

  Example Code
  ```html
  <img src="https://cdn.freecodecamp.org/platform/universal/fcc_secondary.svg">
  ```
  Output:
  <img src="https://cdn.freecodecamp.org/platform/universal/fcc_secondary.svg">


# STEP 9
  
  All img elements should have an alt attribute. The alt attribute's text is used for screen readers to improve accessibility and is displayed if the image fails to load.

  Here is an example of an img element with an alt attribute:

  Example Code:
  ```html
  <img src="cat.jpg" alt="A cat">
  ```
  Output:
  <img src="cat.jpg" alt="A cat">
  

# STEP 10

  You can link to another page with the anchor (a) element.

  Here is an example linking to https://www.freecodecamp.org:

  Example Code:
  ```html
  <a href="https://www.freecodecamp.org"></a>
  ```
  Output:
  <a href="https://www.freecodecamp.org"></a>


# STEP 11

  A link's text must be placed between the opening and closing tags of an anchor (a) element.

  Here is an example of a link with the text click here to go to freeCodeCamp.org:

  Example Code:
  ```html
  <a href="https://www.freecodecamp.org">click here to go to freeCodeCamp.org</a>
  ```
  Output:
  <a href="https://www.freecodecamp.org">click here to go to freeCodeCamp.org</a>


# STEP 12

  You can turn any text into a link, such as the text inside of a p element.

  Example Code:
  ```html
  <p>I think <a href="https://www.freecodecamp.org">freeCodeCamp</a> is great.</p>
  ```
  Output:
  <p>I think <a href="https://www.freecodecamp.org">freeCodeCamp</a> is great.</p>


# STEP 13

  To open links in a new tab, you can use the target attribute on the anchor (a) element.

  The target attribute specifies where to open the linked document. target="_blank" opens the linked document in a new tab or window.

  Here is the basic syntax for an a element with a target attribute:

  Example Code:
  ```html
  <a href="https://www.freecodecamp.org" target="_blank">freeCodeCamp</a>
  ```
  Output:
  <a href="https://www.freecodecamp.org" target="_blank">freeCodeCamp</a>

# Step 14

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
