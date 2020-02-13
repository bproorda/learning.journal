[Home](https://bproorda.github.io/learning.journal/)

# Introducing Javascript #

- **What is it**
   - programming language developed to make webpages interactive.
   - it is the behavior layer, where the html is content and css is presentation.
   -written in plain text, does not require complier
    -an interperted language, works and runs entirely in the browser.

- **Linking js to html
    - best way is to have js in a separate file and link it
      > ```<script src="js/add-content.js"></script>```
    - you can also put it directly into the page, like css
      > ```<script></script>```
    - when the browser finds a ```<script>``` element, it will stop and see if it needs to do anything.

- **Objects and Methods**
    - example of _calling_ a method
       >```object.method(parameters);```
       >```document.write('Good Afternoon');```
    - js will run where it is places in html

- # Basic Javascript instruction #
    - each individual instruction, line of code, is a _statement_, highlighted green
    - pink curly brackets indicate a code block, often multiple statements
    - comments
     > //single line comment
     > /*multi line comment */
    - a _variable_ temporarily stores data for use in the script
      - variables must be declared using var
      > var variable-name
      - assign a value with =
      > variable-name = value
    - Data types
     - number
     - string, must in quotes
     - boolean, true or false

