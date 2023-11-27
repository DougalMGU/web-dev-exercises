# Example Exercise

This exercise builds on the previous one, by adding separate pages and showcasing navigation between different web pages.

The primary objective in this exercise is to understand:
1. How to build separate pages in the same web project
2. How to link the web pages and navigate between them
3. Highlighting the current page on the nav menu


# Instructions

1. Pages Directory
Add a pages/ directory at the root of the project

2. About Page
Add an about.html file in the pages directory;
Copy the HTML code from index.html into the about.html file;
Change the title from "Home" to "About";

3. Link About in Home page
Replace the "#" of the href attribute for the About anchor element <a> in index.html with the path to the about.html file.

4. About Page CSS
The path to the styles.css file that is specified in the href attribute of the <link> element in the about.html file is broken. Fix it by adding ../ 

5. About Page Image
The path to the image file that is specified in the src attribute of the <img> element in the about.html file is broken. Fix it by adding ../

6. Change Image in About Page
Get a different image and set a different image for the about page.

7. Link Home in About Page
Replace the "#" of the href attribute for the Home anchor element <a> in about.html with the path to the index.html file. This requires the path to have ../ because it is at the root.

# Checkpoint
You should be able to click on 'About' in the nav menu and notice that you are now in the About page, and then return to 'Home'.

8. Gallery Page
Add a gallery.html file in the pages directory;
Copy the HTML code from index.html into the gallery.html file;
Change the title from "Home" to "Gallery";

9. Link Gallery in Home page
Replace the "#" of the href attribute for the Gallery anchor element <a> in index.html with the path to the gallery.html file.

10. Gallery Page CSS
The path to the styles.css file that is specified in the href attribute of the <link> element in the gallery.html file is broken. Fix it by adding ../ 

11. Gallery Page Image
The path to the image file that is specified in the src attribute of the <img> element in the gallery.html file is broken. Fix it by adding ../

12. Change Image in Gallery Page
Get a different image and set a different image for the gallery page.

13. Link Home in Gallery Page
Replace the "#" of the href attribute for the Home anchor element <a> in gallery.html with the path to the index.html file. This requires the path to have ../ because it is at the root.

14. Link About and Gallery Pages
Replace the "#" of the href attribute for the About anchor element <a> in the gallery.html file with the path to the about.html file. 
Similarly, replace the "#" of the href attribute for the Gallery anchor element <a> in the about.html file with the path to the gallery.html file. 

# Checkpoint
You should be able to navigate back and forth between Home, About, and Gallery pages. And notice different images on each page, as well as different title on the browser tab.

15. Contact Page
Add a contact.html file in the pages directory;
Copy the HTML code from index.html into the contact.html file;
Change the title from "Home" to "Contact";

16. Link Contact in Home page
Replace the "#" of the href attribute for the Contact anchor element <a> in index.html with the path to the contact.html file.

17. Contact Page CSS
The path to the styles.css file that is specified in the href attribute of the <link> element in the contact.html file is broken. Fix it by adding ../ 

18. Contact Page Image
The path to the image file that is specified in the src attribute of the <img> element in the contact.html file is broken. Fix it by adding ../

19. Change Image in Contact Page
Get a different image and set a different image for the contact page.

20. Link Home in Contact Page
Replace the "#" of the href attribute for the Home anchor element <a> in contact.html with the path to the index.html file. This requires the path to have ../ because it is at the root.

21. Link About and Contact Pages
Replace the "#" of the href attribute for the About anchor element <a> in the contact.html file with the path to the about.html file. 
Similarly, replace the "#" of the href attribute for the Contact anchor element <a> in the about.html file with the path to the contact.html file. 

22. Link Gallery and Contact Pages
Replace the "#" of the href attribute for the Gallery anchor element <a> in the contact.html file with the path to the gallery.html file. 
Similarly, replace the "#" of the href attribute for the Contact anchor element <a> in the gallery.html file with the path to the contact.html file. 

# Checkpoint
You should be able to navigate back and forth between Home, About, Gallery, and Contact pages. And notice different images on each page, as well as different title on the browser tab.

23. (Bonus Step) Current Page CSS Trick
In the styles.css file, immediately after the #contact-item declaration (which should be after the .menu declarations), add the following selector combinator:

    .menu a.current {}

and inside of it change the color to something different from white but still light colored such as cyan or pink.

24. (Bonus Step) Current Page CSS Trick - Home
In the index.html, add the class "current" to the anchor element <a> that is for the Home link.

25. (Bonus Step) Current Page CSS Trick - About
In the about.html, add the class "current" to the anchor element <a> that is for the About link.

26. (Bonus Step) Current Page CSS Trick - Gallery
In the gallery.html, add the class "current" to the anchor element <a> that is for the Gallery link.

27. (Bonus Step) Current Page CSS Trick - Contact
In the contact.html, add the class "current" to the anchor element <a> that is for the Contact link.

# Checkpoint
When navigating between the pages, you should notice the menu item for the page you are on has a different color.