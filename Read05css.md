[Home](https://bproorda.github.io/learning.journal/)

# CSS and Colors ##

- ### What is CSS ###
      - CSS sets rules for the HTML elements should appear
        - can include such items, as color, background, font style, font decoration, border and many more
      - Works by putting an box around every HTML element
      - uses a selector indicating which element and a declaration saying how the element should be styled
        > selector { Declaration;}
        - inside the declaration there is the propery being changed and the value it is being changed to.
            >selector { property: value;}
            > p {font-size: 12px;}

- ### Linking to CSS stylesheet ###
      - When using a file separate from the html page, and you should, you use link element to connect the two
        > ```<link href="css/styles.css" type="text/css" rel="stylesheet" />```
        - href: specifies the path to the file
        - type: specifies type of document
        - rel: specifies the relation between the two pages
      - If you are placing the CSS code *inside* the html, use the style tags
        > ```<style type="text/css"></style>```

- ### CSS Selectors
      - used to target individual elements
      - case sensitive
      - **universal selector** ```*```
          - will target *all* the elements on page
      - **type selector** h1, h2, h3 etc {}
            - use commas to select multiple types
      - **class selector** .class {}
      - **ID selector** #ID {}
      - **Descendant selector** p a {}

- ### Cascade Rules
      - last rule resests previous.
        - if change the font color to red in one line, then below it you change it blue, the final color will be blue
      - The more specific selector trumps the less specific
        >``` p a {} trumps p {} ```
      - you can also mark a rule as important !


## Colors ##      
