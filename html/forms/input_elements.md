##Example Form Exploration
* Doctype - The <!DOCTYPE> declaration is not an HTML tag; it is an instruction to the web browser about what version of HTML the page is written in.

* HTML - Tells broser that this is an HTML document. It represents the root of an HTML document and is the container for all other html elements.
* Head - Provides general information (metadata) about the document, including its title and links to its scripts and style sheets.

* Title - Defines the title of the document, shown on the browsers title bar.

* Body - Represents the content of an HTML Document.

* Form - Represents a document section that contains interactive controls to submit information to a web server.
    * Action - The URI of a program that processes the form information.
    * Method - The HTTP method that the browser uses to submit the form. Possible values are:
        * Post: Corresponds to the HTTP POST method; form data are included in the body of the form and sent to the server.
        * Get: Corresponds to the HTTP GET method; form data are appended to the action attribute URI with a '?' as separator, and the resulting URI is sent to the server. USe this method when the form has no side-effects and contains only ASCII characters.

* Fieldset - Used to group several controls as well as labels within a web form.

* Div - Document Division Element is the gerneic contain for flow content, which does not inhernetly represent anything. It can be used to group elements for styling purposes (using the class or id attributes), or because they share attribue values, such as lang. It should be used only when no other semantic element (such as nav or article) is appropriate.

* Label - The HTML Label Element (label) represents a caption for an item in a user interface. It can be associated with a control either by placing the control element inside the label element, or by using the for attribute. Such a control is called the labeled control of the label element. One input can be associated with multiple labels. It's worth noting, however, that labels are not themselves directly associated with forms. They are only indirectly associated with forms through the controls with which they're associated.

* Input - Used to create interavtive controls for web-based forms in order to accept data from the user.
    * Type -The type of control to display. The default type is text.
        * Password - Does not show the values entered into the form
        * Email - The input value is validated to contain either the empty string or a single valid e-mail address before submitting.
        * Checkbox - A check box. You must use the value attribute to define the value submitted by this item. Use the checked attribute to indicate whether this item is selected. You can also use the indeterminate attribute (which can only be set programmatically) to indicate that the checkbox is in an indeterminate state (on most platforms, this draws a horizontal line across the checkbox).
        * Date - A control for entering a date (year, month, and day, with no time).
        * Submit - A button that submits the form.
    * Placeholder - A hint to the user of what can be entered in the control . The placeholder text must not contain carriage returns or line-feeds.

* Select - control used to create a list of options. Used with option element inside.
    * Name - The name of the control

* Option - Option tag defines an option in a select list. Option elements go inside a select or datalist element
    * Value - specifies the value to be sent to the server.

* Button - The button tag defines a clickable button. Inside the element you can put content like text or images. This is the diference between this element and buttons created with the input element.

