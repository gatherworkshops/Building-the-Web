---
title: background-css-cover
section: pagebuilder
layout: slide
class: default-slide

notes: |
  To make a full screen background, we need to add two extra lines.

  We still use `background-image` in the same way, but we also add `background-size` and `background-attachment`.

  `background-size: cover;` tells the CSS to `cover` the whole html elements with the picture. It stretches the image to fit.

  `background-attachment: fixed;` tells the CSS to make page content move over top of the background, and keep the background `fixed` in one place. 

---

## Full-Screen Background

Here's some code for a full-screen background.

**In your CSS:**

    html {
        background-image: url('images/background.jpg');
        background-size: cover;
        background-attachment: fixed;
    }

Make sure to choose a nice large image!