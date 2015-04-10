---
title: gallery-image-css
section: htmlcssbasics
layout: slide
class: default-slide

notes: |
  This style says "find a block with the class `gallery`, then find every `img` element inside it and apply these styles"

---

## Gallery Image Styles

We can also use a trick to style the images *inside* the gallery section, without adding a class to every single one.

**In your CSS, on a new line:**

    .gallery-section img {
      border: 5px solid white;
      height: 150px;
    }

Your gallery images should now have white borders and all be the same height.