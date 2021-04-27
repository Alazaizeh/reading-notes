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

# Lists:

## Unordered Lists

An unordered list starts with the `<ul>` tag. Each list item starts with the `<li>` tag.

### Example:

```
<ul>
<li>Coffee</li>
<li>Tea</li>
<li>Milk</li>
</ul>
```

## Ordered Lists

An ordered list starts with the `<ol>` tag. Each list item starts with the `<li>` tag.

### Example:

```
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```

## Definition Lists

The `<dl> `tag defines the definition list, the `<dt>` tag defines the term (name), and the`<dd>`tag describes each term:

### Example:

```
<dl>
  <dt>Coffee</dt>
  <dd>- black hot drink</dd>
  <dt>Milk</dt>
  <dd>- white cold drink</dd>
</dl>
```

## Nested Lists

Lists can be nested (list inside list)

### Example:

```
<ul>
  <li>Coffee</li>
  <li>Tea
    <ul>
      <li>Black tea</li>
      <li>Green tea</li>
    </ul>
  </li>
  <li>Milk</li>
</ul>
```

# Boxes:

## What is Boxes?

The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content

## Border

A border that goes around the padding and content

## Margin

Clears an area outside the border. The margin is transparent

## Padding

Clears an area around the content. The padding is transparent

## Boxes Style

### Example

This `<div>` element will have a total width of 350px:

```
div {
  width: 320px;
  padding: 10px;
  border: 5px solid gray;
  margin: 0;
}
```

## Helpful resources:

- [HTML Tutorial](https://www.w3schools.com/html/)
- [HTML Documentation](https://developer.mozilla.org/en-US/docs/Web/HTML)
