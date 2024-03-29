Write a blog on the difference between document and window objects.

DOCUMENT OBJECTS :

•	The Document objects represents a web page that is loaded in the browser.
•	By accessing the document object, we can access the element in the HTML page.
•	It can be accessed with a window.document or document
•	With the help of document object, we can add dynamic content to our web page.

Properties of Document :

* body - It returns the contents of the body element.c
* head - It returns the head element of the document.
* title - It returns the title element of the document.
* URL  -  It returns the complete URL of the document.
* doctype - It returns the document’s doctype.

Methods of Document :

* createComment() - It is used to create a comment node with some text.
* createElement() - It is used to create HTML element .
* write() - It is used to write content or javascript code in the document.
* writeln() - It is used to write a document with a newline character after each statement.

Key features of the Document Object:

1.	DOM Manipulation :
        It allows the developers to change the text content of an element,attributes and create new elements.
2.	Element Selection :
        This helps the developers to select an element by ID.
3.	DOM Events :
        It helps to adding a click event listener to a button such as clicks,keypresses and form submission.





WINDOW OBJECT :
	
•	It is the topmost object of the DOM hierarchy.
•	It helps the browser window to display the contents of webpage.
•	Whenever the window appears on the screen to display the contents of the document, the window object is created. 

Properties of Window :

* Closed - It holds a Boolean value that represents whether the window is closed or not.
* console - It returns a reference to the console object which provides access to the browser’s debugging console.
* Document -  It returns a reference to the document object of that window.
* Length - It represents the number of frames in the current window.

Methods of Window :

* open() -  It is used to open a new tab or window with the specified URL and name.
* close() - It is used for closing a certain window or tab of the browser which was previously opened.
* focus() - It is used to give focus to an element in the current window.
* confirm() - It is used to display a modal dialog with an optional message and two buttons i.e. OK and Cancel.


Key features of the Window Object :

1.	Global Scope :
        Variables and functions are declared without the “var” , “let” or “const” keyword become properties of the ‘window’ object.
2.	Navigation and Location :
        Developers can access the URL and Manipulate the browser’s location through the “window.location” object.
3.	Timers and Intervals :
        Using ‘setTimeout’ and ‘setInterval’ it run a function after a delay.