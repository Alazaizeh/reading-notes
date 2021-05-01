
![Javascript](https://i.ibb.co/BsCTKJc/68747470733a2f2f75706c6f61642e.png)

# What is JavaScript?

JavaScript is a scripting or programming language that allows you to implement complex features on web pages  every time a web page does more than just sit there and display static information for you to look at  displaying timely content updates, interactive maps, animated 2D/3D graphics, scrolling video jukeboxes, etc. you can bet that JavaScript is probably involved. It is the third layer of the layer cake of standard web technologies

## Why JavaScript?
JavaScript is one of the 3 languages all web developers must learn:

   1. **HTML** to define the content of web pages

   2. **CSS** to specify the layout of web pages

   3. **JavaScript** to program the behavior of web pages

# OBJECT
## WHAT IS AN OBJECT? 
JavaScript object is a standalone entity that holds multiple values in terms of properties and methods.
### Example
```
var person = {
  firstName: "John",
  lastName: "Doe",
  age: 25,
};
```
#  Document Object Model
Each node is an object with methods and properties.
Scripts access and update this DOM tree (not the source HTML file).
Any changes made to the DOM tree are reflected in the browser. 

![tree](https://i.ibb.co/CKgxXH1/rsz-1200px-dom-modelsvg.png)

## Body of HTML page 
As a browser loads a web page, it creates a model of that page. The model is called a DOM tree, and it is stored in the browsers' memory. It consists of four main types of nodes.
![html](https://i.ibb.co/9y58Jsp/Untitled-1.png)


## Accessing and updating the DOM tree involves two steps:
1. Locate the node that represents the element you want to work with.
2. Use its text content, child elements, and attributes. 

## Navigating Between Nodes
You can use the following node properties to navigate between nodes with JavaScript:
* `parentNode`
* `childNodes[nodenumber]`
* `firstChild`
* `lastChild`
* `nextSibling`
* `previousSibling`

### Example:
Retrieves the text of an `<h1>` element and copies it into a `<p>` element:
```
<!DOCTYPE html>
<html>
<body>

<h1 id="id01">My First Page</h1>
<p id="id02"></p>

<script>
document.getElementById("id02").innerHTML = document.getElementById("id01").innerHTML;
</script>

</body>
</html>
```

### Example: 
Looping through a nodelist 
```
var hotltems = document.querySelectorAll('li.hot') ;   // Store Nodel ist i n array 
if (hotltems.length > O) {               // If it contains i t ems 
for (var i=O; i<hotltems.length; i++) {        // Loop throug h each it em 
hotltems[i].className = 'cool';       // Change val ue of class at tri bute 
}
}
```
## The most important nodeType properties are:

|Node|Type|Example|
|---|---|---|
|ELEMENT_NODE|1|`<h1 class="heading">Title</h1>`|
|ATTRIBUTE_NODE|2|` class = "heading" (deprecated)`|
|TEXT_NODE|3|`Hello`|
|COMMENT_NODE|8|`<!-- This is a comment -->`|
|DOCUMENT_NODE|9|`The HTML document itself (the parent of <html>)`|
|DOCUMENT_TYPE_NODE|10|`<!Doctype html>`|

## Removing Elements 
1. Store the element to be removed in a variable
2. Store the parent of that element in a variable
3. Remove the element from its containing element

```
var removeEl = document.getElementsByTagName('li')[3]; 
var containerEl = removeEl .parentNode;
containerEl.removeChild(removeEl);
```
## Removing Attributes 
```
var firstltem = document.getElementByld{'one');      // Get the first item
if (firstltem.hasAttribute('class')) {       //If it has a class attribute
firstltem.removeAttribute( 'class' );        //Remove its class attribute
}
```

# CROSS-SITE SCRIPTING
Cross-Site Scripting (XSS) attacks are a type of injection, in which malicious scripts are injected into otherwise benign and trusted websites

## HOW XSS HAPPENS 
XSS involves an attacker placing malicious code into a site, Websites often feature content created by many different people.

## WHAT CAN THESE ATTACKS DO?
XSS can give the attacker access to information in :
* The DOM (including form data)
* That website's cookies
* Session tokens: information that identifies you from other users when you log into a site


## Helpful resources:
- [JavaScript basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
- [JavaScript Tutorial](https://www.w3schools.com/js/DEFAULT.asp)
- [Node.nodeType](https://developer.mozilla.org/en-US/docs/Web/API/Node/nodeType)
