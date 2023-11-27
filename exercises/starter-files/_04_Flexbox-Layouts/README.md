# Example Exercise

This exercise builds on the previous one, by modifying the gallery page to work with flexboxes instead.

The primary objective in this exercise is to understand:
1. How flexboxes work and how they differ from blocks, inline-blocks, and floats


# Instructions

1. Gallery Page HTML
Wrap the <img> and the "text-content" <div> elements inside of another <div>.
Add the class "panel-a" to the new parent <div> (which should be direct child of "content").
Add another <div> with class "panel-b" after the "panel-a" one, both should be direct children of "content".
Replace the two <p> with the three from the about page (copy paste).

2. Flexboxes Layout CSS File
Add a new CSS file called 'flexboxes.css' in the css/ directory.

3. Link Flexboxes CSS in HTML
In the <head> of the gallery.html file, swap inline-blocks.css for the new flexboxes.css file.

4. Flexboxes Layout CSS Setup
Copy and paste the CSS code from floats.css into the new flexboxes.css file.


In the flexboxes.css file...

5. Nav Element CSS
Change the nav element to have display of flex.
Remove the overflow declaration from the nav element.
Add justify-content of space-between to the nav element to push its children (logo and menu) to the sides.
Add align-items of center to the nav element to center the logo and menu horizontally.

6. Logo Element CSS
Remove the float declaration from the logo element.

7. Menu Element CSS
Remove the left margin and float declarations from the menu.
Add a display of flex to the menu.

8. Menu Anchors CSS
Remove the float declaration from the menu anchors (.menu a)
Remove the right margin declaration as well.

# Checkpoint
Your nav bar element should now be a flex box, as well as the menu that is inside it.

9. Contact-item
In the gallery.html file, remove the id="contact-item" from the contact element.
Back in the flexboxes.css file, remove the #contact-item declarations.

10. Menu Element CSS
Add justify-content of space-between to the menu.
Add gap of 20px to the menu.

11. Content Element CSS
Change the display of the content element to flex.
Replace the current overflow property of the content element with overflow-y of auto.
Add gap of 3rem to the content element.

12. Panel A CSS
Right after the content declarations, give a flex of 2 to the element with class of panel-a.

13. Floated Image CSS
Change the .image selector to be .panel-a > img 

14. text-content CSS
Remove the .text-content declarations.

15. Panel B HTML
In the HTML (gallery.html), copy the image <img> element that is in panel-a, and paste 6 copies inside panel-b.

16. Panel B CSS
Back in the flexboxes.css file, before the footer declarations, add a .panel-b declaration.
Give the panel-b class a flex of 1.
Give the panel-b class a display of flex.
Give the panel-b class flex-wrap of wrap.

17. Panel B Image Elements' CSS
Add a  .panel-b > img  selector right after the panel-b one.
Give the panel-b images a max-width of calc(50% - 1rem).

18. Panel B CSS
Give the panel-b class a gap of 1rem.
Give the panel-b class a justify-content of center.
Give the panel-b class an align-items of flex-start.

19. Panel B CSS
Give the panel-b class a height of min-content.

# Checkpoint
Your content area is now a flex container with two panels. Panel A still has the floated image, but panel b is also a flex container with more images.