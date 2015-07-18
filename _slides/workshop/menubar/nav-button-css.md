---
title: nav-button-css
section: menubar
layout: slide
class: centered-slide

notes: |
  
  The first CSS rule says how we want the menu buttons to look.

  The second CSS rules says how we want the buttons to look when we move our mouse pointer over them, when we "hover".

  You can change these values to make your buttons look however you like.

---

## Navigation Button Styles

In your CSS:

    .main-menu a {
        background-color: #00FF00;
        border-color: #00DD00;
        font-weight: bold;
        display: inline-block;
        padding: 5px 10px;
    }

    .main-menu a:hover {
        background-color: #00DD00;
        color: #FFFFFF;
    }


_Style your links to look like buttons_