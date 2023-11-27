# Example Exercise

This exercise showcases how to build a simple web page that has a navigation bar, a content area, and a footer, using only elements with block, inline, and inline-block display setting.

The primary objective in this exercise is to understand:
1. How block, inline, and inline-block elements behave
2. How to layout HTML elements and content in the DOM
3. How to apply some basic styling via external CSS
4. Familiarize with basic and common HTML elements and styling properties

# Instructions

1. HTML Boilerplate
Create an index.html at the root of the project, and insert boilerplate HTML5 code

2. Title
Change the default title <title> to "Home Page"

3. Format the Boilerplate
Right-click and select 'Format Document'

4. CSS Setup Part 1
Create a styles.css file in the root of the project; and
Reset the browser default margin and padding to 0 using the universal selector; and
Set the box-sizing property to border-box; and
Ensure the base font size is 16px using the html or root selector.

5. CSS Setup Part 2
In the <head> of the index.html file, embed the CSS code using the <link> element.

6. Page sections
In the <body>, insert: a <div> with a "nav" class, a <div> with a "content" class, and a <div> with a "footer" class

7. Nav section CSS
Use the .nav class selector to give styling to the nav section in the styles.css file:
Give it a block display; and
Give it a dark background color; and 
Give it top and bottom padding of 1rem; and
Give it left and right padding of 2rem.

# Checkpoint
At this point, if you open your index.html in a browser, you should see a dark bar at the top of the page. That's the nav bar section.

8. Logo Element
Inside the <div> with the "nav" class, add a <span> with a "logo" class, and give it the text content of 'LOGO'.

9. Menu Element
Also inside the <div> with the "nav" class, after the <span> with the "logo" class, add another <span> with a "menu" class on it. 

10. Menu Items
Inside the <span> with the "menu" class, add four <a> elements: 
The first <a> will have text content of "Home";
The second <a> text content of "About";
The third <a> text content of "Gallery";
And the fourth and last <a> text content of "Contact";
Give all four <a> an href value of "#";
And give an id of "contact-item" to the fourth and last <a> which has the "Contact" text.

# Checkpoint
Your nav bar should now have the LOGO text as well as the menu links on it.

11. Logo element CSS
Use the .logo class selector to give styling to the logo element in the styles.css file:
Give it display of inline-block;
Give it a width of 100px;
Give it font size of 1.5rem;
Give it bold font;
And give it white color. (the content/text, not the background)

12. Menu Links CSS
Use the combined class and type selectrs: .menu a 
to give style to all the <a> elements in the menu:
Give them display of inline-block;
Give them a right margin of 20px;
Give them text decoration none to remove their underline;
And give them a white color. (the text)

13. Menu Links Visited / Hover / Active
Use the selectors: .menu a:visited / .menu a:hover / .menu a:active 
to change the color of links when they are visited, hover, and active.

14. Last Link Margin
Remove the right margin of the last (fourth) <a> element (Contact);
Using the id selector #contact-item give it a right margin of 0px

15. Menu Left Margin
Push the Menu to the right side of the nav bar by adding margin on its left.
In the styles.css after the .logo declarations and before the .menu a declarations;
Use the .menu selector to give the following left margin to the menu element:

    margin-left: calc(100vw - 4rem - 100px - 274px);

# Checkpoint
The menu on your navbar should now be pushed to the right side, and the links on it should change color when you hover and click on them.

16. Image Asset
Add a directory imgs/ in the root of your project.
Download a square image from Pexels, Unsplash, or Pixabay.
Make sure it is a square image (same width and height).
Put the image inside the imgs/ directory of your project.

17. Embed Image in HTML
In the index.html file, inside the <div> that has the "content" class;
Add an image element <img> and link the imgs/ directory along with your image to its src attribute;
Give it an appropriate short description in the alt attribute;
And give the <img> element a class of "image"

18. Image CSS
In the styles.css, after the #contact-item declaration, add a styling declaration for the image using the .image class selector;
Give the image class a display of inline-block;
A width of 420px;
And vertical align of top.

# Checkpoint
Your content area should now display your image. It should appear up against the top left corner.

19. Text Content Div
In the index.html file, inside the <div> that has the "content" class, and after the image <img> element we just added, add a <div> element with a class of "text-content".

20. Heading Element
Inside of the <div> that has the "text-content" class, add a Heading 1 <h1> element.
Give the <h1> a text/content of "Heading" or whichever heading or title you want.

21. Paragraph Elements
Immediately after the <h1> element (also within the "text-content" <div>) add two Paragraph elements <p> with some Lorem Ipsum placeholder text. One or two sentences each.

22. Button Element
After the second <p> add a Button element <button> with the text/content "Button" on it.

# Checkpoint
You should see a heading, two paragraphs, and a button under the image in the content area.

23. Adjust Position of Text Content
In the styles.css file, use the class selector .text-content to style the text-content element:
Give it a display of inline-block;
Give it vertical-align of top;
Give it padding left of 4rem; 
and give it the following width:

    width: calc(100% - 460px);

24. Line Spacing of Text HTML
In the index.html, add the following classes:
Add a class of "title-space" to the <h1> element, as well as to the second <p> element.
Add a class of "line-space" to the first <p> element.

25. Line Space of Text CSS
In the styles.css file, after the .text-content declaration:
Add margin bottom of 0.75rem to the .title-space class
And a margin bottom of 0.25rem to the .line-space class

# Checkpoint
The heading, paragraphs, and button should now be on the right side of the image, and there should be some spacing between the heading and paragraphs.

26. Content Area Padding
In the styles.css file, right before the .image declaration:
Use the .content class selector to give the following styling to the content element:
Give it display of block;
Give it top and bottom padding of 2rem;
Give it left and right padding of 4rem;
and give it the following height:

    height: calc(100vh - 2rem - 1.5rem - 200px);

# Checkpoint
The content (image, text, and button) of the page, should now have some space around it.

27. Button Styling
In the styles.css file, right after the .line-space declaration:
Use the type selector of button to give the button the following CSS declarations:
Give it a display of inline-block;
Give it top and bottom padding of 0.3rem;
Give it left and right padding of 1.5rem;
Give it a light blue background color;
Give it a border or none;
Give it a border radius of 0.5rem;
Give it a font size of 1.25rem;
Give it a color of white; (text color)
And make the cursor a pointer.

28. Button Hover CSS
Immediately after the aforementioned, add another declaration for button:hover with:
A different background color of your choice such as orange; (make sure it is a light color)
And make the color black. (text color)

# Checkpoint
The button should now look nicer, and react to hovering the mouse on it.

29. Footer Text
In the index.html file, add a paragraph element <p> inside the <div> that has the "footer" class. Put the following text/context in the <p>
"Terms of Use | Privacy Policy"

30. Footer Section CSS
In the styles.css file, add styling for the footer using the .footer class selector:
Give it display of block;
Give it minimum height of 200px;
Give it a dark background color;
Give it top and bottom padding of 1rem;
and left and right padding of 2rem.

31. Footer Paragraph CSS
Use the combined class and type select  .footer p  to give styling to the paragraph <p> that is inside the .footer classed element:
Give it a text align of center;
Give it a white color; (the text)
and the following top margin:

    margin-top: calc(200px - 2rem - 1.5em);

# Checkpoint
Your page should now have a footer section, with text on the bottom center.

32. Custom Font (optional bonus step)
Import a custom font from Google Fonts using  @impot url()  at the top of the styles.css file, and then add a type selector for  body {}  after the  html {}  declaration, and apply the custom font family in the body, with at least one fallback font.
