# Example Exercise

This exercise builds on the previous one, by building a contact form in the contact page using flexbox.

The primary objective in this exercise is to understand:
1. Practice using Flexbox
2. Learn about HTML elements and attributes used to create forms

in the contact.html...
copy and paste the HTML from the gallery.html
remove everything that is inside the content section
add a <form> element inside the content section
add a class "contact-form" to the form element

add <h2>Contact Us</h2> inside the form
add two <div> with class="form-group" after the <h2>
add a <button> after those two <div>
add the text content of "Submit" to the button
give the <button> a type="submit" attribute

add a contact.css file to the css/
copy paste the CSS from flexboxes.css into contact.css
reformat the CSS in contact.css to fix indentations
remove the panel-a style declarations, except the button ones
remove the panel-b style declarations

in the contact.html, link contact.css instead of flexboxes.css

in main.css add a style declaration for buttons in general
cut and paste the styling of button from contact.css to main.css, except the display property
move the button:hover style declarations to main.css as wel;

back in contact.css, add .contact-form {} with:
  flex: 1;

add .contact-form h2 {} with:
  margin-bottom: 20px;
  text-align: center;

add .form-group {} with:
  margin-bottom: 20px;
  display: flex;
  flex-direction: column;

back in the HTML, contact.html:
inside the first <div> which has the "form-group" class, add an <input> element;
add an id="name" to that <input>
add name="name" to that <input>
add a required attribute to that <input>
and add placeholder="Name" to that <input>

after that <input>, add another one with:
  type="email"
  id="email"
  name="email"
  placeholder="Email"

in the second <div> which has the "form-group" class, add a <textarea> element;
give it a name attribute of "message"
give it an id of "message"
remove the cols attribute and change the rows to 4
add a required attribute
and add placeholder="Message"

back in contact.css, after the .form-group declarations, add grouped selectors:
.form-group input[type="text"],
.form-group input[type="email"],
.form-group textarea { }

in there, add the CSS:
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #ddd;
    border-radius: 4px;

after that, add .form-group textarea {} with:
  resize: vertical;

change button {} to button[type="submit"] {}
and add the CSS to it:
  transition: background-color 0.3s ease;

