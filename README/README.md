# introduction to communicating with the sever.
## three pillars of web programming 
1. manipulating the DOM. 
2. Creating events.
3. Communicating with the server.- how we send and retrieve information from the server.

## describing the process of communicating with the server.
- Click events kicks off a sequence of actions to notify the server that the post has received a like.
- The server updates the post in teh backend then passes a message back to the browser indicating that the update was made successfully.
- when teh success message is received, we then update the DOM to reflect the change.

to keep the user experience fast and smooth, we use something called the AJAX technique.

## AJAX technique.
AJAX technique allows a website in the browser to work fast and smoothly when a user is interacting with website.
- AJAX is short for "asynchronous Javascript and XML"
- asynchronous javascript and XML is the process used to make requests to the server and update the DOM without reloading the webpage.
- the name AJAX arises from the fact that in the past, the data sent back to the browser from the server was encoded as XML. However its most often sent back in a format known as JSON(jay-Sawn) short for Javascript Object Notation.
- Javascript object notation (JSON) is a string that javascript knows into an object.
- Using Javascript we can access the JSON returned by the server and use it to update the DOM.
