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

4. Footer CSS
Add position fixed with top and left set to 0 to the 'header'
Add width of 100vw to the header
Move the Footer styling from 'inline-blocks.css' to 'main.css'
Remove the margin properties that use calc()
Give the <body> display of flex and flex-direction of column
Give the <body> a min-height of 100vh
Remove the display block from '.content' class and give it flex of 1
Give the '.footer' class display of flex with flex-direction column
Give the '.footer' class justify-content of flex-end

5. Dropdown HTML
Give a 'dropdown' class to the <li> of the About <a>
Add a <ul> with class 'dropdown-menu' after the About <a> within the <li>
Add three <li> inside the <ul> each with an <a> "Sublink 1", "Sublink 2", etc.

6. Dropdown CSS
Add a 'dropdown' class selector after the menu selectors in main.css
Give it position relative and display inline-flex
Add a 'dropdown-menu' class selector after, and give it:
  position: absolute;
  top: 100%;
  left: -0.5rem;
  z-index: 1;
  display: none;
  flex-direction: column;
  width: auto;
  background-color: #07121d;
  list-style: none;

After that, add:
.dropdown-menu a {
  display: block;
  padding: 0.5rem;
  color: white;
  text-decoration: none;
  white-space: nowrap;
}

After that, add:
.dropdown:hover .dropdown-menu {
  display: flex;
}

