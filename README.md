# Ex.05 Book Cover Page Design
## Date:28-12-2025

## AIM:
To design a book back cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
cover.html

<html>
    <head>
        <title>Book cover page</title>
        <link href="styles.css" rel="stylesheet">
    </head>
    <body>
        <div class="container">
            <div class="header">
                <h1 align="center">About the Book</h1>
                <hr color="black" size="3" width="80%">
            </div>
            <div class="name">
                <h3>Name of the book:HTML AND CSS</h3>
            </div>
            <div class="content">
                <p>
                    <br><b>A book on **HTML and CSS** explains how to create and design web pages from scratch. It covers the basic structure of websites using HTML and shows how CSS is used to add colors, fonts, layouts, and responsive designs. This book is helpful for beginners who want to understand the fundamentals of web development and build simple, attractive websites..</br><b>
                </p>
            </div>
            <div class="quotes">
                <h4>"HTML builds the skeleton; CSS brings it to life."</h4>
            </div>
            <div class="author">
                <img src="pic7.jpeg" width="90" height="100" align="left" hspace="10" vspace="10">
                <h3 color="blue">ABINITHI H (25009178)</h3>
                <p>Abinithi H,A first year B.tech AIML student who is always passionate towards programming and to solve real life problems with the help of coding.</p>
            </div>
            <div class="footer">
                <h3 fontcolor="yellow">SEC PUBLISHERS</h3>
                <h3 align="right">Price:Rs.300/-</h3>
            </div>
        </div>
    </body>
</html>

styles.css

.container
{
    background:url("picg1.avif");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    height:720px;
    width:600px;
    border:4px solid cyan;
    border-radius: 10px 10px 10px 10px;
}
.header
{
    color:black;
}
.name
{
    background-color:yellow;
    width:53%;
    margin-left: 30px;
}
.content
{
    font-size: 20px;
    padding-left: 20px;
    padding-right: 20px;
}
.quotes
{
    width:500px;
    height: 50px;
    background-color: antiquewhite;
    margin-left: 30px;
    padding-left:20px;
    color:hotpink
}
.author
{
    width:500px;
    height:120px;
    background-color:bisque;
    margin-left: 30px;
    padding-left:20px;
    color:cadetblue;
}
.footer
{
    width:500px;
    height:60px;
    background-color:lightslategray;
    margin-left:30px;
    padding-left:20px;
    padding-bottom:15px;
    margin-top:20px;
    color:yellow;
    bottom: 0px;    
}

```


## OUTPUT:
![alt text](<Screenshot 2025-12-28 172259.png>)


## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
