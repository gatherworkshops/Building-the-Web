---
title: html-head
section: layoutbuilder
layout: slide
class: default-slide

notes: |
  Click on your `index.html` and let's take a quick look at the code.

  The `head` section of a web page contains information about your page. It _doesn't_ contain anything which is actually visible on the page.

  Be careful, `head` and `header` are two very different tags!

  The `title` is what shows up in your browser tab.

  The `link` is to the stylesheet which will contain our CSS code.

  You won't be able to see your title in CloudCannon.

---


## HTML Head

Every web page should have a `head` section.

    <!-- head only used by the browser -->
    <head>
        <title>My Page Title</title>
        <link rel="stylesheet" href="style.css">
    </head>

The `title` is the text which shows up<br>
in your browser's tab bar.

The `link` is to the stylesheet which will contain our CSS code.
