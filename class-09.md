## Chapter 7: Forms
### Why we need them:
> In addition to enabling users to search, forms also allow users to perform other functions online. Forms are used when registering as a member of a website, when shopping online, and when signing up for newsletters or mailing lists.

## There are several types of form controls that are used to collect information from visitors to sites.
1, Adding Text:
+ Text input (single-line)
+ Password input
+ Text area (multi-line)
2. Making Choices:
+ Radio buttons
+ Checkboxes
+ Drop-down boxes
3. Submitting Forms:
+  Submit buttons
+ Image buttons
4. Uploading Files:
+ File upload
# How Forms Work
+  + A user fills in a form and then presses a button to submit the information to the server.

+ The name of each form control is sent to the server along with the value the user enters or selects.

+ The server processes the information using a programming language such as PHP, C#, VB.net, or Java. It may also store the information in a database.

+ The server creates a new page to send back to the browser based on the information received.

# Form Structure
```<form>``` Form controls live inside a

element. This element should always carry the action attribute and will usually have a method and id attribute too. `action` Every element requires an action attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted. `method` Forms can be sent using one of two methods: `get` or `post`. `id` ### Text Input ``` ```
used to create several different form controls. The value of the type attribute determines what kind of input they will be creating. `type="text"` When the type attribute has a value of text, it creates a singleline text input. `name` into a form, the server needs to know which form control each piece of data was entered into. `size` The size attribute should not be used on new forms. It was used in older forms to indicate the width of the text input `maxlength` to limit the number of characters a user may enter into the text field. ### Password Input `
` `type="password"` When the type attribute has a value of password it creates a text box that acts just like a single-line text input, except the characters are blocked out. `name` The name attribute indicates the name of the password input, which is sent to the server with the password the user enters. `size` `maxlength` It can also carry the size and maxlength attributes like the the single-line text input. ### Text Area  


