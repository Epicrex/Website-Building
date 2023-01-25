```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Tab Name</title>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <h1>One</h1>
        <h1 class = "h1Example">Two</h1>
    </body>
</html>    
```
In this example the external style method is used. one can link multiple css files at once. Always set the "rel" of the link to "stylesheet".

```css
body {
    font-family: Segoe UI;
}

h1 {
    background-color: red;
}

.h1Example {
    background-color: blue;
}

```


# Div Tag



# Other Tags
Normal/ Paragraph
```html
<p>Normal</p>
```
**Bold**
```html
<b>Bold</b>
```
__Italic__
```html
<i>Italic</i>
```
__Emphasized__
```html
<em>Emphasized</em>
```
Marked (like highlighted with a marker)
```html
<mark>Marked</mark>
```
~~Deleted~~
```html
<del>Deleted</del>
```
<ins>Inserted</ins>
```html
<ins>Inserted</ins>
```
Small (A bit smaller text)
```html
<small>Small</small>
```
This is <sub>Subscript</sub>
```html
<sub>Subscript</sub>
```
This is <sup>Superscript</sup>
```html
<sup>Superscript</sup>
```
<h3>Header</h3> (Ranges from h1 to h6. h1 being the biggest)

```html
<h2>Header</h2>
```

Pre Formated (leaves the text as is)
```html
<pre>
pre 

formated
</pre>
```

Break<br>Break
```html
<p>Break<br/>Break</p>
```

<span>Span 1</span>
<span>Span 2</span>

```html
<span>Span 1</span>
<span>Span 2</span>
```

<p>Paragraph 1</p>
<p>Paragraph 2</p>

```html
<p>Paragraph 1</p>
<p>Paragraph 2</p>
```

<span>Span and<br>brek</span>

```html
<span>Span and<br>brek</span>
```

Span and paragraph are both similar, but paragraph adds big gaps (note that these gaps arent selectable, and also allot biger than gaps from break).

---

Link (The target defines the action. "_self" will open the link in the same tab and "_blank" will open it in a new tab  )
```html
<a href="https://www.google.com/" target="_self">I'm a link</a>
```

Open Link in mail client (Will open the link from the href in the os default mail clinet)
```html
<a href="mailto:someone@example.com">Email Me</a>
```

Show image that's clikcable link
```html
<a href="https://www.google.com/" target="_blank"> <img src="https://i.imgur.com/xZTQEP9.png" alt="Image"> </a>
```

Image (The alt parameter is optional)
```html
<img src="https://i.imgur.com/EQmmDaE.png" alt="Image">
```

Image with custom width
```html
<img src="https://i.imgur.com/EQmmDaE.png" alt="Image" width="35">
```

Abbreviation (In this example when hovering the T one will see "Test")
```html
<p>The <abbr title="Test">T</abbr> defines abbreviation</p>
```

# Attributes

<p title="I'm a tooltip">Tooltip</p>

```html
<p title="I'm a tooltip">Hover me for tooltip.</p> 
```

```html
```
```html
```
