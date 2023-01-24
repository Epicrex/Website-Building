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
