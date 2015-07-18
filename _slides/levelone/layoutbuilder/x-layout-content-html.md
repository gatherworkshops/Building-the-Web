---
title: x-layout-content-html
section: layoutbuilder
layout: slide
class: centered-slide

notes: |
  A section is just another layout rectangle, like header.

  It has no design by itself, it's just an invisible box to hold content.

  First we will put in some content, then we will design the section.

  Notice that we have given this section a name, or "class".

---

## Content Section

Add to your `index.html`, on a new line after your closing `</header>` tag:

    <section class="page-content">

        <h2>Hello there, amazing person!</h2>

        <p>
        This is a site all about my favourite stuff, 
        thanks so much for visiting.
        </p>

    </section>

We will use this `page-content` section on every page,<br>
but we will change the content inside it for each page.
