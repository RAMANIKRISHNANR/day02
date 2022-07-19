# day02


Difference between document object and window object

Document object:

The document object represent a web page that is loaded in the browser. By accessing the document object, we can access the element in the HTML page. With the help of document objects, we can add dynamic content to our web page. The document object can be accessed with a window.document or just document.

syntax:

document.methodname();

eg;document.getelementById();

Window Object:

The window object is the topmost object of the DOM hierarchy. It represents a browser window or frame that displays the contents of the webpage. Whenever a window appears on the screen to display the contents of the document, the window object is created. 

syntax:

windows.propertyname();

eg;windows.alert();

Difference:

Document Object:

i.It represents any HTML document or web page that is loaded in the browser.

ii.It is loaded inside the window.

iii.It is the object of window property.

iv.All the tags, elements with attributes in HTML are part of the document.

v.We can access the document from a window using the window. document

vi.The document is part of BOM (browser object model) and dom (Document object model)

Window Object:

i.It represents a browser window or frame that displays the contents of the webpage.

ii.It is the very first object that is loaded in the browser.

iii.It is the object of the browser.

iv.Global objects, functions, and variables of JavaScript are members of the window object.

v.We can access the window from the window only. i.e. window.window

vi.The window is part of BOM, not DOM.


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------























