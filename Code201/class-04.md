![html](https://www.freeiconspng.com/uploads/w3c-html5-logo-0.png)

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

## Helpful resources:

- [HTML Tutorial](https://www.w3schools.com/html/)
- [HTML Documentation](https://developer.mozilla.org/en-US/docs/Web/HTML)
