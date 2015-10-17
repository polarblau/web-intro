---
layout: chapter
title: HTML
permalink: /html/
next: /css/
---

[HTML][html] is a markup language for describing the structure of web pages. HTML is made out of [elements][html-elements] which are marked using a start tag (`<title>`) and end tag (`</title>`). Between the start and end tags you can put text and other elements. The start tags may contain [attributes][html-attributes] (`<img src="picture.jpg">`). For some elements the end tag is not needed.


## Minimal HTML page

The following code shows the minimal structure of a HTML page.

Create a folder called `MyAwesomeSite` on your computer's desktop. This will be your project folder where to put all the files you create in this tutorial.

Copy the following HTML code into your text editor and save it as `my-page.html` into your project folder. Then open the file in your web browser.

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>title goes here</title>
</head>
<body>

<p>body goes here</p>

</body>
</html>
```

It should look like this:

![Minimal HTML page](minimal-page.png)

[View solution](https://github.com/orfjackal/web-intro-project/commit/a44ee69891389e49eee70ede6323cd9c387425c5)


## Basic HTML elements

Edit the page you just created to say a few things about yourself.

Create a heading with `<h1>some text</h1>`, one or more paragraphs with `<p>some text</p>` and a picture using `<img src="picture.jpg" alt="alternative text">` (if you don't have a picture of yourself, you can use [this one](http://railsgirls.com/images/ruby-100.png)). All visible elements like these will go between `<body>` and `</body>`. Also change the page title.

You can find out more information about the [`<h1>`][html-h1], [`<p>`][html-p], [`<img>`][html-img] and all other possible HTML elements in the [HTML element reference][html-elements].

![Basic HTML Elements](basic-elements.png)

[View solution](https://github.com/orfjackal/web-intro-project/commit/9be6966443affc4395cb5327ee411d5251026dd9)


[html]: https://developer.mozilla.org/en-US/docs/Web/HTML
[html-elements]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element
[html-attributes]: https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes
[html-h1]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements
[html-p]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p
[html-img]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img
