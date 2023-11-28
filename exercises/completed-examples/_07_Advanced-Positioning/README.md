# Example Exercise

This exercise builds on the previous one, by modifying the Nav bar to have Fixed positioning.

The primary objective in this exercise is to understand:
1. Learn about Advanced Positioning with Relative positioning
2. Learn about Advanced Positioning with Absolute positioning
3. Learn about Advanced Positioning with Fixed positioning
4. Learn about Advanced Positioning with Sticky positioning

1. Nav bar HMTL
Replace the old Nav HTML with new one
Add <header> under <body>
Add a <div> and a <nav> to the <header>
Add a <h1> to the <div> and give it the "logo" class
Add a <ul> to the <nav> and give it the "menu" class
Add a <li> for each <a> of the menu
Fix the links by adding './' in src
Remove the "contact-item" id from the contact <a>

2. Nav bar CSS
Move the Nav styling from 'inline-blocks.css' to 'main.css' (at the bottom)
Add a 'header' type selector before the '.nav' one and give it display flex
Move the background-color to the header declaration
Remove the display properties from logo, menu, etc.
Move the padding from '.nav' to 'header'
Give the '.menu' a display flex
Remove 'margin-right' from '.menu a'
Add gap of 1rem to '.menu'
Add 'align-items' of 'center' to the 'header'
Add 'justify-content' of 'space-between' to the 'header'
Remove the #contact-item declaration

3. Fixed Nav
In the index.html, duplicate the image twice to add more vertical content to the page
Add position fixed with top and left set to 0 to the 'header'
Add width of 100vw to the header


