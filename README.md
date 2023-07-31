# CssCourse

# Html 1
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <!-- External Style -->
    <link rel="stylesheet" href="css/master.css" />
    <!-- Internal Style -->
    <style>
      .special {
        color: green;
      }
    </style>
  </head>
  <body>
    <p style="color: purple">This Is Paragraph</p>
    <p>This Is Paragraph</p>
    <p class="special">This Is Paragraph</p>
    <p>This Is Paragraph</p>
  </body>
</html>
```
# Css 1
```
/*
  Target All Paragraphs
*/
p {
  color: red;
}
```

# Html 2
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
    <link rel="stylesheet" href="css/library.css" />
    <link rel="stylesheet" href="css/rtl.css" />
  </head>
  <body>
    <div>Div</div>
    <div class="_test">Div</div>
    <div id="test">Div</div>
  </body>
</html>
```

# Css 2

```
._test {
  color: red;
}
.user-test {
  color: red;
}
```
# Html 3
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <div>
      <h2>Product Title</h2>
      <p>This Is Paragraph</p>
    </div>
  </body>
</html>
```

# Css 3

```
div {
  background-color: red; /* Color Name */
  background-color: rgb(0 0 0 / 50%); /* Red, Green, Blue, Alpha Channel */
  background-color: #FF0000; /* Color Hex Code */
  background-image: url("../imgs/learn-programming.png");
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: left top;
  background-size: auto;
}
```

# Css 4

```
div {
  background-color: #DDD;

  /* Top Right Bottom Left */
  /* 10px 10px 10px 10px */
  /* padding: 10px; */

  /* Top Right Bottom Left */
  /* 10px 20px 10px 20px */
  /* padding: 10px 20px; */

  /* Top Right Bottom Left */
  /* 10px 20px 15px 20px */
  /* padding: 10px 20px 15px; */

  padding-bottom: 10px;
  padding-top: 10px;
}
```
# Css 5
```
div {
  background-color: #DDD;
  padding: 10px;
  width: 70%;
  margin: auto;
}
```

#Css 6
```
div {
  background-color: #DDD;
  padding: 10px;
  width: 70%;
  margin: auto;
  border-width: 10px;
  border-color: red;
  border-style: solid;
  border: 10px solid red;
}
```

# Css 7
```
div {
  background-color: #DDD;
  width: 300px;
  padding: 10px;
  outline: 10px solid red;
  border: 10px solid blue;
}
```

# Html 8
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <div>Div => Block</div>
    <div>Div => Block</div>
    <div>Div => Block</div>

    <span>Span => Inline</span>
    <span>Span => Inline</span>
    <span>Span => Inline</span>
  </body>
</html>
```
# Css 8
```
/*

  Block

  - Take Full Width If No Width
  - Add Line Break
  - Respect Padding, Margin, Width, Height

  Inline

  - Do Not Repsepct Width, Height
  - Respect Padding And Margin [ Just Wight + Left ]
  - Do Not Add Line Break
  - Allow Elements Before And After It in The Same Line

  Inline-Block

  - Allow Elements Before And After It in The Same Line
  - Respect Padding, Margin, Width, Height

*/

span {
  background-color: #EEE;
  display: inline-block;
}
```

# Html 9
```

```

# Css 9 
```

```
