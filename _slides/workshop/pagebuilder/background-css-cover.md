---
title: background-css-cover
section: pagebuilder
layout: slide
class: default-slide

notes: |
  We already have an 'html' tag on the page, so we can style it from the CSS using the keyword 'html'.

  We use this one for adding a background as it is the outermost element - it contains everything else on the page so we know the bg will go behind everything else.

---

## Full-Screen Background

You can make a full-screen background using code like this:

    html {
        background-color: black;
        background-image: url('http://tiny.cc/grassy-field');
        background-size: cover;
        background-attachment: fixed;
    }

Make sure to choose a nice large image!