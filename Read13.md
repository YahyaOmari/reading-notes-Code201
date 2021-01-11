# Local Storage for Web Application!

HTTP cookies or internet cookies also are built specifically for Internet web browsers to track, personalize, and save information about each user's session. Cookies have limited data about 4 KB. 

We can use functions to support our html storage. 

But instead of using these functions we can use  Modernizr to detect support for HTML5 Storage.


Web storage provides two objects for storing data on the client:

- window.localStorage - stores data with no expiration date
- window.sessionStorage - stores data for one session (data is lost when the browser tab is closed)

### The localStorage Object
The localStorage object stores the data with no expiration date. The data will not be deleted when the browser is closed. 