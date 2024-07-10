# HTML-Dropdown-List

Attributes of the Select Tag
Before I dive deep into whot to create a dropdown menu with the select tag, we need to discuss the attributes the select tag takes.

These are its attributes:

name: You need to attach the name to every form control as it is used to reference the data after it's submitted to the server.
multiple: This attribute lets the user select multiple options from the dropdown menu.
required: This is typically used for validation. With it, the form won't submit unless a user selects at least one option from the dropdown.
disabled: This attribute stops the user from interacting with the options.
size: Expressed in numbers, the size attribute is used to specify how many options will be visible at a time.
autofocus: This attribute is used on all form inputs, select inclusive, to specify that the input should be on focus when the page loads.

The HTML <form> element can contain one or more of the following form elements:

<input>'
'<label>'
'<select>'
'<textarea>'
'<button>'
'<fieldset>'
'<legend>'
'<datalist>'
'<output>'
'<option>'
'<optgroup>'


The <label> Element
The <label> element defines a label for several form elements.

The <label> element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element.

The <label> element also help users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the <label> element, it toggles the radio button/checkbox.

The for attribute of the <label> tag should be equal to the id attribute of the <input> element to bind them together.

