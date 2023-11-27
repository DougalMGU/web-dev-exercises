# Example Exercise

This exercise builds on the previous one, by transforming the contact form to work with Grid instead of Flexbox.

The primary objective in this exercise is to understand:
1. Learn about CSS Grid
2. Learn the difference between Flex and Grid

# Instructions

Setup
1. Add a grid.css file to the css/ directory
2. Copy and paste the CSS from contact.css to grid.css (and reformat)
3. Link grid.css instead of contact.css in contact.html

Contact Page CSS
4. In grid.css, to the .contact-form {} declarations add:
  display: grid;
  grid-gap: 1rem;

5. Then add:
  grid-template-rows: auto 1fr 1fr 1fr;

6. Then modify:
  grid-template-rows: auto auto 1fr 1fr;

7. Then modify:
  grid-template-rows: auto auto auto 1fr;

8. Then modify:
  grid-template-rows: auto auto auto auto;

9. Add height: min-content;  to the .contact-form {}

10. Remove margin-bottom: 20px; from the .form-group {}

Contact Page HTML
11. In contact.html, extract the textarea element from the form-group <div> it is in, and delete that <div> (Leave the textarea element directly after the first form-group <div>)

Contact Page CSS
12. Add grid-template-columns: 1fr 1fr; to the .contact-form {}

13. Add grid-column: 1 / -1; to the .contact-form h2 {}

Contact Page HTML
14. In the contact.html, extract the <input> elements from the form-group <div> they are in, and delete that <div>

Contact Page CSS
15. Back in the grid.css, delete the .form-group {}

16. Remove the .form-group from the grouped selectors of the input elements
17. Remove it from textarea too, then add the following to .textarea {}

18. Add 4 columns to .contact-form {}

19. Add input[type="text"] {} with grid-column: 1 / 4;
20. Add input[type="email"] {} with grid-column: 3 / -1;

21. Modify input[type="email"] {} to grid-column: 4 / -1;