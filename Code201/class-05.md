![htmlcss](https://i.ibb.co/JQnNcFF/1-l4x-ICb-IIYlz1-OTym-WCo-UTw-removebg-preview.png)

# Web Page Structure

JavaScript is one of the 3 languages all web developers must learn:

1. **HTML** to define the content of web pages
2. **CSS** to specify the layout of web pages
3. **JavaScript** to program the behavior of web pages

# Images:

## Adding Images

To add an image into the page you need to use an`<img>`element.

```
<img src="images/cat.jpg" alt="cat"/>
```

## attributes :

- `src` : This tells the browser where it can find the image file.
- `alt` : This provides a text description of the image which describes the image if you cannot see it.
- `title` : You can also use the title attribute with the `<img>` element.
- `height` : This specifies the height of the image in pixels.
- `width` : This specifies the width of the image in pixels.
- `align` : This was commonly used to indicate how the other parts of a page should flow around an image.

## Three Rules for Creating Images

1. Save images in the right format.
2. Save images at the right size.
3. Use the correct resolution.

## Image Formats:

### JPEG

Whenever you have many different colors in a picture you should use a JPEG.

- JPEG images can support around 16 million colours. This is what makes them suitable for storing images of natural scenes.
- JPEG images don’t support transparency and are hence not usable for such cases.

### GIF

when saving images with few colors or large areas of the same color.

- Only GIF supports animation.
- GIF images support transparency by declaring a single colour in the colour palette as transparent .

### PNG

PNG images mainly have two modes — PNG8 and PNG24. PNG8 can support upto 256 colours whereas PNG24 can handle upto 16 million colours like a JPEG image.

- PNG images support transparency in two ways — inserting an alpha channel that allows partial transparency or by declaring a single colour as transparen.

## Colors

![color](https://www.w3schools.com/colors/img_colormap.gif)
### Colors methods:

- **Hexadecimal colors :** Hex values represent values for red, green, and blue in hexadecimal code.
- **RGB colors :** Values for red, green, and blue are expressed as numbers between 0 and 255.
- **RGBA colors :** RGBA color values are an extension of RGB color values with an alpha channel - which specifies the opacity for a color.
- **HSL colors :** CSS3 introduces an entirely new and intuitive way to specify colors using hue, saturation, and lightness values.
- **HSLA colors :** HSLA color values are an extension of HSL color values with an Alpha channel - which specifies the opacity for a color.
- **Color names :** Colors are represented by predefined names.
- **Currentcolor keyword :** The currentcolor keyword refers to the value of the color property of an element.

# Texts

## Typeface Terminology

- **Serif**
  > Serif fonts have extra details on the ends of the main strokes of the letters. These details are known as serifs.
- **Sans-Serif**
  > Sans-serif fonts have straight ends to letters, and therefore have a much cleaner design.
- **Monospace**
  > Every letter in a monospace (or fixed-width) font is the same width.
- **Cursive**
  > Cursive fonts either have joining strokes or other cursive characteristics, such as handwriting styles.
- **Fantasy**
  > Fantasy fonts are usually decorative fonts and are often used for titles. They're not designed for long bodies of text.

## Units of Type Size

- Pixels
- Percentages
- EMS

### Attribute Selectors

| Selector  | Meaning                                                                                 | Example         |
| --------- | --------------------------------------------------------------------------------------- | --------------- |
| Existence | [] Matches a specific attribute                                                         | p[class]        |
| Equality  | [=] Matches a specific attribute with a specific value                                  | p[class="dog"]  |
| Space     | [~=] Matches a specific attribute whose value appears in a spaceseparated list of words | p[class~="dog"] |
| Prefix    | [^=] Matches a specific attribute whose value begins with a specific string             | p[attr^"d"]     |
| SubString | [*=] Matches a specific attribute whose value contains a specific substring             | p[attr*"do"]    |
| Suffix    | [$=] Matches a specific attribute whose value ends with a specific string               | p[attr$"g"]     |

## Text Formats

- font-weight
- font-style
- text-transform
- text-decoration
- line-height
- letter-spacing and word-spacing
- text-align
- vertical-align
- text-indent
- text-shadow

### Helpful resources:

- [HTML Documentation](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [What is CSS?](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)
- [Color Codes](https://htmlcolorcodes.com/)
- [CSS Text](https://www.w3schools.com/css/css_text.asp)
