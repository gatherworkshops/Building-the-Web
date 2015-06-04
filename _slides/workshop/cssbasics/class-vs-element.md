---
title: class-vs-element
section: cssbasics
layout: slide
class: default-slide

notes: |
  :)

---

## Element Selectors

Rather than always using classes, we can also choose to style all HTML elements of the same type.

**At the top of your CSS, on a new line:**

    header,
    section {
      width: 700px;
      margin-left: auto;
      margin-right: auto;
      line-height: 130%;
    }

All your sections (and your header) should now be centered on the page.
