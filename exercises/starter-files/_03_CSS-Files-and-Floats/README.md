# Example Exercise

This exercise builds on the previous one, by modifying the about page to work with floats instead of inline-blocks, and using multiple CSS files instead of one.

The primary objective in this exercise is to understand:
1. How floats work and how they differ from blocks and inline-blocks
2. How to work with multiple .css files


# Instructions

1. CSS Directory
Add a css/ directory at the root of the project

2. main.css
Add a main.css file in the new css/ directory
Copy and paste the following style declarations from the styles.css file to main.css:
    the custom font import (if you have one)
    the browser reset declarations made with the universal selector
    the root html {} declarations
    the body declarations

3. inline-blocks.css
Add an inline-blocks.css file in the new css/ directory
Copy and paste the rest of the CSS from styles.css to inline-blocks.css

4. floats.css
Add a floats.css file in the new css/ directory
Copy and paste the CSS code from inline-blocks.css to floats.css

5. Linked CSS in Home page
In the index.html file, link the main.css file instead of styles.css
Add a second <link> in the <head> of index.html to link the inline-blocks.css file

6. Linked CSS in About page
In the about.html file, link the main.css file instead of styles.css
Add a second <link> in the <head> of about.html to link the floats.css file

7. Linked CSS in Gallery page
In the gallery.html file, link the main.css file instead of styles.css
Add a second <link> in the <head> of gallery.html to link the inline-blocks.css file

8. Linked CSS in Contact page
In the contact.html file, link the main.css file instead of styles.css
Add a second <link> in the <head> of contact.html to link the inline-blocks.css file

9. Delete styles.css

10. Nav Overflow in floats.css
In the floats.css file, add overflow: auto; to the .nav class

11. Float Logo in floats.css
In the floats.css file, remove display: inline-block and add float: left; to the .logo class declaration

12. Menu in floats.css
In the floats.css file, add float: right; to the .menu class

13. Menu <a> in floats.css
In the floats.css file, remove display: inline-block and add float: left; to the .menu a class-type declaration

14. Content in floats.css
In the floats.css file, add overflow: auto; to the .content class declaration

15. Image in floats.css
In the floats.css file, remove display: inline-block and add float: left; to the .image class declaration

16. .text-content in floats.css
In the floats.css file, remove the display: inline-block from the .text-content class declaration

17. About Page HTML format
Right-click the HTML code of about.html and select 'Format Document'
This should add line breaks and indentation between the <span> and <a> elements which were previously inline-block elements. (avoid white spaces between inline and inline-block elements in HTML)

18. Adjusting Line Spacing CSS
Copy and paste the .title-space declaration from inline-blocks.css into main.css and set its bottom margin to 1rem;
Copy and paste the .line-space declaration from inline-blocks.css into main.css and set its bottom margin to 1.5rem;
Remove the .title-space declaration from both inline-blocks.css and floats.css
Remove the .line-space declaration from both inline-blocks.css and floats.css
Add a new .p-space declaration in main.css right after .line-space, and set it to have bottom margin of 3rem.

19. Adjusting Line Spacing HTML
Change the second <p> in index.html, about.html, gallery.html, and contact.html to have p-space class instead of .line-space or .title-space

20. Adjust Typography of About Page
In floats.css, right after the .text-content declaration, add a new .text-content p  declaration which has:
    font size of 1.5rem;
    line height of 1.3;
    text align set to justify.

21. Add Lorem Ipsum Text to About page
Add 3~5 more Lorem Ipsum sentences to the first <p> in about.html
Duplicate the first <p> in about.html (so there are three <p> now)

22. Adjust Text Content CSS of About page
Remove the width and left padding from the .text-content declaration in floats.css

23. Adjust Image Margin in About page
Add 2rem of right margin to the image element in floats.css

# Checkpoint
Your About page should now look similar to the other pages, but have more text wrapping under the image. The about page is now setup to have a similar layout but using floats instead of inline-blocks.