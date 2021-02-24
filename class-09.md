# Read: 09 - Forms and Events

## Forms 
* printed document that contains spaces for you to fill in information
* Information from a form is sent in name/value pairs.

```html
<form action="http://www.example.com/subscribe.php" method="get">
  <p>This is where the form controls will appear.
  </p>
</form>
```

`action` Every `<form>` element requires an action attribute. Its value
is the URL for the page on the server that will receive the
information in the form when it is submitted.
`method` Forms can be sent using one of two methods: get or post.
`id` often used by scripts — such as those that check you have
entered information into fields that require values)

* There are several types of form controls that you can use to collect information from visitors to your site. Each form control is given a name, and the text the user types in or the values of the options they select are sent to the server

1. ADDInG tEXt:
  * *Text input (single-line)* Used for a single line of text such as email addresses and names

  * *Password input* Like a single line text box but it masks the characters entered

  * *Text area (multi-line)* For longer areas of text, such as messages and comments.

2. mAkInG ChoICEs:
  * *Radio buttons* For use when a user must select one of a number of options

  * *Checkboxes* When a user can select and unselect one or more options

  * *Drop-down boxes* When a user must pick one of a number of options from a list.

3. submIttInG Forms:
  * *Submit buttons:* to submit data from your form to another web page.

  * *Image buttons*: Similar to submit buttons but they allow you to use an image.

4. *File upload* Allows users to upload files to a website

### hoW Forms Work
1. A user fills in a form and then presses a button to submit the information to the server
2. The name of each form control is sent to the server along with the value the user enters or selects.
3. The server processes the information using a programming language such as PHP, C#, VB.net, or Java. It may also store the information in a database.
4. The server creates a new page to send back to the browser based on the information received.

## Events
Events are the browser's way of indicating when something has happened 

### HOW EVENTS TRIGGER JAVASCRIPT CODE
1. Select t he element node(s) you want the script to respond to.

2. Indicate which event on the selected node(s) will trigger the response.

3. State the code you want to run when the event occurs.


***

Go back

[Back](README.md)

