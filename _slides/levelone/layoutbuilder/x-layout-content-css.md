---
title: x-layout-content-css
section: layoutbuilder
layout: slide
class: centered-slide

notes: |
  
  Our content is on the page, but it is just kind of... floating.

  By adding some CSS, we can make our content section visible and start working on how we'd like it to look.

  In our HTML, we gave our section the class `page-content`, so we can use that name to apply styling from our CSS code.

  The blank line is just to split up the layout stuff from the text design stuff, it doesn't affect the code.

---

## Content Section Design

Add to your `style.css`:

    .page-content {
        background-color: #222222;
        padding: 30px;
        width: 700px;
        margin: 0 auto;
        margin-top: 30px;

        color: #FFFFFF;
        font-size: 14px;
        line-height: 130%;
    }

This code will give you a starting point to begin<br>
designing your content section.