![htmlcss](https://i.ibb.co/JQnNcFF/1-l4x-ICb-IIYlz1-OTym-WCo-UTw-removebg-preview.png)

## What is HTML?

The HyperText Markup Language, or HTML is the standard markup language for documents designed to be displayed in a web browser. It can be assisted by technologies such as Cascading Style Sheets and scripting languages such as JavaScript.

## HTML Structure :

1. line containing HTML version information.
2. head a declarative header section.
3. body which contains the document's actual content.
   - header
   - main
   - footer

# Links

## Linking to Other Sites

Links are created using the` <a>`
element which has an attribute
called href. The value of the
href attribute is the page that
you want people to go to when
they click on the link.

### Example

```
<a href="http://www.empireonline.com">
 Empire</a>
```

## Linking to Other Pages on the Same Site

When you are linking to other
pages within the same site.

### Example

```
 <a href="contact.html">Contact</a>

```

## Directory Structure

On larger websites it's a good idea to organize your code by placing the
pages for each different section of the site into a new folder. Folders on a
website are sometimes referred to as directories.

### Example

```
<a href="movies/dvd/reviews.html">
Reviews</a>
```

## Email Links

To create a link that starts up
the user's email program and
addresses an email to a specified
email address.

### Example

```
<a href="mailto:jon@example.org">Email Jon</a>

```

## Opening Links in a New Window

If you want a link to open in a new window.

### Example

```
<a href="http://www.imdb.com" target="_blank">
Internet Movie Database</a>
```

# Layout

## HTML Layout Elements

- `<header> `- Defines a header for a document or a section
- `<nav> ` - Defines a set of navigation links
- `<section> `- Defines a section in a document
- `<article> `- Defines an independent, self-contained content
- `<aside> `- Defines content aside from the content (like a sidebar)
- `<footer> `- Defines a footer for a document or a section
- `<details> `- Defines additional details that the user can open and close on demand
- `<summary> `- Defines a heading for the `<details>` element

## Positioning schemes

- Normal flow
- Relative Positioning
- Absolute positioning

## Position

- position: static;
- position: relative;
- position: fixed;
- position: absolute;
- position: sticky;

## Floating Elements

The float property allows you
to take an element in normal
flow and place it as far to the
left or right of the containing
element as possible.

## Clearing Floats

The clear property allows you
to say that no element
should touch the left or righthand sides of a box.

# Javascript Functions

Functions let you group a series of statements together to perform a
specific task. If different parts of a script repeat the same task, you can
reuse the function rather than repeating the same set of statements.

## Why Functions?

1. You can reuse code: Define the code once, and use it many times.

2. You can use the same code many times with different arguments, to produce different results.

## Syntax

A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

Function names can contain letters, digits, underscores, and dollar signs same as variables.

The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)

The code to be executed, by the function, is placed inside curly brackets: {}

```
function name(parameter1, parameter2, parameter3) {
  // code to be executed
}
```

## Example

```
function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}

var x = myFunction(4, 3);   // Function is called, return value will end up in x
```

# Pair programming

## How does pair programming work?

While there are many different styles, pair programming commonly involves two roles: the Driver and the Navigator. The Driver is the programmer who is typing and the only one whose hands are on the keyboard. Handling the “mechanics” of coding, the Driver manages the text editor, switching files, version control, and—of course writing—code. The Navigator uses their words to guide the Driver but does not provide any direct input to the computer. The Navigator thinks about the big picture, what comes next, how an algorithm might be converted in to code, while scanning for typos or bugs. The Navigator might also utilize their computer as a second screen to look up solutions and documentation, but should not be writing any code.

## Why pair program?

1. Greater efficiency
2. Engaged collaboration
3. Learning from fellow students
4. Social skills
5. Job interview readiness
6. Work environment readiness

## Helpful resources:

- [HTML Tutorial](https://www.w3schools.com/html/)
- [HTML Documentation](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [What is CSS?](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)
- [JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
- [6 Reasons for Pair Programming](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)
