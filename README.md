### Create a complex HTML form ("WePaintInteriors")

#### Part 1

Use HTML form elements, Google Fonts, and Flexbox, as well as margin and padding, to create the mockup below in HTML and CSS (download the attached files to see a larger version).

![Mockup of WePaintInteriors web page](images/paintingWebsite%20mockup.jpg)

Use the appropriate form control for each field (e.g. text, date, time, color, etc.). When the user fills in the form and clicks submit, the result should show data for all fields. For example:

![Mockup of submitted form data](images/submittedData%20mockup.jpg)

Here are some things to keep in mind:

* Font name is Muli
* Tips and helpful links on HTML forms can be found on the [HTML forms cheat sheet](./HTML-Forms-Cheat-Sheet.pdf)
* All form elements should be inside just one `<form>` element
* The `action` for the form should go to [https://www.w3schools.com/action_page.php](https://www.w3schools.com/action_page.php)
* Each field should specify a `name` attribute for user input to be recorded
* Using the `button` element instead of `input type="submit"` will allow you to style the button in CSS
* To style a text box in CSS, use the `input[type=text]` selector. To style an email field, use `input[type=email]`, etc.
* Form layout can be applied using Flexbox (among other options); you can add `div` and other elements inside the `form` element
* Don't forget "Box Vision"!

#### Part 2

Add basic front end validation to your WePaintInteriors work:

* Make sure the first name, last name, and email are required.
* Make sure the first name and last name only contain letters.
* Limit the number of characters in the state field to 2.
* Make sure the zip code only contains numbers.
* Bonus: make sure the comments only contain letters, numbers, and normal punctuation characters.

Note: You don't want to have form validations that are too strict. You never know what characters are in someone's name, and in other countries the zip code can contain letters.

More important note even though it's at the bottom: NEVER TRUST DATA COMING FROM THE CLIENT. Always validate data on the server as well (more on this coming soon).
