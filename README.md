## CSS
### Change color inline
```HTML
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="description" content="css tutorial">
        <title>CSS Tutorial</title>
    </head>
    <body>
        <p style="color: red;"> Click here </p>
    </body>
</html>
```
<br>

### Use CSS Selectors to style elements
```HTML
<!DOCTYPE html>

<!-- If you want every paragraph has same style -->
<style>
    p {color: red;}
    h2 {color: blue}
</style>

<html>
    <head>
        <meta charset="UTF-8">
        <meta name="description" content="css tutorial">
        <title>CSS Tutorial</title>
    </head>
    <body>
        <h2>Head style</h2>
        <p>paragraph1</p>
        <p>paragraph2</p>
    </body>
</html>
```
<br>

### Use a CSS Class to style an element
```HTML
<!DOCTYPE html>

<!-- Use dot to declare a class -->
<style>
    .blue-text {
        color: blue;
    }
    .red-text {
        color: red;
    }
</style>

<html>
    <head>
        <meta charset="UTF-8">
        <meta name="description" content="css tutorial">
        <title>CSS Tutorial</title>
    </head>
    <body>
        <h2 class="blue-text">Head style</h2>
        <p class="red-text">paragraph1</p>
        <p>paragraph2</p>
    </body>
</html>
```
<br>

### Style multiple elements with a CSS class
If CSS class exist, same class is able to adapted to several html elements.
<br>
<br>

### Change font size 
```HTML
<!DOCTYPE html>

<!-- If you want every paragraph has same style -->
<style>
    .blue-text {
        color: blue;
    }
    .red-text {
        color: red;
    }
    .change-font{
        font-size: 18px;
    }
</style>

<html>
    <head>
        <meta charset="UTF-8">
        <meta name="description" content="css tutorial">
        <title>CSS Tutorial</title>
    </head>
    <body>
        <h2 class="blue-text">Head style</h2>
        <p class="red-text">paragraph1</p>
        <p class="change-font">paragraph2</p>
    </body>
</html>
```
<br>

### Set the Font family of an Element
```HTML
<!DOCTYPE html>

<!-- If you want every paragraph has same style -->
<style>
    .blue-text {
        color: blue;
    }
    .red-text {
        color: red;
    }
    .change-font{
        font-size: 18px;
    }
    p{
        font-size: 18px;
        font-family: monospace;
    }
</style>

<html>
    <head>
        <meta charset="UTF-8">
        <meta name="description" content="css tutorial">
        <title>CSS Tutorial</title>
    </head>
    <body>
        <h2 class="blue-text">Head style</h2>
        <p class="red-text">paragraph1</p>
        <p class="change-font">paragraph2</p>
    </body>
</html>
```
<br>

### Import font from website
```HTML
<!DOCTYPE html>

<link href="https://fonts.googleapis.com/css2?family=Lobster&display=swap" rel="stylesheet">
<style>
    .blue-text {
        color: blue;
    }
    .red-text {
        color: red;
    }
    .change-font{
        font-size: 18px;
    }
    p{
        font-size: 18px;
        font-family: Helvetica, monospace;
    }
    h2{
        font-family: Lobster;
    }
</style>

<html>
    <head>
        <meta charset="UTF-8">
        <meta name="description" content="css tutorial">
        <title>CSS Tutorial</title>
    </head>
    <body>
        <h2 class="blue-text">Here is a Headline</h2>
        <p class="red-text">paragraph1</p>
        <p class="change-font">paragraph2</p>
    </body>
</html>
```
<br>


### Specify how fonts should degrade
List possible fonts in font-family.
```HTML
<!DOCTYPE html>

<!-- If you want every paragraph has same style -->
<style>
    .blue-text {
        color: blue;
    }
    .red-text {
        color: red;
    }
    .change-font{
        font-size: 18px;
    }
    p{
        font-size: 18px;
        font-family: Helvetica, monospace;
    }
</style>

<html>
    <head>
        <meta charset="UTF-8">
        <meta name="description" content="css tutorial">
        <title>CSS Tutorial</title>
    </head>
    <body>
        <h2 class="blue-text">Head style</h2>
        <p class="red-text">paragraph1</p>
        <p class="change-font">paragraph2</p>
    </body>
</html>
```
<br>

### Size your images
```HTML
<!DOCTYPE html>

<link href="https://fonts.googleapis.com/css2?family=Lobster&display=swap" rel="stylesheet">
<style>
    .blue-text {
        color: blue;
    }
    .red-text {
        color: red;
    }
    .change-font{
        font-size: 18px;
    }
    p{
        font-size: 18px;
        font-family: Helvetica, monospace;
    }
    h2{
        font-family: Lobster;
    }
    .smaller-image {
        width: 200px;
    }
</style>

<html>
    <head>
        <meta charset="UTF-8">
        <meta name="description" content="css tutorial">
        <title>CSS Tutorial</title>
    </head>
    <body>
        <h2 class="blue-text">Here is a Headline</h2>
        <p class="red-text">paragraph1</p>
        <p class="change-font">paragraph2</p>
        <img class="smaller-image" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTd_iTDAjLJmbhAFpHye9aaC_fTzEoULaPb9w&usqp=CAU">
    </body>
</html>
```
<br>

### Add Borders around elements
```HTML
<!DOCTYPE html>

<link href="https://fonts.googleapis.com/css2?family=Lobster&display=swap" rel="stylesheet">
<style>
    .thick-green-border {
        border-color: green;
        border-width: 10px;
        border-style: solid;
    }
    .blue-text {
        color: blue;
    }
    .red-text {
        color: red;
    }
    .change-font{
        font-size: 18px;
    }
    p{
        font-size: 18px;
        font-family: Helvetica, monospace;
    }
    h2{
        font-family: Lobster;
    }
    .smaller-image {
        width: 200px;
    }
</style>

<html>
    <head>
        <meta charset="UTF-8">
        <meta name="description" content="css tutorial">
        <title>CSS Tutorial</title>
    </head>
    <body>
        <h2 class="blue-text">Here is a Headline</h2>
        <p class="red-text">paragraph1</p>
        <p class="change-font">paragraph2</p>
        <img class="smaller-image thick-green-border" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTd_iTDAjLJmbhAFpHye9aaC_fTzEoULaPb9w&usqp=CAU">
    </body>
</html>
```
<br>

### Set border rounded
```HTML
<!DOCTYPE html>

<link href="https://fonts.googleapis.com/css2?family=Lobster&display=swap" rel="stylesheet">
<style>
    .thick-green-border {
        border-color: green;
        border-width: 10px;
        border-style: solid;
        border-radius: 10px;
    }
    .blue-text {
        color: blue;
    }
    .red-text {
        color: red;
    }
    .change-font{
        font-size: 18px;
    }
    p{
        font-size: 18px;
        font-family: Helvetica, monospace;
    }
    h2{
        font-family: Lobster;
    }
    .smaller-image {
        width: 200px;
    }
</style>

<html>
    <head>
        <meta charset="UTF-8">
        <meta name="description" content="css tutorial">
        <title>CSS Tutorial</title>
    </head>
    <body>
        <h2 class="blue-text">Here is a Headline</h2>
        <p class="red-text">paragraph1</p>
        <p class="change-font">paragraph2</p>
        <img class="smaller-image thick-green-border" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTd_iTDAjLJmbhAFpHye9aaC_fTzEoULaPb9w&usqp=CAU">
    </body>
</html>
```
<br>

### Makes a circle
```HTML
<!DOCTYPE html>

<link href="https://fonts.googleapis.com/css2?family=Lobster&display=swap" rel="stylesheet">
<style>
    .thick-green-border {
        border-color: green;
        border-width: 10px;
        border-style: solid;
        border-radius: 50%;
    }
    .blue-text {
        color: blue;
    }
    .red-text {
        color: red;
    }
    .change-font{
        font-size: 18px;
    }
    p{
        font-size: 18px;
        font-family: Helvetica, monospace;
    }
    h2{
        font-family: Lobster;
    }
    .smaller-image {
        width: 200px;
    }
</style>

<html>
    <head>
        <meta charset="UTF-8">
        <meta name="description" content="css tutorial">
        <title>CSS Tutorial</title>
    </head>
    <body>
        <h2 class="blue-text">Here is a Headline</h2>
        <p class="red-text">paragraph1</p>
        <p class="change-font">paragraph2</p>
        <img class="smaller-image thick-green-border" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTd_iTDAjLJmbhAFpHye9aaC_fTzEoULaPb9w&usqp=CAU">
    </body>
</html>
```
<br>

### Give a background color to a div elements
```HTML
<!DOCTYPE html>

<link href="https://fonts.googleapis.com/css2?family=Lobster&display=swap" rel="stylesheet">
<style>
    .silver-background {
        background-color: silver;
    }
    .thick-green-border {
        border-color: green;
        border-width: 10px;
        border-style: solid;
        border-radius: 50%;
    }
    .blue-text {
        color: blue;
    }
    .red-text {
        color: red;
    }
    .change-font{
        font-size: 18px;
    }
    p{
        font-size: 18px;
        font-family: Helvetica, monospace;
    }
    h2{
        font-family: Lobster;
    }
    .smaller-image {
        width: 200px;
    }
</style>

<html>
    <head>
        <meta charset="UTF-8">
        <meta name="description" content="css tutorial">
        <title>CSS Tutorial</title>
    </head>
    <body>
        <h2 class="blue-text">Here is a Headline</h2>
        <p class="red-text">paragraph1</p>
        <p class="change-font">paragraph2</p>
        <img class="smaller-image thick-green-border" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTd_iTDAjLJmbhAFpHye9aaC_fTzEoULaPb9w&usqp=CAU">
        <div class="silver-background">
            <p>This is a dog. They have</p>
            <ul>
                <li>Ears</li>
                <li>Nose</li>
                <li>Eyes</li>
                <li>Lovely Face</li>
            </ul>
        </div>
    </body>
</html>
```
<br>

### Set the id of an Elements
Now we can use the id to add css styles or we can reference it in JavaScript.
```HTML
<!DOCTYPE html>

<link href="https://fonts.googleapis.com/css2?family=Lobster&display=swap" rel="stylesheet">
<style>
    .silver-background {
        background-color: silver;
    }
    .thick-green-border {
        border-color: green;
        border-width: 10px;
        border-style: solid;
        border-radius: 50%;
    }
    .blue-text {
        color: blue;
    }
    .red-text {
        color: red;
    }
    .change-font{
        font-size: 18px;
    }
    p{
        font-size: 18px;
        font-family: Helvetica, monospace;
    }
    h2{
        font-family: Lobster;
    }
    .smaller-image {
        width: 200px;
    }
</style>

<html>
    <head>
        <meta charset="UTF-8">
        <meta name="description" content="css tutorial">
        <title>CSS Tutorial</title>
    </head>
    <body>
        <h2 class="blue-text">Here is a Headline</h2>
        <p class="red-text">paragraph1</p>
        <p class="change-font">paragraph2</p>
        <img id="dog-photo" class="smaller-image thick-green-border" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTd_iTDAjLJmbhAFpHye9aaC_fTzEoULaPb9w&usqp=CAU">
        <div class="silver-background">
            <p>This is a dog. They have</p>
            <ul>
                <li>Ears</li>
                <li>Nose</li>
                <li>Eyes</li>
                <li>Lovely Face</li>
            </ul>
        </div>
    </body>
</html>
```
<br>

### Use an id Attribute to style an elements
- We can use it by # mark
- Id is only able to be allocated per each element
- Priority: id > class
```HTML
<!DOCTYPE html>

<link href="https://fonts.googleapis.com/css2?family=Lobster&display=swap" rel="stylesheet">
<style>
    #heading {
        color: green;
    }
    .silver-background {
        background-color: silver;
    }
    .thick-green-border {
        border-color: green;
        border-width: 10px;
        border-style: solid;
        border-radius: 50%;
    }
    .blue-text {
        color: blue;
    }
    .red-text {
        color: red;
    }
    .change-font{
        font-size: 18px;
    }
    p{
        font-size: 18px;
        font-family: Helvetica, monospace;
    }
    h2{
        font-family: Lobster;
    }
    .smaller-image {
        width: 200px;
    }
</style>

<html>
    <head>
        <meta charset="UTF-8">
        <meta name="description" content="css tutorial">
        <title>CSS Tutorial</title>
    </head>
    <body>
        <h2 id="heading" class="blue-text">Here is a Headline</h2>
        <p class="red-text">paragraph1</p>
        <p class="change-font">paragraph2</p>
        <img id="dog-photo" class="smaller-image thick-green-border" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTd_iTDAjLJmbhAFpHye9aaC_fTzEoULaPb9w&usqp=CAU">
        <div class="silver-background">
            <p>This is a dog. They have</p>
            <ul>
                <li>Ears</li>
                <li>Nose</li>
                <li>Eyes</li>
                <li>Lovely Face</li>
            </ul>
        </div>
    </body>
</html>
```
<br>

### Adjust the padding and margin of an element
```HTML
<!DOCTYPE html>

<link href="https://fonts.googleapis.com/css2?family=Lobster&display=swap" rel="stylesheet">
<style>
    #heading {
        background-color: gray;
    }
    .silver-background {
        background-color: silver;
    }
    .thick-green-border {
        border-color: green;
        border-width: 10px;
        border-style: solid;
        border-radius: 50%;
    }
    .blue-text {
        color: blue;
        padding: 10px;
    }
    .red-text {
        color: red;
        margin: 20px;
    }
    .change-font{
        font-size: 18px;
    }
    p{
        font-size: 18px;
        font-family: Helvetica, monospace;
    }
    h2{
        font-family: Lobster;
    }
    .smaller-image {
        width: 200px;
    }
</style>

<html>
    <head>
        <meta charset="UTF-8">
        <meta name="description" content="css tutorial">
        <title>CSS Tutorial</title>
    </head>
    <body>
        <h2 id="heading" class="blue-text">Here is a Headline</h2>
        <p class="red-text">paragraph1</p>
        <p class="change-font">paragraph2</p>
        <img id="dog-photo" class="smaller-image thick-green-border" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTd_iTDAjLJmbhAFpHye9aaC_fTzEoULaPb9w&usqp=CAU">
        <div class="silver-background">
            <p>This is a dog. They have</p>
            <ul>
                <li>Ears</li>
                <li>Nose</li>
                <li>Eyes</li>
                <li>Lovely Face</li>
            </ul>
        </div>
    </body>
</html>
```
> Padding and margin would be used in each direction by top, bottom, right, left or clockwise notaion
<br>

### Use attribute selectors to style elements
```HTML
<!DOCTYPE html>

<link href="https://fonts.googleapis.com/css2?family=Lobster&display=swap" rel="stylesheet">
<style>
    [type='radio'] {
        margin: 10px 15px 20px 15px;
    }

    #heading {
        background-color: gray;
    }
    .silver-background {
        background-color: silver;
    }
    .thick-green-border {
        border-color: green;
        border-width: 10px;
        border-style: solid;
        border-radius: 50%;
    }
    .blue-text {
        color: blue;
        padding: 10px;
    }
    .red-text {
        color: red;
        margin: 20px;
    }
    .change-font{
        font-size: 18px;
    }
    p{
        font-size: 18px;
        font-family: Helvetica, monospace;
    }
    h2{
        font-family: Lobster;
    }
    .smaller-image {
        width: 200px;
    }
</style>

<html>
    <head>
        <meta charset="UTF-8">
        <meta name="description" content="css tutorial">
        <title>CSS Tutorial</title>
    </head>
    <body>
        <h2 id="heading" class="blue-text">Here is a Headline</h2>
        <p class="red-text">paragraph1</p>
        <p class="change-font">paragraph2</p>
        <img id="dog-photo" class="smaller-image thick-green-border" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTd_iTDAjLJmbhAFpHye9aaC_fTzEoULaPb9w&usqp=CAU">
        <div class="silver-background">
            <p>This is a dog. They have</p>
            <ul>
                <li>Ears</li>
                <li>Nose</li>
                <li>Eyes</li>
                <li>Lovely Face</li>
            </ul>
        </div>

        <span>
            <input type="radio" name="wch radio">
            <label>One</label>
        </span>
          
        <span>
            <input type="radio" name="wch radio">
            <label>Two</label>
        </span>
          
        <span>
            <input type="radio" name="wch radio">
            <label>Three</label>
        </span>
    </body>
</html>
```
<br>

### Understnad absolute versus relative units
Use em or m value. These notation would be more handled in responsive web development.
```HTML
<!DOCTYPE html>

<link href="https://fonts.googleapis.com/css2?family=Lobster&display=swap" rel="stylesheet">
<style>
    [type='radio'] {
        margin: 10px 15px 20px 15px;
    }

    #heading {
        background-color: gray;
    }
    .silver-background {
        background-color: silver;
    }
    .thick-green-border {
        border-color: green;
        border-width: 10px;
        border-style: solid;
        border-radius: 50%;
    }
    .blue-text {
        color: blue;
        padding: 10px;
    }
    .red-text {
        color: red;
        margin: 1.5em;
    }
    .change-font{
        font-size: 18px;
    }
    p{
        font-size: 18px;
        font-family: Helvetica, monospace;
    }
    h2{
        font-family: Lobster;
    }
    .smaller-image {
        width: 200px;
    }
</style>

<html>
    <head>
        <meta charset="UTF-8">
        <meta name="description" content="css tutorial">
        <title>CSS Tutorial</title>
    </head>
    <body>
        <h2 id="heading" class="blue-text">Here is a Headline</h2>
        <p class="red-text">paragraph1</p>
        <p class="change-font">paragraph2</p>
        <img id="dog-photo" class="smaller-image thick-green-border" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTd_iTDAjLJmbhAFpHye9aaC_fTzEoULaPb9w&usqp=CAU">
        <div class="silver-background">
            <p>This is a dog. They have</p>
            <ul>
                <li>Ears</li>
                <li>Nose</li>
                <li>Eyes</li>
                <li>Lovely Face</li>
            </ul>
        </div>

        <span>
            <input type="radio" name="wch radio">
            <label>One</label>
        </span>
          
        <span>
            <input type="radio" name="wch radio">
            <label>Two</label>
        </span>
          
        <span>
            <input type="radio" name="wch radio">
            <label>Three</label>
        </span>
    </body>
</html>
```
<br>

### Style the HTML Body elements
```HTML
<style>
    body {
        background-color: black;
    }
</style>
```

### Inherit styles from the body elements
Cascading means anything that you apply to an upper element goes down to any lower elements or any elements that are inside other elements. So anything that you apply to the body element will cascade or get be inherited to all the other elements on the page.
```HTML
<style>
    body {
        background-color: black;
        color: green;
        font-family: monospace;
    }
</style>

<h1>Hello World</h1>
```

### Prioritize one style over another
Pink text is more specific, so it's going to be applied.
```HTML
<style>
    body {
        background-color: black;
        color: green;
        font-family: monospace;
    }

    .pink-text {
        color: pink;
    }
</style>

<h1 class="pink-text">Hello World</h1>
```

### Override styles in subsequent CSS
It just depends on order in `<style>`
```HTML
<style>
    body {
        background-color: black;
        color: green;
        font-family: monospace;
    }

    .pink-text {
        color: pink;
    }

    .blue-text {
        color: blue;
    }
</style>

<h1 class="pink-text blue-text">Hello World</h1>
```
<br>

### Override class declarations by styling id attributes
Similarily, id is more specific.
```HTML
<style>
    body {
        background-color: black;
        color: green;
        font-family: monospace;
    }

    #orange-text {
        color: orange;
    }
    .pink-text {
        color: pink;
    }

    .blue-text {
        color: blue;
    }
</style>

<h1 class="pink-text blue-text" id="orange-text">Hello World</h1>
```
> `conclusion: inline > id > lower order in style sheet`
<br>

### Override class declaration by using important
```HTML
<style>
    body {
        background-color: black;
        color: green;
        font-family: monospace;
    }

    #orange-text {
        color: orange;
    }
    .pink-text {
        color: pink !important;
    }

    .blue-text {
        color: blue;
    }
</style>

<h1 class="pink-text blue-text" id="orange-text">Hello World</h1>
```
<br>

### Colors by Hex and RGB
```HTML
<style>
    body {
        background-color: rgb(0, 0, 0);
        color: #01523F;
    }
</style>
```

### Use CSS variable to change several elements at once
Penguin example.
```HTML
<style>
    .penguin {
      --penguin-skin: black;
      --penguin-belly: white;
      --penguin-beak: green;
      
      position: relative;
      margin: auto;
      display: block;
      margin-top: 5%;
      width: 300px;
      height: 300px;
    }
  
    .penguin-top {
      top: 10%;
      left: 25%;
  
      /* Change code below this line */
      background: black;
      /* Change code above this line */
  
      width: 50%;
      height: 45%;
      border-radius: 70% 70% 60% 60%;
    }
  
    .penguin-bottom {
      top: 40%;
      left: 23.5%;
  
      /* Change code below this line */
      background: black;
      /* Change code above this line */
  
      width: 53%;
      height: 45%;
      border-radius: 70% 70% 100% 100%;
    }
  
    .right-hand {
      top: 0%;
      left: -5%;
  
      /* Change code below this line */
      background: black;
      /* Change code above this line */
  
      width: 30%;
      height: 60%;
      border-radius: 30% 30% 120% 30%;
      transform: rotate(45deg);
      z-index: -1;
    }
  
    .left-hand {
      top: 0%;
      left: 75%;
  
      /* Change code below this line */
      background: black;
      /* Change code above this line */
  
      width: 30%;
      height: 60%;
      border-radius: 30% 30% 30% 120%;
      transform: rotate(-45deg);
      z-index: -1;
    }
  
    .right-cheek {
      top: 15%;
      left: 35%;
      background: white;
      width: 60%;
      height: 70%;
      border-radius: 70% 70% 60% 60%;
    }
  
    .left-cheek {
      top: 15%;
      left: 5%;
      background: white;
      width: 60%;
      height: 70%;
      border-radius: 70% 70% 60% 60%;
    }
  
    .belly {
      top: 60%;
      left: 2.5%;
      background: white;
      width: 95%;
      height: 100%;
      border-radius: 120% 120% 100% 100%;
    }
  
    .right-feet {
      top: 85%;
      left: 60%;
      background: orange;
      width: 15%;
      height: 30%;
      border-radius: 50% 50% 50% 50%;
      transform: rotate(-80deg);
      z-index: -2222;
    }
  
    .left-feet {
      top: 85%;
      left: 25%;
      background: orange;
      width: 15%;
      height: 30%;
      border-radius: 50% 50% 50% 50%;
      transform: rotate(80deg);
      z-index: -2222;
    }
  
    .right-eye {
      top: 45%;
      left: 60%;
      background: black;
      width: 15%;
      height: 17%;
      border-radius: 50%;
    }
  
    .left-eye {
      top: 45%;
      left: 25%;
      background: black;
      width: 15%;
      height: 17%;
      border-radius: 50%;
    }
  
    .sparkle {
      top: 25%;
      left: 15%;
      background: white;
      width: 35%;
      height: 35%;
      border-radius: 50%;
    }
  
    .blush-right {
      top: 65%;
      left: 15%;
      background: pink;
      width: 15%;
      height: 10%;
      border-radius: 50%;
    }
  
    .blush-left {
      top: 65%;
      left: 70%;
      background: pink;
      width: 15%;
      height: 10%;
      border-radius: 50%;
    }
  
    .beak-top {
      top: 60%;
      left: 40%;
      background: orange;
      width: 20%;
      height: 10%;
      border-radius: 50%;
    }
  
    .beak-bottom {
      top: 65%;
      left: 42%;
      background: orange;
      width: 16%;
      height: 10%;
      border-radius: 50%;
    }
  
    body {
      background:#c6faf1;
    }
  
    .penguin * {
      position: absolute;
    }
  </style>
  <div class="penguin">
    <div class="penguin-bottom">
      <div class="right-hand"></div>
      <div class="left-hand"></div>
      <div class="right-feet"></div>
      <div class="left-feet"></div>
    </div>
    <div class="penguin-top">
      <div class="right-cheek"></div>
      <div class="left-cheek"></div>
      <div class="belly"></div>
      <div class="right-eye">
        <div class="sparkle"></div>
      </div>
      <div class="left-eye">
        <div class="sparkle"></div>
      </div>
      <div class="blush-right"></div>
      <div class="blush-left"></div>
      <div class="beak-top"></div>
      <div class="beak-bottom"></div>
    </div>
  </div>
```
<br>

### Create a custom CSS variable
Double dash `--Variable_name` is going to be used all around in subsequent in css.
```HTML
<style>
    .penguin {
      --penguin-skin: gray;
      --penguin-belly: white;
      --penguin-beak: green;

      position: relative;
      margin: auto;
      display: block;
      margin-top: 5%;
      width: 300px;
      height: 300px;
    }
  
    .penguin-top {
      top: 10%;
      left: 25%;
  
      /* Change code below this line */
      background:var(--penguin-skin);
      /* Change code above this line */
  
      width: 50%;
      height: 45%;
      border-radius: 70% 70% 60% 60%;
    }
  
    .penguin-bottom {
      top: 40%;
      left: 23.5%;
  
      /* Change code below this line */
      background: black;
      /* Change code above this line */
  
      width: 53%;
      height: 45%;
      border-radius: 70% 70% 100% 100%;
    }
  
    .right-hand {
      top: 0%;
      left: -5%;
  
      /* Change code below this line */
      background: black;
      /* Change code above this line */
  
      width: 30%;
      height: 60%;
      border-radius: 30% 30% 120% 30%;
      transform: rotate(45deg);
      z-index: -1;
    }
  
    .left-hand {
      top: 0%;
      left: 75%;
  
      /* Change code below this line */
      background: black;
      /* Change code above this line */
  
      width: 30%;
      height: 60%;
      border-radius: 30% 30% 30% 120%;
      transform: rotate(-45deg);
      z-index: -1;
    }
  
    .right-cheek {
      top: 15%;
      left: 35%;
      background: white;
      width: 60%;
      height: 70%;
      border-radius: 70% 70% 60% 60%;
    }
  
    .left-cheek {
      top: 15%;
      left: 5%;
      background: white;
      width: 60%;
      height: 70%;
      border-radius: 70% 70% 60% 60%;
    }
  
    .belly {
      top: 60%;
      left: 2.5%;
      background: white;
      width: 95%;
      height: 100%;
      border-radius: 120% 120% 100% 100%;
    }
  
    .right-feet {
      top: 85%;
      left: 60%;
      background: orange;
      width: 15%;
      height: 30%;
      border-radius: 50% 50% 50% 50%;
      transform: rotate(-80deg);
      z-index: -2222;
    }
  
    .left-feet {
      top: 85%;
      left: 25%;
      background: orange;
      width: 15%;
      height: 30%;
      border-radius: 50% 50% 50% 50%;
      transform: rotate(80deg);
      z-index: -2222;
    }
  
    .right-eye {
      top: 45%;
      left: 60%;
      background: black;
      width: 15%;
      height: 17%;
      border-radius: 50%;
    }
  
    .left-eye {
      top: 45%;
      left: 25%;
      background: black;
      width: 15%;
      height: 17%;
      border-radius: 50%;
    }
  
    .sparkle {
      top: 25%;
      left: 15%;
      background: white;
      width: 35%;
      height: 35%;
      border-radius: 50%;
    }
  
    .blush-right {
      top: 65%;
      left: 15%;
      background: pink;
      width: 15%;
      height: 10%;
      border-radius: 50%;
    }
  
    .blush-left {
      top: 65%;
      left: 70%;
      background: pink;
      width: 15%;
      height: 10%;
      border-radius: 50%;
    }
  
    .beak-top {
      top: 60%;
      left: 40%;
      background: orange;
      width: 20%;
      height: 10%;
      border-radius: 50%;
    }
  
    .beak-bottom {
      top: 65%;
      left: 42%;
      background: orange;
      width: 16%;
      height: 10%;
      border-radius: 50%;
    }
  
    body {
      background:#c6faf1;
    }
  
    .penguin * {
      position: absolute;
    }
  </style>
  <div class="penguin">
    <div class="penguin-bottom">
      <div class="right-hand"></div>
      <div class="left-hand"></div>
      <div class="right-feet"></div>
      <div class="left-feet"></div>
    </div>
    <div class="penguin-top">
      <div class="right-cheek"></div>
      <div class="left-cheek"></div>
      <div class="belly"></div>
      <div class="right-eye">
        <div class="sparkle"></div>
      </div>
      <div class="left-eye">
        <div class="sparkle"></div>
      </div>
      <div class="blush-right"></div>
      <div class="blush-left"></div>
      <div class="beak-top"></div>
      <div class="beak-bottom"></div>
    </div>
  </div>
```
<br>

### Media query
It apply different variable value depending on browser sizes.
```HTML
<style>
    :root {
        --penguin-size: 300px;
        --penguin-skin: gray;
        --penguin-belly: white;
        --penguin-beak: yellow;
    }

    @media (max-width: 150px) {
        :root {
            --penguin-size: 200px;
            --penguin-skin: black;
        }
    }

    .penguin {
      position: relative;
      margin: auto;
      display: block;
      margin-top: 5%;
      width: 300px;
      height: 300px;
    }
  
    .penguin-top {
      top: 10%;
      left: 25%;
  
      /* Change code below this line */
      background: var(--penguin-skin);
      /* Change code above this line */
  
      width: 50%;
      height: 45%;
      border-radius: 70% 70% 60% 60%;
    }
  
    .penguin-bottom {
      top: 40%;
      left: 23.5%;
  
      /* Change code below this line */
      background: var(--penguin-skin);
      /* Change code above this line */
  
      width: 53%;
      height: 45%;
      border-radius: 70% 70% 100% 100%;
    }
  
    .right-hand {
      top: 0%;
      left: -5%;
  
      /* Change code below this line */
      background: var(--penguin-skin);
      /* Change code above this line */
  
      width: 30%;
      height: 60%;
      border-radius: 30% 30% 120% 30%;
      transform: rotate(45deg);
      z-index: -1;
    }
  
    .left-hand {
      top: 0%;
      left: 75%;
  
      /* Change code below this line */
      background: var(--penguin-skin);
      /* Change code above this line */
  
      width: 30%;
      height: 60%;
      border-radius: 30% 30% 30% 120%;
      transform: rotate(-45deg);
      z-index: -1;
    }
  
    .right-cheek {
      top: 15%;
      left: 35%;
      background: white;
      width: 60%;
      height: 70%;
      border-radius: 70% 70% 60% 60%;
    }
  
    .left-cheek {
      top: 15%;
      left: 5%;
      background: white;
      width: 60%;
      height: 70%;
      border-radius: 70% 70% 60% 60%;
    }
  
    .belly {
      top: 60%;
      left: 2.5%;
      background: var(--penguin-belly);
      width: 95%;
      height: 100%;
      border-radius: 120% 120% 100% 100%;
    }
  
    .right-feet {
      top: 85%;
      left: 60%;
      background: orange;
      width: 15%;
      height: 30%;
      border-radius: 50% 50% 50% 50%;
      transform: rotate(-80deg);
      z-index: -2222;
    }
  
    .left-feet {
      top: 85%;
      left: 25%;
      background: orange;
      width: 15%;
      height: 30%;
      border-radius: 50% 50% 50% 50%;
      transform: rotate(80deg);
      z-index: -2222;
    }
  
    .right-eye {
      top: 45%;
      left: 60%;
      background: black;
      width: 15%;
      height: 17%;
      border-radius: 50%;
    }
  
    .left-eye {
      top: 45%;
      left: 25%;
      background: black;
      width: 15%;
      height: 17%;
      border-radius: 50%;
    }
  
    .sparkle {
      top: 25%;
      left: 15%;
      background: white;
      width: 35%;
      height: 35%;
      border-radius: 50%;
    }
  
    .blush-right {
      top: 65%;
      left: 15%;
      background: pink;
      width: 15%;
      height: 10%;
      border-radius: 50%;
    }
  
    .blush-left {
      top: 65%;
      left: 70%;
      background: pink;
      width: 15%;
      height: 10%;
      border-radius: 50%;
    }
  
    .beak-top {
      top: 60%;
      left: 40%;
      background: orange;
      width: 20%;
      height: 10%;
      border-radius: 50%;
    }
  
    .beak-bottom {
      top: 65%;
      left: 42%;
      background: orange;
      width: 16%;
      height: 10%;
      border-radius: 50%;
    }
  
    body {
      background:#c6faf1;
    }
  
    .penguin * {
      position: absolute;
    }
  </style>
  <div class="penguin">
    <div class="penguin-bottom">
      <div class="right-hand"></div>
      <div class="left-hand"></div>
      <div class="right-feet"></div>
      <div class="left-feet"></div>
    </div>
    <div class="penguin-top">
      <div class="right-cheek"></div>
      <div class="left-cheek"></div>
      <div class="belly"></div>
      <div class="right-eye">
        <div class="sparkle"></div>
      </div>
      <div class="left-eye">
        <div class="sparkle"></div>
      </div>
      <div class="blush-right"></div>
      <div class="blush-left"></div>
      <div class="beak-top"></div>
      <div class="beak-bottom"></div>
    </div>
  </div>
```
<br>

### Create CSS Grid (columns and rows with grid-template)
We can turn any HTML elements into a grid container by setting its display property to grid.
```HTML
<style>
    .d1{background:LightSkyBlue;}
    .d2{background:LightSalmon;}
    .d3{background:PaleTurquoise;}
    .d4{background:LightPink;}
    .d5{background:PaleGreen;}
  
    .container {
      font-size: 40px;
      width: 100%;
      background: LightGray;
      /* Only change code below this line */
      display: grid;
      grid-template-columns: 100px 100px 100px;
      grid-template-rows: 50px 50px;
      /* Only change code above this line */
    }
  </style>
  
  <div class="container">
    <div class="d1">1</div>
    <div class="d2">2</div>
    <div class="d3">3</div>
    <div class="d4">4</div>
    <div class="d5">5</div>
  </div>
```
<br>

### Change Grid size of columns and rows
Using fr units.
```HTML
<style>
    .d1{background:LightSkyBlue;}
    .d2{background:LightSalmon;}
    .d3{background:PaleTurquoise;}
    .d4{background:LightPink;}
    .d5{background:PaleGreen;}
  
    .container {
      font-size: 40px;
      width: 100%;
      background: LightGray;
      /* Only change code below this line */
      display: grid;
      grid-template-columns: 1fr 100px 2fr;

      grid-template-rows: 50px 50px;
      /* Only change code above this line */
    }
  </style>
  
  <div class="container">
    <div class="d1">1</div>
    <div class="d2">2</div>
    <div class="d3">3</div>
    <div class="d4">4</div>
    <div class="d5">5</div>
  </div>
```
<br>

### Using gap
```HTML
<style>
    .d1{background:LightSkyBlue;}
    .d2{background:LightSalmon;}
    .d3{background:PaleTurquoise;}
    .d4{background:LightPink;}
    .d5{background:PaleGreen;}
  
    .container {
      font-size: 40px;
      width: 100%;
      background: LightGray;
      /* Only change code below this line */
      display: grid;
      grid-template-columns: 1fr 100px 2fr;
      grid-column-gap: 10px;

      grid-template-rows: 50px 50px;
      grid-row-gap: 10px;
      /* Only change code above this line */
    }
  </style>
  
  <div class="container">
    <div class="d1">1</div>
    <div class="d2">2</div>
    <div class="d3">3</div>
    <div class="d4">4</div>
    <div class="d5">5</div>
  </div>
```
<br>

### Use grid to select columns and rows
```HTML
<style>
    .item1{background:LightSkyBlue;}
    .item2{background:LightSalmon;}
    .item3{background:PaleTurquoise;}
    .item4{background:LightPink;}
  
    .item5 {
      background: PaleGreen;
      /* Only change code below this line */
        grid-column: 1/4;
        grid-row: 3/4;
  
      /* Only change code above this line */
    }
  
    .container {
      font-size: 40px;
      min-height: 300px;
      width: 100%;
      background: LightGray;
      display: grid;
      grid-template-columns: 1fr 1fr 1fr;
      grid-template-rows: 1fr 1fr 1fr;
      grid-gap: 10px;
    }
  </style>
  
  <div class="container">
    <div class="item1">1</div>
    <div class="item2">2</div>
    <div class="item3">3</div>
    <div class="item4">4</div>
    <div class="item5">5</div>
  </div>
```

### Align an item horizontally using justify-self
Each cells are considered different and independent elements.
```HTML
<style>
    .item1{background: LightSkyBlue;}
  
    .item2 {
      background: LightSalmon;
      /* Only change code below this line */
      justify-self: center;
      
      /* Only change code above this line */
    }
  
    .item3{background:PaleTurquoise;}
    .item4{background:LightPink;}
    .item5{background:PaleGreen;}
  
    .container {
      font-size: 40px;
      min-height: 300px;
      width: 100%;
      background: LightGray;
      display: grid;
      grid-template-columns: 1fr 1fr 1fr;
      grid-template-rows: 1fr 1fr 1fr;
      grid-gap: 10px;
    }
  </style>
  
  <div class="container">
    <div class="item1">1</div>
    <div class="item2">2</div>
    <div class="item3">3</div>
    <div class="item4">4</div>
    <div class="item5">5</div>
  </div>
```
<br>

### Align vertically
```HTML
<style>
    .item1{background:LightSkyBlue;}
    .item2{background:LightSalmon;}
  
    .item3 {
      background: PaleTurquoise;
      /* Only change code below this line */
      align-self: end;
      
      /* Only change code above this line */
    }
  
    .item4{background:LightPink;}
    .item5{background:PaleGreen;}
  
    .container {
      font-size: 40px;
      min-height: 300px;
      width: 100%;
      background: LightGray;
      display: grid;
      grid-template-columns: 1fr 1fr 1fr;
      grid-template-rows: 1fr 1fr 1fr;
      grid-gap: 10px;
    }
  </style>
  
  <div class="container">
    <div class="item1">1</div>
    <div class="item2">2</div>
    <div class="item3">3</div>
    <div class="item4">4</div>
    <div class="item5">5</div>
  </div>
```
<br>

### Divide the grid into an Area template
```HTML
<style>
  .item1{background:LightSkyBlue;}
  .item2{background:LightSalmon;}
  .item3{background:PaleTurquoise;}
  .item4{background:LightPink;}
  .item5{background:PaleGreen;}

  .container {
    font-size: 40px;
    min-height: 300px;
    width: 100%;
    background: LightGray;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr;
    grid-gap: 10px;
    grid-template-areas:
    /* Only change code below this line */
      "header header header"
      "advert content content"
      "footer footer footer";
    /* Only change code above this line */
  }
</style>

<div class="container">
  <div class="item1">1</div>
  <div class="item2">2</div>
  <div class="item3">3</div>
  <div class="item4">4</div>
  <div class="item5">5</div>
</div>
```
<br>

### Place items in grid areas using the grid-area property
Items are able to choose where these component would be located itself as well as grids are.
```HTML
<style>
  .item1{background:LightSkyBlue;}
  .item2{background:LightSalmon;}
  .item3{background:PaleTurquoise;}
  .item4{background:LightPink;}
  .item5{
    background:PaleGreen;
    grid-area: header; /* header, advert, footer */
  }

  .container {
    font-size: 40px;
    min-height: 300px;
    width: 100%;
    background: LightGray;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr;
    grid-gap: 10px;
    grid-template-areas:
    /* Only change code below this line */
      "header header header"
      "advert content content"
      "footer footer footer";
    /* Only change code above this line */
  }
</style>

<div class="container">
  <div class="item1">1</div>
  <div class="item2">2</div>
  <div class="item3">3</div>
  <div class="item4">4</div>
  <div class="item5">5</div>
</div>
```
<br>

### Use gird-area without creating an areas template
```HTML
<style>
  .item1{background:LightSkyBlue;}
  .item2{background:LightSalmon;}
  .item3{background:PaleTurquoise;}
  .item4{background:LightPink;}
  .item5{
    background:PaleGreen;
    grid-area: 3/1/4/4; /* Left up point, Right down point*/
  }

  .container {
    font-size: 40px;
    min-height: 300px;
    width: 100%;
    background: LightGray;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr;
    grid-gap: 10px;
    grid-template-areas:
    /* Only change code below this line */
      "header header header"
      "advert content content"
      "footer footer footer";
    /* Only change code above this line */
  }
</style>

<div class="container">
  <div class="item1">1</div>
  <div class="item2">2</div>
  <div class="item3">3</div>
  <div class="item4">4</div>
  <div class="item5">5</div>
</div>
```
<br>

### Reduce repetition using the repeat function
```HTML
<style>
  .item1{background:LightSkyBlue;}
  .item2{background:LightSalmon;}
  .item3{background:PaleTurquoise;}
  .item4{background:LightPink;}
  .item5{
    background:PaleGreen;
    grid-area: 2/1/5/4;
  }

  .container {
    font-size: 40px;
    min-height: 300px;
    width: 100%;
    background: LightGray;
    display: grid;
    grid-template-columns: repeat(3, 1fr) 1fr;
    grid-template-rows: 1fr 1fr 1fr;
    grid-gap: 10px;
    grid-template-areas:
      "header header header"
      "advert content content"
      "footer footer footer";
  }
</style>

<div class="container">
  <div class="item1">1</div>
  <div class="item2">2</div>
  <div class="item3">3</div>
  <div class="item4">4</div>
  <div class="item5">5</div>
</div>
```

### Limit item size using the minmax function
```HTML
<style>
  .item1{background:LightSkyBlue;}
  .item2{background:LightSalmon;}
  .item3{background:PaleTurquoise;}
  .item4{background:LightPink;}
  .item5{
    background:PaleGreen;
    grid-area: 2/1/5/4;
  }

  .container {
    font-size: 40px;
    min-height: 300px;
    width: 100%;
    background: LightGray;
    display: grid;
    grid-template-columns: repeat(3, minmax(10px, 1fr)) 1fr;
    grid-template-rows: 1fr 1fr 1fr;
    grid-gap: 10px;
    grid-template-areas:
      "header header header"
      "advert content content"
      "footer footer footer";
  }
</style>

<div class="container">
  <div class="item1">1</div>
  <div class="item2">2</div>
  <div class="item3">3</div>
  <div class="item4">4</div>
  <div class="item5">5</div>
</div>
```
<br>

### Create Flexible layouts using auto-fill
```HTML
<style>
  .item1{background:LightSkyBlue;}
  .item2{background:LightSalmon;}
  .item3{background:PaleTurquoise;}
  .item4{background:LightPink;}
  .item5{background:PaleGreen;}

  .container {
    font-size: 40px;
    min-height: 100px;
    width: 100%;
    background: LightGray;
    display: grid;
    /* Only change code below this line */

    grid-template-columns: repeat(auto-fill, minmax(60px, 1fr));

    /* Only change code above this line */
    grid-template-rows: 1fr 1fr 1fr;
    grid-gap: 10px;
  }

  .container2 {
    font-size: 40px;
    min-height: 100px;
    width: 100%;
    background: Silver;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(60px, 1fr));
    grid-template-rows: 1fr 1fr 1fr;
    grid-gap: 10px;
  }
</style>
<div class="container">
  <div class="item1">1</div>
  <div class="item2">2</div>
  <div class="item3">3</div>
  <div class="item4">4</div>
  <div class="item5">5</div>
</div>
<div class="container2">
  <div class="item1">1</div>
  <div class="item2">2</div>
  <div class="item3">3</div>
  <div class="item4">4</div>
  <div class="item5">5</div>
</div>
```
<br>

### Create Flexible Layouts using auto-fit
```HTML
<style>
  .item1{background:LightSkyBlue;}
  .item2{background:LightSalmon;}
  .item3{background:PaleTurquoise;}
  .item4{background:LightPink;}
  .item5{background:PaleGreen;}

  .container {
    font-size: 40px;
    min-height: 100px;
    width: 100%;
    background: LightGray;
    display: grid;
    /* Only change code below this line */

    grid-template-columns: repeat(auto-fill, minmax(60px, 1fr));

    /* Only change code above this line */
    grid-template-rows: 1fr 1fr 1fr;
    grid-gap: 10px;
  }

  .container2 {
    font-size: 40px;
    min-height: 100px;
    width: 100%;
    background: Silver;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(60px, 1fr));
    grid-template-rows: 1fr 1fr 1fr;
    grid-gap: 10px;
  }
</style>
<div class="container">
  <div class="item1">1</div>
  <div class="item2">2</div>
  <div class="item3">3</div>
  <div class="item4">4</div>
  <div class="item5">5</div>
</div>
<div class="container2">
  <div class="item1">1</div>
  <div class="item2">2</div>
  <div class="item3">3</div>
  <div class="item4">4</div>
  <div class="item5">5</div>
</div>
```
<br>

### Use media queries to create responsive layouts
Use ctrl + scoll to check out.
```HTML
<!DOCTYPE html>

<style>
  .item1 {
    background: LightSkyBlue;
    grid-area: header;
  }

  .item2 {
    background: LightSalmon;
    grid-area: advert;
  }

  .item3 {
    background: PaleTurquoise;
    grid-area: content;
  }

  .item4 {
    background: lightpink;
    grid-area: footer;
  }

  .container {
    font-size: 1.5em;
    min-height: 300px;
    width: 100%;
    background: LightGray;
    display: grid;
    grid-template-columns: 1fr;
    grid-template-rows: 50px auto 1fr auto;
    grid-gap: 10px;
    grid-template-areas:
      "header"
      "advert"
      "content"
      "footer";
  }

  @media (min-width: 300px){
    .container{
      grid-template-columns: auto 1fr;
      grid-template-rows: auto 1fr auto;
      grid-template-areas:
        "advert header"
        "advert content"
        "advert footer";
    }
  }

  @media (min-width: 400px){
    .container{
      grid-template-areas:
      /* Only change code below this line */
        "advert header"
        "advert content"
        "advert footer";
      /* Only change code above this line */
    }
  }
</style>

<html>
  <head>
    <meta name="viewport" content="width=device-width,initial-scale=1">
  </head>
  <body>    
    <div class="container">
      <div class="item1">header</div>
      <div class="item2">advert</div>
      <div class="item3">content</div>
      <div class="item4">footer</div>
    </div>
  </body>
</html>
```
<br>

### Create Grids within grids
```HTML
<style>
  .container {
    font-size: 1.5em;
    min-height: 300px;
    width: 100%;
    background: LightGray;
    display: grid;
    grid-template-columns: auto 1fr;
    grid-template-rows: auto 1fr auto;
    grid-gap: 10px;
    grid-template-areas:
      "advert header"
      "advert content"
      "advert footer";
  }
  .item1 {
    background: LightSkyBlue;
    grid-area: header;
  }

  .item2 {
    background: LightSalmon;
    grid-area: advert;
  }

  .item3 {
    background: PaleTurquoise;
    grid-area: content;
    /* Only change code below this line */
    display: grid;
    grid-template-columns: auto lfr;

    /* Only change code above this line */
  }

  .item4 {
    background: lightpink;
    grid-area: footer;
  }

  .itemOne {
    background: PaleGreen;
  }

  .itemTwo {
    background: BlanchedAlmond;
  }

</style>

<div class="container">
  <div class="item1">header</div>
  <div class="item2">advert</div>
  <div class="item3">
    <div class="itemOne">paragraph1</div>
    <div class="itemTwo">paragraph2</div>
  </div>
  <div class="item4">footer</div>
</div>
```
<br>

### Use display: flex to position two boxes
```HTML
<style>
  #box-container {
    height: 500px;
    display:flex;
  }

  #box-1 {
    background-color: dodgerblue;
    width: 50%;
    height: 50%;
  }

  #box-2 {
    background-color: orangered;
    width: 50%;
    height: 50%;
  }
</style>
<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```
<br>

### Use the flex-direction property to make a Row
`flex-direction: row-reverse;`
```HTML
<style>
  #box-container {
    display: flex;
    height: 500px;
    flex-direction: row-reverse;
  }
  #box-1 {
    background-color: dodgerblue;
    width: 50%;
    height: 50%;
  }

  #box-2 {
    background-color: orangered;
    width: 50%;
    height: 50%;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```
<br>

### Align elements using the justify-content
Move in main-axis.
```HTML
<style>
  #box-container {
    background: gray;
    display: flex;
    height: 500px;
    justify-content: center;

  }
  #box-1 {
    background-color: dodgerblue;
    width: 25%;
    height: 100%;
  }

  #box-2 {
    background-color: orangered;
    width: 25%;
    height: 100%;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```
<br>

### Align Elements Using the justify-content Property
```HTML
<style>
  #box-container {
    background: gray;
    display: flex;
    height: 500px;
    align-items: center;
  }
  #box-1 {
    background-color: dodgerblue;
    width: 25%;
    height: 100%;
  }

  #box-2 {
    background-color: orangered;
    width: 25%;
    height: 100%;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```
<br>

### Use the flex-wrap, shrink, flex-grow, flex-basis, shrthand, etc

### Reference
- [link](https://heropy.blog/2018/11/24/css-flexible-box/)