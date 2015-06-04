---
title: background-css-tile
section: layoutbuilder
layout: slide
class: default-slide

notes: |
  To make a tiled background, we need some very basic CSS.
  
  Put the CSS code for the tiled background into your `style.css` file.
  
  We are adding the background to our `html` element, because that element contains everything else on the page. Adding a background to it will make the background fill up all the space behind everything else on the page.

---


## Tiled Background

Here's some CSS code for a repeating background.

**In your CSS:**

    html {
        background-image: url('images/ravens-tile.gif');
    }

Make sure to choose an image which tiles nicely!
