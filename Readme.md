# Cat & Light Beginer Application

Breaking Down into Parts
Manipulating the HTML
How do we manipulate HTML and Css Using javascript ?
- Based on the user action we are manipulating adding Dynamic
Need to understand the DOM (Document Object Model) & Why it is important ?
-DOM is the structured representation of the content in the Document created by the browser

What is HTML DOM ?
-Tree structured representation of HTML Document Created by the Browser .
- It Allows Javascript to change the Document Structure, Style and Content 
HTML DOM:- 
<!DOCTYPE html>
<html>
<head></head>
<body>

<h1>Web Technologies</h1>
<button> Change Heading</button>

</body>
</html>
# html DOM Tree Look Like
Document
html
1. head 2. body
        a. h1            b. button
        Web Technologies  Change Heading 

- The Dom tree  represents html document as nodes.
-Each node is reffered to as an object 

# What is Document Object ?
- it is the entry point of the DOM 
- To access any html element you should always start with aceessing the document object first.
* getElementById()- Method helps to select the HTML Element with a specific Id
* textContent -   To manipulate the text with in the HTML Element use textContent Property.
* style- The style Property is used to get or set a specific  style of an HTML Element using different Css Properties.

# How to manipulate HTML and Css Based on the User Actions ?
- Based on the user action manipulate the HTML & Css we have Events 
- Events are the Actions by which the User or Browser interact with HTML Elements
Actions are Like- Clicking Button, Pressing keyboard keys, scrolling the page etc.
1.onclick-Event :- onclick event occur when user clicks on an html Element.
SO need to Define a function
In Javascript define the function 
- Function Declaration.
function Function_Name(){
    //reusable Code
}
//invoking the Function
Function_Name()

1.  Project - Cat & Light Observations
- Switch status Changes
- Bulb goes On and Off
- cat becom visible and invisible
- Switch (Button) background color Changes

Achive this Project
1. Static HTML Page With Css Creating
2. Based on the user actions we have to change the Content, image, color.Steps are
a. Make switches listen to User Actions     
b. Make bulb Go On and Off
c. Make Cat Visible and invisible
d. Update Switch Status
e. Change the background color of the Switch


Adding Functionalities:-
a. Making Switches listen to User Actions
- So Define the onclick event to the Both Button with name of event onclick="switchOff()", onclick="switchOn()"
Q:- How to make Bulb Go On and Off ?
So uniquely identify the Bulb so add Id='bulbImage"- next based on the user action this Id Image will change to anothe Image.



#   C a t - L i g h t 
 
 