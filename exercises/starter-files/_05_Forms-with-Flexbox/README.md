# Example Exercise

This exercise builds on the previous one, by building a contact form in the contact page using flexbox.

The primary objective in this exercise is to understand:
1. Practice using Flexbox
2. Learn about HTML elements and attributes used to create forms

# Instructions

Contact Page HTML
1. Copy and paste the HTML from the gallery.html to the contact.html file 
2. Remove everything that is inside the content section
3. Add a <form> element inside the content section
4. Add a class "contact-form" to the form element
5. Add <h2>Contact Us</h2> inside the form
6. Add two <div> with class="form-group" after the <h2>
7. Add a <button> after those two <div>
8. Add the text content of "Submit" to the button
9. Give the <button> a type="submit" attribute

Contact Page CSS
10. Add a contact.css file to the css/
11. Copy paste the CSS from flexboxes.css into contact.css
12. Reformat the CSS in contact.css to fix indentations
13. Remove the panel-a style declarations, except the button ones
14. Remove the panel-b style declarations

Contact Page HTML
15. In the contact.html, link contact.css instead of flexboxes.css

Main CSS
16. In main.css add a style declaration for buttons in general
17. Cut and paste the styling of button from contact.css to main.css, except the display property
18. Move the button:hover style declarations to main.css as well

Contact Page CSS
19. Back in contact.css, add .contact-form {} with:
  flex: 1;

20. Add .contact-form h2 {} with:
  margin-bottom: 20px;
  text-align: center;

21. Add .form-group {} with:
  margin-bottom: 20px;
  display: flex;
  flex-direction: column;

Contact Page HTML
22. In the contact.html file, inside the first <div> which has the "form-group" class, add an <input> element
23. Add an id="name" to that <input>
24. Add name="name" to that <input>
25. Add a required attribute to that <input>
26. And add placeholder="Name" to that <input>

27. After that <input>, add another one with:
  type="email"
  id="email"
  name="email"
  placeholder="Email"

28. In the second <div> which has the "form-group" class, add a <textarea> element
29. Give it a name attribute of "message"
30. Give it an id of "message"
31. Remove the cols attribute and change the rows to 4
32. Add a required attribute
33. And add placeholder="Message"

Contact Page CSS
34. Back in contact.css, after the .form-group declarations, add the grouped selectors:
.form-group input[type="text"],
.form-group input[type="email"],
.form-group textarea { }

35. In there, add the CSS:
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #ddd;
    border-radius: 4px;

36. After that, add .form-group textarea {} with:
  resize: vertical;

37. Change button {} to button[type="submit"] {} and add the CSS to it:
  transition: background-color 0.3s ease;
