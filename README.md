# HW8 T1

This project demonstrates basic HTML and CSS styling. The HTML file contains various elements that are styled using the CSS file.

## HTML

The HTML file includes:

- A `div` element with the class `text-box` containing multiple `h3` and `p` elements.
- Each `p` element has specific text that indicates the color it should be styled in.

## CSS

The CSS file includes the following styles:

- The first `h3` element is styled with the color pink.
- The `p` element with the ID `greycol` is styled with the color grey.
- The `p` element inside a `div` within the `text-box` class is styled with the color red.
- The seventh child `p` element is styled with the color green.
- The `p` element with the class `yellow` is styled with the color yellow.

## Usage

To use this project, simply open the `index.html` file in a web browser. The styles defined in the `style.css` file will be applied to the HTML elements.

## Example

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <link rel="stylesheet" href="style.css" />
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>HW8 T1</title>
  </head>
  <body>
    <div class="text-box">
      <h3>Пофарбуйте мене в рожевий колір (color:pink).</h3>
      <p>Даний елемент має залишитись неоформленим.</p>
      <p id="greycol">Пофарбуйте мене в сірий колір (color:grey).</p>
      <div>Даний елемент має залишитись неоформленим.</div>
      <div><p>
