
![htmlcss](https://i.ibb.co/JQnNcFF/1-l4x-ICb-IIYlz1-OTym-WCo-UTw-removebg-preview.png)

# What is HTML?
The HyperText Markup Language, or HTML is the standard markup language for documents designed to be displayed in a web browser. It can be assisted by technologies such as Cascading Style Sheets and scripting languages such as JavaScript.


## Why HTML?
Browsers do not display the HTML tags, but use them to interpret the content of the page. HTML can embed programs written in a scripting language such as JavaScript which affect the behavior and content of web pages. Inclusion of CSS defines the look and layout of content.


## What is an HTML Element?

The HTML code is made up of characters that live inside angled
brackets  these are called HTML elements. Elements are usually
made up of two tags: an opening tag and a closing tag. The closing tag
has an extra forward slash in it. Each HTML element tells the browser
something about the information that sits between its opening and
closing tags.

`<tagname>Content goes here</tagname>`

## HTML Structure :

1. line containing HTML version information.
2. head a declarative header section.
3. body which contains the document's actual content.
    - header
    - main
    - footer


## Example :

```
<!DOCTYPE html>
<HTML>
   <HEAD>
      <TITLE>My first HTML document</TITLE>
   </HEAD>
   <BODY>
      <P>Hello world!</P>
   </BODY>
</HTML>
```

## Commonly Used HTML Tags :

| **Tags** | **Use** |
| ----------- | ----------- |
| `<HTML>. . . </HTML>` | The entire HTML document |
| `<HEAD> . . . </HEAD>` | 	The head of the HTML document |
| `<BODY> . . . </BODY>` | All the other content in the HTML document |
| `<TITLE> . . . </TITLE>` | 	The title of the document |
| `<H1> . . . </H1> `| First-level heading large text size |
|` <H6> . . . </H6> `| Sixth-level heading small text size |
|`<P> . . . </P>`|**Paragraph** You need to use this tag to make a new paragraph.|
|`<BR>`|**Line Break** This tag will show a blank line.|
|`<em> . . . </em>`|Emphasized text |
|`<strong> . . . </strong>`| Important text|
|`<mark> . . . </mark>`|Marked/highlighted text|
|`<cite> . . . </cite>`|The title of a work|
|`<dfn> . . . </dfn>`|A definition term|
|`<ins> . . . </ins> `|Content that has been inserted into a document|
|`<del> . . . </del>`| Text that has been deleted from document|



# What is CSS?
Cascading Style Sheets is a style sheet language used for describing the presentation of a document written in a markup language such as HTML. CSS is a cornerstone technology of the World Wide Web, alongside HTML and JavaScript.

## Why CSS?
CSS is a language for specifying how documents are presented to users how they are styled, laid out, etc.
A document is usually a text file structured using a markup language  HTML is the most common markup language, but you may also come across other markup languages such as SVG or XML.
Presenting a document to a user means converting it into a form usable by your audience. Browsers, like Firefox, Chrome, or Edge , are designed to present documents visually, for example, on a computer screen, projector or printer.

## CSS syntax : 
```
h1 {
    color: red;
    font-size: 5em;
}
```
## How to use CSS and HTML ?
CSS can be added to HTML documents in 3 ways:

- **Inline** - by using the style attribute inside HTML elements
- **Internal** - by using a <style> element in the <head> section
- **External** - by using a <link> element to link to an external CSS file

The most common way to add CSS, is to keep the styles in external CSS files. 

## CSS Selectors
| **Selector** | **Meaning** |
| ----------- | ----------- |
|Universal Selector|Applies to all elements in the document|
|Type Selector|Matches element names|
|Class Selector|Matches an element whose class attribute has the value|
|ID Selector|Matches an element whose id attribute has the value|
|Child Selector|Matches an element that is a direct child of another|
|Descendant Selector|Matches an element that is a descendent of another specified element|
|Adjacent Sibling Selector|Matches an element that is the next sibling of another|
|General Sibling Selector|Matches an element that is a sibling of another, although it does not have to be the directly preceding element|

# What is JavaScript?

JavaScript is a scripting or programming language that allows you to implement complex features on web pages  every time a web page does more than just sit there and display static information for you to look at  displaying timely content updates, interactive maps, animated 2D/3D graphics, scrolling video jukeboxes, etc. you can bet that JavaScript is probably involved. It is the third layer of the layer cake of standard web technologies

## Why JavaScript?
JavaScript is one of the 3 languages all web developers must learn:

   1. **HTML** to define the content of web pages

   2. **CSS** to specify the layout of web pages

   3. **JavaScript** to program the behavior of web pages


![js](https://i.ibb.co/PMQBWTC/tjlpqypllsz31-removebg-preview.png)


## Example :

```
var iceCream = 'chocolate';
if(iceCream === 'chocolate') {
  alert('Yay, I love chocolate ice cream!');
} else {
  alert('Awwww, but chocolate is my favorite...');
}
```

**Note:** A semicolon at the end of a line indicates where a statement ends. It is only required when you need to separate statements on a single line. However, some people believe it's good practice to have semicolons at the end of each statement. 



## JavaScript Data Types: 

| Variable | Example |
| ------------ | ------------ |
|String| "var myVariable = 'Bob';"|
|Number| 	"var  myVariable = 10;"|
|Boolean| "	var myVariable = true;"|
|Array| "let myVariable = [1,'Bob','Steve',10];"|
|Object|"let myVariable = document.querySelector("h1");"|

## Operators 

- ASSIGNMENT OPERATORS
  - `color = 'beige'; `
- ARITHMETIC OPERATORS
  - `area = 3 * 2; `
- STRING OPERATORS 
  - `greeting= 'Hi' + 'Molly';`
- COMPARISON OPERATORS
  - `buy = 3 > 5; `
- LOGICAL OPERATORS 
  - `buy= (5 > 3) && (2 < 4); `

## For Loop
For loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

### Why For Loops?

1. Like all loops, "for loops" execute blocks of code over and over again.
2. The advantage to a for loop is we know exactly how many times the loop will execute before the loop starts.
3. Generic Syntax.

### Syntax
A for statement looks as follows:
```
for (statement 1; statement 2; statement 3) {
  // code block to be executed
}
```
### Example

```
for (i = 0; i < 5; i++) {
  text += "The number is " + i + "<br>";
}
```
## While Loop
While statement executes its statements as long as a specified condition evaluates to true


### Why while Loops?
1. Like all loops, "while loops" execute blocks of code over and over again.
2. The advantage to a while loop is that it will go (repeat) as often as necessary to accomplish its goal.
3. Generic Syntax.
4. Infinite loops.

### Syntax
A while statement looks as follows:
```
while (condition) {
  // code block to be executed
}
```
### Example
```
while (i < 10) {
  text += "The number is " + i;
  i++;
}
```

preceding element
### Helpful resources:
- [HTML Tutorial](https://www.w3schools.com/html/)
- [HTML Documentation](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [What is CSS?](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)
- [JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
