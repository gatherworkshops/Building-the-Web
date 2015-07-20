---
title: css-background
section: layoutbuilder
layout: slide
class: centered-slide

notes: |

  A page background can really set the tone of a website, so let's start with that.

  You can choose between a tiled or a full-screen background for your website.

  Download one of the same images from the slide to get started. You can replace it with your own image once you've got it working.

  The next slide has example code for tiled backgrounds, and the slide after it has example code for a full-screen background.

  Choose one or the other for your site.

---


## Choose a Background Type

<div class="two-table">

<div>
<img src="/Building-the-Web/slides/workshop/layoutbuilder/images/ravens-tile.gif" height="220">
<h3>Tiled</h3>
<p>A smaller image which repeats<br>
to fill the whole page.</p>
</div>

<div>
<img src="/Building-the-Web/slides/workshop/layoutbuilder/images/tree-cover.jpg" height="220">
<h3>Full-Screen</h3>
<p>A large image which stretches<br>
to fill the whole page.</p>
</div>

</div>

<div class="clearer"></div>

_Right-click an image and "Save Image As..."_

<style>
.two-table {
  padding-bottom: 30px;
}

.two-table div {
    box-sizing: border-box;
    float: left;
    width: 49%;
    border-left: 2px dotted #001E39;
    min-height: 200px;
    padding: 10px;
}

.two-table div p {
    font-size: 75%;
}

.two-table div:first-of-type {
    border: none;
}

.clearer {
  clear: both;
}
</style>
