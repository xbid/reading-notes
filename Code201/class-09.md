# FORMS , LISTS & TABLES

## Why Forms?

![ ](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT2bp675ft2gXq7SKuM0iUlvZiNS70w5KntAA&usqp=CAU)

Photo by [GStatic](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT2bp675ft2gXq7SKuM0iUlvZiNS70w5KntAA&usqp=CAU)

The best known form on the web is probably the search box that sits right in the middle of Google's homepage.

In addition to enabling users to search, forms also allow users to perform other functions online. You will see forms when registering as a member of a website, when shopping online, and when signing up for newsletters or mailing lists.

![ ](https://progressive.org/downloads/13507/download/google.gif?cb=ef422921d864963ec48a500a0efd00ad)

## The `<form>` Element

*The HTML `<form>` element is used to create an HTML form for user input:*
  
~~~
<form>
.
form elements
.
</form>
~~~

### The `<input>` Element

***The HTML `<input>` element is the most used form element.***

*An `<input>` element can be displayed in many ways, depending on the type attribute.*

## HTML Input Types

*Here are the different input types you can use in HTML:*

~~~
`<input type="button">`
`<input type="checkbox">`
`<input type="color">`
`<input type="date">`
`<input type="email">`
`<input type="file">`
`<input type="image">`
`<input type="month">`
`<input type="number">
`<input type="password">`
`<input type="radio">`
`<input type="reset">`
`<input type="search">`
`<input type="submit">`
`<input type="tel">`
`<input type="text">`
`<input type="time">`
`<input type="url">`
~~~

## The `<label>` Element

*Notice the use of the `<label>` element in the example above.*

> The `<label>` tag defines a label for many form elements.
> The `<label>` element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element.
> The `<label>` element also help users who have difficulty clicking on very small regions (such as radio buttons or checkboxes)
> because when the user clicks the text within the `<label>` element, it toggles the radio button/checkbox.
> The for attribute of the `<label>` tag should be equal to the id attribute of the `<input>` element to bind them together.

## Radio Buttons

***The `<input type="radio">` defines a radio button.***

*Radio buttons let a user select ONE of a limited number of choices.*

*Example:*
*A form with radio buttons:*

~~~
<form>
  <input type="radio" id="male" name="gender" value="male">
  <label for="male">Male</label><br>
  <input type="radio" id="female" name="gender" value="female">
  <label for="female">Female</label><br>
  <input type="radio" id="other" name="gender" value="other">
  <label for="other">Other</label>
</form>
~~~

## Checkboxes

***The `<input type="checkbox">` defines a checkbox.***

*Checkboxes let a user select*ZERO*or*MORE*options of a limited number of choices.*

*Example:*
*A form with checkboxes:*

~~~
<form>
  <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
  <label for="vehicle1"> I have a bike</label><br>
  <input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
  <label for="vehicle2"> I have a car</label><br>
  <input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
  <label for="vehicle3"> I have a boat</label>
</form>
~~~

## The Submit Button

***The `<input type="submit">` defines a button for submitting the form data to a form-handler.***

> The form-handler is typically a file on the server with a script for processing input data.
> The form-handler is specified in the form's action attribute.

*Example:*
*A form with a submit button:*

~~~
<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe"><br><br>
  <input type="submit" value="Submit">
</form>
~~~

## The `<textarea>` Element

***The `<textarea>` element defines a multi-line input field (a text area):***

*Example*

~~~
<textarea name="message" rows="10" cols="30">
The cat was playing in the garden.
</textarea>
~~~

## Input Type Password

***`<input type="password">` defines a password field:***

*Example*

~~~
<form>
  <label for="username">Username:</label><br>
  <input type="text" id="username" name="username"><br>
  <label for="pwd">Password:</label><br>
  <input type="password" id="pwd" name="pwd">
</form>
~~~

## Input Type Email

***The `<input type="email">` is used for input fields that should contain an e-mail address.***

> Depending on browser support, the e-mail address can be automatically validated when submitted.
> Some smartphones recognize the email type, and add ".com" to the keyboard to match email input.

*Example*

~~~
<form>
  <label for="email">Enter your email:</label>
  <input type="email" id="email" name="email">
</form>
~~~

## Input Type Url

***The `<input type="url">` is used for input fields that should contain a URL address.***

> Depending on browser support, the url field can be automatically validated when submitted.
> Some smartphones recognize the url type, and adds ".com" to the keyboard to match url input.

Example

~~~
<form>
  <label for="homepage">Add your homepage:</label>
  <input type="url" id="homepage" name="homepage">
</form>
~~~

# CSS Lists

- unordered lists (```<ul>```) - the list items are marked with bullets
- ordered lists (```<ol>```) - the list items are marked with numbers or letters
  
*The CSS list properties allow you to:*

- Set different list item markers for ordered lists
- Set different list item markers for unordered lists
- Set an image as the list item marker
- Add background colors to lists and list items

## Different List Item Markers

*The list-style-type property specifies the type of list item marker.*

*Example*

~~~
ul.a {
  list-style-type: circle;
}

ul.b {
  list-style-type: square;
}

ol.c {
  list-style-type: upper-roman;
}

ol.d {
  list-style-type: lower-alpha;
}
~~~

***An Image as The List Item Marker***
*The `list-style-image` property specifies an image as the list item marker:*

*Example*

~~~
ul {
  list-style-image: url('sqpurple.gif');
}
~~~

***Position The List Item Markers***
*The list-style-position property specifies the position of the list-item markers (bullet points).*

*Example*

~~~
ul.a {
  list-style-position: outside;
}

ul.b {
  list-style-position: inside;
}
~~~

## CSS Borders

***The CSS border properties allow you to specify the style, width, and color of an element's border.***
> The border-style property specifies what kind of border to display.

*The border-style property can have from one to four values (for the top border, right border, bottom border, and the left border).*

*Example:*

> Demonstration of the different border styles:

- p.dotted {border-style: dotted;}
- p.dashed {border-style: dashed;}
- p.solid {border-style: solid;}
- p.double {border-style: double;}
- p.groove {border-style: groove;}
- p.ridge {border-style: ridge;}
- p.inset {border-style: inset;}
- p.outset {border-style: outset;}
- p.none {border-style: none;}
- p.hidden {border-style: hidden;}
- p.mix {border-style: dotted dashed solid double;}

### CSS cursor Property

***Example***

*CSS can generate a bunch of different mouse cursors:*

- alias {cursor: alias;}
- all-scroll {cursor: all-scroll;}
- auto {cursor: auto;}
- cell {cursor: cell;}
- context-menu {cursor: context-menu;}
- col-resize {cursor: col-resize;}
- copy {cursor: copy;}
- crosshair {cursor: crosshair;}
- default {cursor: default;}
- e-resize {cursor: e-resize;}
- ew-resize {cursor: ew-resize;}
- grab {cursor: grab;}
- grabbing {cursor: grabbing;}
- help {cursor: help;}
- move {cursor: move;}

### Creating custom events

![ ](https://static.adevait.com/2019/07/9-Complete-Guide-for-Frontend-Validation-of-Forms@2x-100-768x401.jpg)

~~~
const event = new Event('build');

// Listen for the event.
elem.addEventListener('build', function (e) { /* ... */ }, false);

// Dispatch the event.
elem.dispatchEvent(event);
~~~

### JavaScript HTML DOM EventListener

***The addEventListener() method***

> Add an event listener that fires when a user clicks a button:
> document.getElementById("myBtn").addEventListener("click", displayDate);
> The `addEventListener()` method attaches an event handler to the specified element.
> The `addEventListener()` method attaches an event handler to an element without overwriting existing event handlers.

## HTML Event Attributes

*On this page I give a quick overview of the most important events, including compatibility information for modern browsers.*

> All events named on this page are recognized by most browsers when they occur on certain HTML elements.
> This means that the browser looks if any event handling script is registered to the HTML element for this event. If there is such a script, it is executed immediately.

***Interface events***
*Interface events are events that are not caused by user actions, but by the result of user actions.
***When the user clicks on any element he always causes a click event. When clicking on the element has special meaning, an additional interface event is caused.
For instance, when the user clicks on a link his action causes a click event. Clicking on a link orders a new page to be loaded, though, so the result of this specific click event is the interface event unload.***

***Mouse events***
*From Netscape 2 onwards all browsers recognize two events on links. When the user moves the mouse into the link area, the mouseover event fires.*
*When he clicks on it the click event fires. Pretty soon after the mouseout event was added, which fires when the mouse leaves the link area.*
*Thus the Traditional Triad of mouse events was formed.*

***Form events***
*Forms recognize the submit and reset events, which — predictably — fire when the user submits or resets a form.*
*The submit event is the key of any form validation script.*
*When the user submits the form, go through all form fields and see if he has filled in correct data.
*If you spot a mistake, stop the form submission and alert the user of the problem.*
