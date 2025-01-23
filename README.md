# HW8 T1

This project demonstrates basic HTML and CSS styling.

## HTML

The HTML file includes:

- A `div` with the class `text-box` containing multiple `h3` and `p` elements.
- Each `p` element has specific text indicating its color.

## CSS

The CSS file styles the elements as follows:

- The first `h3` is pink.
- The `p` with the ID `greycol` is grey.
- The `p` inside a `div` within the `text-box` is red.
- The seventh `p` is green.
- The `p` with the class `yellow` is yellow.

## Usage

Open the `index.html` file in a web browser to see the styles applied.

## Example

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>HW8 T1</title>
    <style>
      h3:first-of-type {
        color: pink;
      }

      #greycol {
        color: grey;
      }

      .text-box div p {
        color: red;
      }

      .text-box p:nth-of-type(7) {
        color: green;
      }

      .yellow {
        color: yellow;
      }
    </style>
  </head>
  <body>
    <div class="text-box">
      <h3>Пофарбуйте мене в рожевий колір (color:pink).</h3>
      <p>Даний елемент має залишитись неоформленим.</p>
      <p id="greycol">Пофарбуйте мене в сірий колір (color:grey).</p>
      <div>
        Даний елемент має залишитись неоформленим.
        <p>Пофарбуйте мене в червоний колір (color:red).</p>
      </div>
      <p>Даний елемент має залишитись неоформленим.</p>
      <p>Даний елемент має залишитись неоформленим.</p>
      <p>Даний елемент має залишитись неоформленим.</p>
      <p>Даний елемент має залишитись неоформленим.</p>
      <p>Даний елемент має залишитись неоформленим.</p>
      <p>Пофарбуйте мене в зелений колір (color:green).</p>
      <p class="yellow">Пофарбуйте мене в жовтий колір (color:yellow).</p>
    </div>
  </body>
</html>
