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

# Css 6
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

# Css 14
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

# Html 15
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

# Css 15
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
# Html 16
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <div class="with-ser">Welcome To Elzero Web School, Hello F</div>
    <div class="san-ser">Welcome To Elzero Web School, Hello F</div>
  </body>
</html>
```

# Css 16
```
.with-ser {
  font-family: 'Times New Roman', Times, serif;
}
.san-ser {
  font-family: Arial, Helvetica, sans-serif;
}
.with-ser,
.san-ser {
  background-color: #EEE;
  padding: 10px;
}
```

# Html 17
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
      Elzero Web School
      <span>Test</span>
    </div>
  </body>
</html>
```

# Css 17
```
body {
  font-size: 40px;
}
div {
  font-size: 5vw;
}
div span {
  font-size: 2rem;
}
```

# Html 18
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <div class="parent">
      <div>Product One</div>
      <div>Product Two</div>
      <div>Product Three</div>
      <div>Product Four</div>
    </div>
    <div class="clear"></div>
    <p>This Is P For Testing Float</p>
  </body>
</html>
```
# Css 18
```
.parent {
  background-color: red;
  padding: 10px;
}
.parent div {
  padding-top: 10px;
  padding-bottom: 10px;
  text-align: center;
  background-color: #eee;
  width: 25%;
  float: left;
}
.clear {
  clear: both;
}
```

# Html 19
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <div>Product One</div>
    <div>Product Two</div>
    <div>Product Three</div>
    <div>Product Four</div>
  </body>
</html>
```

# Css 19
```
body {
  margin: 0;
}
div {
  padding-top: 10px;
  padding-bottom: 10px;
  text-align: center;
  background-color: #eee;
  float: left;
  width: calc((100% - 60px) / 5);
  margin-left: 10px;
}
/*
  Content Width Is: 100%
  6 Spaces  10px * 6 => 60px From Content Width
  100% - 60px Available Space
  5 Elements The Width Is: (100% - 60px) / 5
*/
```
# Html 20
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <table>
      <thead>
        <tr>
          <td>Name</td>
          <td>Age</td>
          <td>Email</td>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Osama</td>
          <td>38</td>
          <td>o@nn.sa</td>
        </tr>
        <tr>
          <td>Ahmed</td>
          <td>38</td>
          <td>o@nn.sa</td>
        </tr>
        <tr>
          <td>Sayed</td>
          <td>38</td>
          <td>o@nn.sa</td>
        </tr>
        <tr>
          <td>Ali</td>
          <td>38</td>
          <td>o@nn.sa</td>
        </tr>
      </tbody>
    </table>
  </body>
</html>
```

# Css 20
```
body {
  font-family: Arial, Helvetica, sans-serif;
}
table {
  width: 100%;
  border: 1px solid #CCC;
  border-spacing: 0;
}
table td {
  padding: 15px;
  background-color: #EEE;
  border: 1px solid #CCC;
}
table thead td {
  background-color: #f44336;
  color: #FFF;
  font-weight: bold;
  text-align: center;
  border-color: #F35246;
}
```

# Html 21
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <div class="one">Normal Element</div>
    <hr />
    <div class="two"></div>
    <p></p>
    <hr />
    <a href="https://google.com">Link 1</a>
    <a href="https://twitter.com">Link 2</a>
    <a href="https://youtube.com">Link 3</a>
    <a href="https://linkedin.com">Link 4</a>
    <hr />
    <form action="">
      <div>
        <input class="in" type="text" />
      </div>
      <div>
        <input class="ch" type="checkbox" />
        <label for="">Testing Check</label>
      </div>
    </form>
  </body>
</html>
```

# Css 21
```
.one {
  background-color: red;
  color: white;
}
.two {
  background-color: #EEE;
  width: 100px;
  height: 100px;
}
a {
  color: green;
  text-decoration: none;
}
a:hover {
  color: red;
}
a:visited {
  color: blue;
}
:empty {
  border: 10px solid red;
}
.ch:checked {
  display: none;
}
.in:focus {
  border-color: red;
  outline: none
}
```

# Html 22
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <div class="parent">
      <div class="user">O</div>
      <div class="one">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum labore culpa dolores, autem voluptatum atque,
        in dolore asperiores facilis libero dolorum magni iure doloribus quae pariatur! Similique ipsum nobis quos.
      </div>
    </div>
    <div class="parent">
      <div class="user">A</div>
      <div class="one">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum labore culpa dolores, autem voluptatum atque,
        in dolore asperiores facilis libero dolorum magni iure doloribus quae pariatur! Similique ipsum nobis quos.
      </div>
    </div>
    <div class="parent">
      <div class="user">E</div>
      <div class="one">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum labore culpa dolores, autem voluptatum atque,
        in dolore asperiores facilis libero dolorum magni iure doloribus quae pariatur! Similique ipsum nobis quos.
      </div>
    </div>
  </body>
</html>
```

# Css 22
```
.parent {
  margin-bottom: 20px;
  overflow: hidden;
}
.one {
  background-color: #eee;
  padding: 10px;
  width: 600px;
  float: left;
  position: relative;
}
.one::after {
  content: "";
  position: absolute;
  width: 5px;
  height: 100%;
  right: -10px;
  top: 0;
  background-color: #009688;
}
.one::before {
  content: "";
  position: absolute;
  top: 50%;
  left: -20px;
  width: 0;
  height: 0;
  background-color: white;
  margin-top: -10px;
  border-style: solid;
  border-width: 10px;
  border-color: transparent #009688 transparent transparent;
}
.user {
  background-color: #eee;
  width: 50px;
  margin-right: 20px;
  padding: 10px;
  height: 55.5px;
  float: left;
  font-size: 50px;
  text-align: center;
}
```

# Html 23
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <div class="parent">
      <div class="user">O</div>
      <div class="one" data-text="Something">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum labore culpa dolores, autem voluptatum atque,
        in dolore asperiores facilis libero dolorum magni iure doloribus quae pariatur! Similique ipsum nobis quos.
      </div>
    </div>
    <div class="parent">
      <div class="user">A</div>
      <div class="one">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum labore culpa dolores, autem voluptatum atque,
        in dolore asperiores facilis libero dolorum magni iure doloribus quae pariatur! Similique ipsum nobis quos.
      </div>
    </div>
    <div class="parent">
      <div class="user">E</div>
      <div class="one">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum labore culpa dolores, autem voluptatum atque,
        in dolore asperiores facilis libero dolorum magni iure doloribus quae pariatur! Similique ipsum nobis quos.
      </div>
    </div>
    <ul>
      <li>One</li>
      <li>One</li>
      <li>One</li>
      <li>One</li>
      <li>One</li>
    </ul>
  </body>
</html>
```

# Css 23
```
.parent {
  margin-bottom: 20px;
  overflow: hidden;
  counter-increment: members-counter;
}
.one {
  background-color: #eee;
  padding: 10px;
  width: 600px;
  float: left;
  position: relative;
}
.one::before {
  content: attr(data-text);
  display: none;
}
.one::after {
  content: counter(members-counter);
  position: absolute;
  background-color: red;
  color: white;
  width: 20px;
  height: 20px;
  text-align: center;
  font-weight: bold;
  right: -10px;
  top: 50%;
  margin-top: -10px;
}
.user {
  background-color: #eee;
  width: 50px;
  margin-right: 20px;
  padding: 10px;
  height: 55.5px;
  float: left;
  font-size: 50px;
  text-align: center;
}
ul {
  list-style: none;
}
ul li {
  position: relative;
}
ul li::before {
  content: "";
  width: 0;
  height: 0;
  position: absolute;
  left: -20px;
  top: 50%;
  margin-top: -10px;
  border-width: 10px;
  border-style: solid;
  border-color: transparent #009688 transparent transparent;
}
```

# Html 24
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <div></div>
  </body>
</html>
```

# Css 24
```
div {
  width: 150px;
  height: 150px;
  background-color: red;
  margin: 20px auto;
  border-radius: 6px;
  /* border-top-left-radius: 20px 20px;
  border-bottom-right-radius: 20px; */
}
```

# Html 25
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <div>Element</div>
  </body>
</html>
```

# Css 25
```
div {
  padding: 20px;
  background-color: #eee;
  margin: 20px auto;
  width: 300px;
  box-shadow:
    0 0 10px 0 #F10000,
    0 0 10px 0 #000,
    0 0 10px 0 #080,
    0 0 10px 0 #00f,
    0 0 10px 0 yellow;
}
```

# Html 26
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <div class="parent">
      <div class="one">One</div>
      <div class="one">One</div>
    </div>
  </body>
</html>
```

# Css 26
```
* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
.parent {
  width: 600px;
  overflow: hidden;
  margin: 20px auto;
  padding: 20px;
  background-color: #ddd;
}
.one {
  background-color: #eee;
  width: 300px;
  float: left;
  padding: 10px;
  border: 1px solid red;
}
```

# Html 27
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
  </body>
</html>
```

# Css 27
```
* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
.one {
  background-color: #EEE;
  width: 200px;
  height: 100px;
  transition-duration: 1s;
  transition-delay: 0.2s;
  transition-property: width;
  transition-timing-function: ease-in-out;
  transition: all 2s 0.5s linear;
}
.one:hover {
  width: 280px;
  height: 120px;
}
```

# Html 28
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <div class="one" style="background-color: red;">One</div>
  </body>
</html>
```

# Css 28
```
.one {
  background-color: #EEE !important;
}
```

# Html 29
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <div class="parent">
      <div class="one"></div>
      <div class="two">
        <div class="up"></div>
        <div class="down"></div>
      </div>
    </div>
  </body>
</html>
```

# Css 29
```
/*
  The Margin Collapse
  [1] Only Vertical Margin Collapse
  [2] Bigger Margin Wins
  [3] Margin Collapsing With Elements Without Anything Between
  [4] Nesting Does Not Prevent Collapse
*/
.parent {
  overflow: hidden;
  margin: auto;
  width: 400px;
  height: 200px;
  padding: 10px;
  background-color: #eee;
}
.parent .one,
.parent .two {
  float: left;
  width: 50%;
  height: 100%;
}
.one {
  background-color: #ddd;
}
.two {
  background-color: #aaa;
}
.up {
  background-color: red;
  color: white;
  height: 80px;
  margin-bottom: 40px;
}
.down {
  background-color: green;
  color: white;
  height: 80px;
  margin-top: 40px;
}
```

# Html 30
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <div class="main">Main Div</div>
    <h2>Main Title</h2>
    <p>My Paragraph</p>
    <a href="#">My Link</a>
    <div class="local">Local</div>
  </body>
</html>
```

# Css 30
```
/*
  CSS Variables
  - Global Variable
  - Local Variable
  var(Variable Name, Fall Back Value)
*/

:root {
  --mainColor: blue;
  --mainPadding: 10px;
}
.main {
  background-color: var(--mainColor, black);
  color: white;
  padding: calc(20px + var(--mainPadding));
}
h2 {
  color: var(--mainColor);
  background-color: #eee;
  padding: var(--mainPadding);
}
p {
  color: var(--mainColor);
  border: 2px solid var(--mainColor);
  padding: var(--mainPadding);
}
a:hover {
  color: var(--mainColor);
}
.local {
  --mainColor: black;
  background-color: var(--mainColor);
  color: white;
}
```

# Html 31
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <h3>Flex</h3>
    <div class="flex">
      <div>One</div>
      <div>Two</div>
      <div>Three</div>
      <div>Four</div>
    </div>
    <hr />
    <h3>Float</h3>
    <div class="float">
      <div>One</div>
      <div>Two</div>
      <div>Three</div>
      <div>Four</div>
    </div>
  </body>
</html>
```

# Css 31
```
/*
  Flexible Box
  For Parent
  - display: flex => To Start Flexible Box
  - flex-direction: row => Default Value
  - flex-wrap: nowrap => Default Value
  - flex-flow: [Flex-Direction] + [Flex-Wrap]
*/

* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
.flex {
  background-color: #eee;
  width: 600px;
  padding: 20px;
  margin: 20px auto;
  display: flex;
  flex-direction: column;
}
.flex div {
  background-color: #f00;
  color: white;
  width: 25%;
  text-align: center;
  padding: 20px;
}
.float {
  overflow: hidden;
  background-color: #eee;
  width: 600px;
  padding: 20px;
  margin: 20px auto;
}
.float div {
  background-color: #f00;
  color: white;
  float: right;
  width: 25%;
  text-align: center;
  padding: 20px;
}
```

# Html 32
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <h3>Flex</h3>
    <div class="flex">
      <div class="one">One</div>
      <div class="two">Two</div>
      <div>Three</div>
    </div>
    <hr />
    <h3>Float</h3>
    <div class="float">
      <div class="one">One</div>
      <div class="two">Two</div>
      <div>Three</div>
    </div>
    <div class="center">Center</div>
  </body>
</html>
```

# Css 32
```
/*
  Flexible Box
  For Parent
  - display: flex => To Start Flexible Box
  - flex-direction: row => Default Value
  - flex-wrap: nowrap => Default Value
  - flex-flow: [Flex-Direction] + [Flex-Wrap]
  ---
  - justify-content: flex-start => Default Value
  - align-items: stretch => Default Value
*/

* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
.flex {
  background-color: #eee;
  width: 600px;
  padding: 20px;
  margin: 20px auto;
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
}
.flex div {
  background-color: #f00;
  color: white;
  width: calc(100% / 3);
  text-align: center;
  padding: 20px;
}
.flex .one,
.float .one {
  height: 80px;
}
.float {
  overflow: hidden;
  background-color: #eee;
  width: 600px;
  padding: 20px;
  margin: 20px auto;
}
.float div {
  background-color: #f00;
  color: white;
  float: right;
  width: calc(100% / 3);
  text-align: center;
  padding: 20px;
}
.center {
  background-color: blue;
  color: white;
  width: 300px;
  height: 200px;
  display: flex;
  justify-content: center;
  align-items: center;
}
```
# Html 33
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <h3>Flex</h3>
    <div class="flex">
      <div>One</div>
      <div>Two</div>
      <div>Three</div>
      <div>Four</div>
      <div>Five</div>
    </div>
  </body>
</html>
```

# Css 33
```
/*
  Flexible Box
  For Parent
  - display: flex => To Start Flexible Box
  - flex-direction: row => Default Value
  - flex-wrap: nowrap => Default Value
  - flex-flow: [Flex-Direction] + [Flex-Wrap]
  ---
  - justify-content: flex-start => Default Value
  - align-items: stretch => Default Value
  - align-content: stretch => Default Value
*/

* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
.flex {
  background-color: #eee;
  width: 600px;
  height: 400px;
  padding: 20px;
  margin: 20px auto;
  display: flex;
  flex-wrap: wrap;
  align-items: flex-start;
  align-content: space-between;
}
.flex div {
  background-color: #f00;
  color: white;
  width: calc(100% / 3);
  text-align: center;
  padding: 20px;
}
```

# Html 34
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <h3>Flex</h3>
    <div class="flex">
      <div>1</div>
      <div>2</div>
      <div>3</div>
      <div>4</div>
      <div>5</div>
      <div>6</div>
    </div>
  </body>
</html>
```

# Css 34
```
/*
  Flexible Box
  For Parent
  - display: flex => To Start Flexible Box
  - flex-direction: row => Default Value
  - flex-wrap: nowrap => Default Value
  - flex-flow: [Flex-Direction] + [Flex-Wrap]
  - justify-content: flex-start => Default Value
  - align-items: stretch => Default Value
  - align-content: stretch => Default Value
  For Child
  - flex-grow: 0 => Default Value
  - flex-shrink: 1 => Default Value
  - order: 0 => Default Value
*/

* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
.flex {
  background-color: #eee;
  width: 800px;
  padding: 20px;
  margin: 20px auto;
  display: flex;
}
.flex div {
  background-color: #f00;
  color: white;
  width: 80px;
  text-align: center;
  padding: 20px;
  margin-right: 5px;
  flex-grow: 1;
}
```

# Html 35
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <div class="flex">
      <div>1</div>
      <div>2</div>
      <div>3</div>
      <div>4</div>
      <div>5</div>
      <div>6</div>
    </div>
    <div class="in">In</div>
  </body>
</html>
```

# Css 35
```
/*
  Flexible Box
  For Parent
  - display: flex => To Start Flexible Box
  - flex-direction: row => Default Value
  - flex-wrap: nowrap => Default Value
  - flex-flow: [Flex-Direction] + [Flex-Wrap]
  - justify-content: flex-start => Default Value
  - align-items: stretch => Default Value
  - align-content: stretch => Default Value
  For Child
  - flex-grow: 0 => Default Value
  - flex-shrink: 1 => Default Value
  - order: 0 => Default Value
  - flex-basis: auto => Default Value
  - flex: [Flex Grow] [Flex Shrink] [Flex Basis] 0 1 Auto
*/

* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
.flex {
  background-color: #eee;
  width: 800px;
  padding: 20px;
  margin: 20px auto;
  display: inline-flex;
}
.flex div {
  background-color: #f00;
  color: white;
  width: 80px;
  text-align: center;
  padding: 20px;
  margin-right: 5px;
  flex-grow: 1;
}
.in {
  display: inline-block;
}
```

# Html 36
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <div class="flex">
      <div>1</div>
      <div>2</div>
      <div>3</div>
      <div>4</div>
      <div>5</div>
      <div>6</div>
    </div>
  </body>
</html>
```

# Css 36
```
/*
  Flexible Box
  For Parent
  - display: flex => To Start Flexible Box
  - flex-direction: row => Default Value
  - flex-wrap: nowrap => Default Value
  - flex-flow: [Flex-Direction] + [Flex-Wrap]
  - justify-content: flex-start => Default Value
  - align-items: stretch => Default Value
  - align-content: stretch => Default Value
  For Child
  - flex-grow: 0 => Default Value
  - flex-shrink: 1 => Default Value
  - order: 0 => Default Value
  - flex-basis: auto => Default Value
  - flex: [Flex Grow] [Flex Shrink] [Flex Basis] 0 1 Auto
  - align-self: auto => Default Value
*/

* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
.flex {
  background-color: #eee;
  width: 800px;
  height: 300px;
  padding: 20px;
  margin: 20px auto;
  display: flex;
  align-items: flex-start;
}
.flex div {
  background-color: #f00;
  color: white;
  width: 80px;
  text-align: center;
  padding: 20px;
  margin-right: 5px;
  flex-grow: 1;
}
```


# Html 37
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <img decoding="async" src="imgs/learn-programming.png" alt="" />
  </body>
</html>
```

# Css 37
```
/*
  Filters
*/

* {
  box-sizing: border-box;
}
img {
  transition: 0.3s;
  filter: grayscale(100%);
}
img:hover {
  filter: grayscale(0);
}
```

# Html 38
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <div>Gradients</div>
  </body>
</html>
```

# Css 38
```
/*
  Gradients
  linear-gradient(Direction || Angle, Color Stop 1, Color Stop 2, ....)
*/

div {
  width: 400px;
  height: 200px;
  background-color: #eee;
  margin: 20px auto;
  position: relative;
  padding: 10px;
}
div:before {
  content: "";
  position: absolute;
  top: -10px;
  left: 0;
  width: 100%;
  background-color: red;
  height: 10px;
  background-image: linear-gradient(
    to right,
    #2980b9 20%,
    #27ae60 20%,
    #27ae60 40%,
    #d35400 40%,
    #d35400 60%,
    #8e44ad 60%,
    #8e44ad 80%,
    #c0392b 80%
  );
}
```
# Html 39
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <input type="text" />
    <a href="https://google.com">Google</a>
    <p>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit.
      Laudantium, culpa dicta vitae quas temporibus nemo
      ducimus odio animi? Blanditiis voluptas suscipit id et ea
      eveniet doloribus libero labore commodi eligendi!
    </p>
  </body>
</html>
```

# Css 39
```
input {
  caret-color: red;
}
a {
  pointer-events: none;
}
```
# Html 40
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <link rel="stylesheet" href="css/master.css" />
  </head>
  <body>
    <div class="parent">
      <div>1</div>
      <div>2</div>
      <div>3</div>
      <div>4</div>
      <div>5</div>
      <div>6</div>
      <div>7</div>
      <div>8</div>
      <div>9</div>
    </div>
  </body>
</html>
```

# Css 40
```
/*
  Grid
  Parent
  - display: grid | inline-grid
  - grid-template-columns: [Number Of Columns In] => [Px, %, Auto, Repeat]
*/

* {
  box-sizing: border-box;
}
.parent {
  margin: 20px auto;
  width: 800px;
  height: 500px;
  background-color: #ddd;
  display: grid;
  grid-template-columns: repeat(2, auto) repeat(2, 1fr);
}
.parent div {
  background-color: red;
  color: white;
  padding: 20px;
  font-size: 30px;
  font-weight: bold;
  text-align: center;
}
```
# Html 41
```

```

# Css 41
```

```
