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
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <div class="first">First</div>
    <div>Div</div>
  </body>
</html>
```

# Css 9 
```
div {
  background-color: red;
  margin: 10px 0;
}
.first {
  visibility: hidden; //بتسيب مكان الها وبتحجزه
//display: none; //حيختفي من مكان التصميم كله
}
```

# Html 10
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <div class="one">One</div>
    <div class="two">Two</div>
    <div class="three">Three</div>
    <div class="four">Four</div>
    <p class="my-p">This Is P</p>
  </body>
</html>
```

# Css 10
```
.one {
  border-bottom: 2px solid red;
  color: red;
}
.two {
  border-bottom: 2px solid green;
  color: green;
}
.three {
  border-bottom: 2px solid blue;
  color: blue;
}
.four {
  border-bottom: 2px solid black;
  color: black;
}
.one,
.two,
.three,
.four,
.my-p {
  padding: 15px;
  margin: 12px 0;
  background-color: #ededed;
}
```

# Html 11
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
      <h2>Title</h2>
      <p>Paragraph Inside Div</p>
      <p class="special">Paragraph Inside Div With Class</p>
    </div>
    <p class="special">Paragraph Outside Div</p>
  </body>
</html>
```

# Css 11
```
div .special {
  color: red;
}
```
# Html 12
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <div> Mohamed</div>
    <hr>
    <div> Mohamed Ahmed</div>
    <hr>
    <div> Mohamed Ahmed Sayed</div>
  </body>
</html>
```

# Css 12 
```
div {
  background-color: red;
  padding: 10px;
  display: inline-block;
  max-width: 400px;
//width: fit-content; //على حجم النص
}
```
# Html 13
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
      Lorem ipsum dolor sit amet consectetur adipisicing elit.
      Inventore sit molestiae, corrupti at quae debitis dicta
      adipisci unde, nemo, veritatis error. Cupiditate,
      deserunt maiores assumenda ut quod voluptate adipisci repellat.
    </div>
  </body>
</html>
```

# Css 13
```
div {
  width: 150px;
  height: 150px;
  background-color: #EEE;
  margin: 20px auto;
  border-radius: 6px;
  overflow: scroll;
}
```

# Html 14
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <div>Elzero Web <img decoding="async" src="https://via.placeholder.com/60" alt=""> School</div>
  </body>
</html>
```

# Css 13
```
div {
  background-color: #f9f9f9;
  text-align: center;
  direction: ltr;
}
img {
  vertical-align: middle;
}
```

# Html 14
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
      <h3>Elzero Web School</h3>
      <p>Welcome To The Website</p>
    </div>
  </body>
</html>
```

# Css 14
```
div {
  text-align: center;
  padding: 20px;
  background-color: #EEE;
  font-size: 20px;
  border: 2px solid blue;
}
div p {
  border: 2px solid;
  border-color: inherit;
  padding: inherit;
}
```
ا

