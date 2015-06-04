---
title: template-files
section: layoutbuilder
layout: slide
class: centered-slide

notes: |
  
  The `images` folder is where you should upload any images you want to use in your website.

  The `index.html` contains all the HTML code for your home page. If you want to add content to your home page, you would edit this file.

  The `style.css` contains all the CSS code for your whole website. If you want to change how anything looks on any page, you would edit this file.

---

## Template Files

<br>

<div class="three-table">

<div>

<img width="50%" src="{{ site.baseurl }}/slides/workshop/layoutbuilder/images/folder.svg">

<h3>images</h3>
<p>All your images go in this folder.</p>
</div>

<div>

<img width="50%" src="{{ site.baseurl }}/slides/workshop/layoutbuilder/images/html-file.svg">

<h3>index.html</h3>
<p>HTML code for your home page.</p>
</div>

<div>

<img width="50%" src="{{ site.baseurl }}/slides/workshop/layoutbuilder/images/css-file.svg">

<h3>style.css</h3>
<p>CSS code for your whole website.</p>
</div>

</div>

<style>
.three-table div {
    box-sizing: border-box;
    float: left;
    width: 33%;
    border-left: 2px dotted #001E39;
    min-height: 200px;
    padding: 10px;
}

.three-table div p {
    font-size: 75%;
}

.three-table div:first-of-type {
    border: none;
}
</style>