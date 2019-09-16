---
layout: post
title: "apuntes css"
comments: false
description: "apuntes css"
keywords: "apuntes, css"
---

vincular hoja de estilos

Linking the CSS File

When HTML and CSS code are in separate files, the files must be linked. Otherwise, the HTML file won't be able to locate the CSS code, and the styling will not be applied.

You can use the <link> element to link HTML and CSS files together. The <link> element must be placed within the head of the HTML file. It is a self-closing tag and requires the following three attributes:

href — like the anchor element, the value of this attribute must be the address, or path, to the CSS file.
type — this attribute describes the type of document that you are linking to (in this case, a CSS file). The value of this attribute should be set to text/css.
rel — this attribute describes the relationship between the HTML file and the CSS file. Because you are linking to a stylesheet, the value should be set to stylesheet.
When linking an HTML file and a CSS file together, the <link> element will look like the following:

<link href="https://www.codecademy.com/stylesheets/style.css" type="text/css" rel="stylesheet">
Note that in the example above the path to the stylesheet is a URL:

https://www.codecademy.com/stylesheets/style.css
Specifying the path to the stylesheet using a URL is one way of linking a stylesheet.

If the CSS file is stored in the same directory as your HTML file, then you can specify a relative path instead of a URL, like so:

<link href="./style.css" type="text/css" rel="stylesheet">
Using a relative path is very common way of linking a stylesheet.

´´´
<!DOCTYPE html>
<html>

<head>
  <title>Vacation World</title>
  <link href="style.css" type="text/css" rel="stylesheet">
</head>
 <link href="style.css" type="text/css" rel="stylesheet">
 ´´´

 ### Diferencia entre tags, class y ID

 CSS puede aplicar a tags específicos del html o a classes o a ID el orden de prioridad es ID->class->tag
