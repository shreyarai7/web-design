# web-design
practical no. 6
<!doctype html>

<head>

<title>Practical no 6</title>

<style>

.main{background-color:blue; padding: 50px;}

.container{display:grid;

grid-template-columns: repeat (4, 1fr);

grid-gap:20px;}

.items{background-color: pink;

border-radius: 5px; border: 3px green solid; color: black;}

</style>

</head>

<body>

<div class="container">

<div class="items"><img src="sunrise.jpg">
<p><h2>type: JPEG</h2></p><h2>size:13.3KB</h2></div>

<div class="items"><img src="sunrise.jpg">

<p><h2>type: JPG</h2></p><h2><p>size:11.4KB</p></h2></div>
<div class="items"><img src="sunrise.jpg">

<p><h2>type:WEBP</h2></p><h2><p>size:12.0KB</h2></p></div>

</div class ="items"><img src= "sunrise.jpg">
<p><h2>type: AVIF</h2></p><p><h2>size:5.50KB</h2><p></div>

<div class="main">
<iframe width="560" height="315" src="https://www.youtube.com/embed/YFmV_MRSD7M?si=UfGEQagFbn7roMNl"
 title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media;
 gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
<audio controls>
<source src="audiow.mp3">
</audio>
</body>
</html>
practical no. 5
<!DOCTYPE html>

<html lang="en">

<head>

<title>Page Title</title>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1">

<style>

body {

font-family: Arial, Helvetica, sans-serif;

}

.header {

padding: 80px;

text-align: center;

background: brown;

color: pink;

font-family:verdana, genova, san-serif;

text-shadow: 4px 4px 4px 10px black;

}

.header h1 {

font-size: 50px;

text-shadow: 4px 4px 4px 10px black;

}

.navbar {

overflow: hidden;

background-color: white;

}

.navbar a {

float: left;

display: block;

color: red;

text-align: center;

padding: 14px 20px;

text-decoration: underline;

}

.navbar a.right {

float: right;

}

.navbar a:hover {

background-color: #ddd;

color: black;

box-sizing: border-box;

{

}

.row {

display: flex;

flex-wrap: wrap;

}

.side {

flex: 30%;
}

.navbar a.right { float: right;

}

.navbar a:hover { background-color: #ddd;

color: green;

box-sizing: border-box;

.row {

display: flex;

flex-wrap: wrap; }

side {

flex: 30%;

<style> </head>

background-color: pink;

padding: 20px;

font-decoration:underline;

font-style: italic;

text-align: center;

text-transform: capitalize;

color: black;

}

main {

} flex: 70%;

background-color:green;

padding: 20px;

font-align:center;

letter spacing:0.1rem;

color: black;

@media screen and (max-width: 700px) {

.row {

flex-direction: column;
