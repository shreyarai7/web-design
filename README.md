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
 flex-direction: column;

navbar a)

@media screen and (max-width: 100px) {

float nore;

width: 100%;

footer {

padding: 0px;

text-align:center;

background: green;

color: black;

text-shadow: 4px 4px 4px 10px;

font-family:arial, helvetica, san-serif; }

</style>

</head>

choty>

Ln 66, Col 15 2,977 characters

<body>

<div class="header">

<p><img src="logo.png"></p>

<<<h1>Edumind Academy</h1>

Welcomel come to the

Future of Education.</p>

</div>

<div class="navbar">

<a href="#">www.onlineclass.com</a>

<a href="#">www.xyz.com</a>

<a href="#">вым.руq.com/ax <a href="#" class="right">Link</a>

</div>

<div class="row">

<div class="side">"Empovering students to succeed, education Academy provides a suppertive and inclusive learning environment. Our expert educators deliver personalized instruction, fostering academic excellence and personal growth. With a focus on Innovation and creativity, we prepare students for success in an ever-changing world."

</div> </div>

</body>

</html>

practical no. 4
a. box model
<!DOCTYPE html>

<html lang="en">

<meta charset="UTF-8" />

<meta name="viewport" content="width=device-width, initial-scale-1.0" />
<head>

consent in CSS

<title>Browser</title>

<style> div{ background-color: yellow;

height: 200px; width:300px; padding: 18px; border: 10px solid black;

margin:20px;}
</style>

</head>

<body> <h1>
CSS Information
</h1>
<p>

<div>CSS (Cascading Style Sheets) is a stylesheet language used to control the layout and appearance of HTML elements on a web page. It allows developers to define styles for elements such as colors, fonts, spacir positioning, and more. CSS can be written inline within HTML, embedded in the <style> tag, or linked externally in a separate file. By separating content (HTML) from presentation (CSS), it makes web design more efficient and maintainable.CSS also enables responsive design, ensuring websites look great across different devices and screen sizes.
</div>
</p>
<script src="script.js"></script>
</body>
</html>
b. media queries 
<!DOCTYPE html>

<html>

<head>

<style>

@media screen and (max-width: 480px), screen and (orientation: landscape) (

body { background-color: pink;

}

</style>

<body>

</head>

<h1>About the Government College College of Engineering, Nagpuri</h1>

<p>This Institute, commonly referred as GGBEN, was started functioning in 2016 with 5 UG & 1 PG Engineering Programmes under the administrative control of Higher and Technical Education, Govt. of Maharashtra. The Institute is affiliated to RTM Nagpur University Nagpur, within a short span of time, GCOEN has established its own identity not only in the Vidarbha region but also in the Maharashtra State. The students of high caliber are the backbones of the Institute.</p>
</body>
</html>
float property 
<!DOCTYPE html>

<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0> <title>Float Property</title>

<style>

body{margin:0 auto;

}

max-width: 900px; width:90%;#box{float:left;

margin:15px;

width:150px;

height:150px;

border-radius:5px;

background-color:blue;

}

padding: 1em;

.special{background-color:red; padding:15px;
}

color:pink;

.cleared{clear: left

}</style>

</head>

<body>

<h1>Float Property</h>

<img id="box" src="pic.jpeg" alt="pic">

<h1 class="special">Resume</h1>
<p>A resume opening statement is an important part of a job application, as it provides employers with the first impression of an applicant. A well-crafted statement can help stand out from the competition and increase their chances of being noticed and considered for a position.</p> <p>The primary benefit of a resume opening statement is that it allows applicants to quickly and efficiently summarize their career goals, qualifications and experiences. This should be concise yet powerful. It should capture the attention of employers and help them to understand why an applicant is an ideal fit for the job. In addition to summarizing qualifications, a resume opening statement can also be used to express the applicant's enthusiase for the position and highlight any unique skills they This helps employers to get a better sense of the applicant's personality and can help to spark their interest.</p>
</body>
</html>
practical no. 10
<!DOCTYPE html>
<html>
    <head>
        <title>SCSS</title>
        <link rel="stylesheet" href="./style.css">
    </head>
 <style>
    /* Variables */
$primary-color: #007acc;
$secondary-color: #005f99;
$light-bg-color: #f9f9f9;
$white-color: #ffffff;
$text-color: #000000;
$box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
$border-radius: 8px;
$font-family: Arial, sans-serif;

/* Global styles */
body {
  font-family: $font-family;
  margin: 0;
  padding: 0;
  background-color: $light-bg-color;
}

header {
  background-color: $primary-color;
  color: $white-color;
  padding: 1rem;
  text-align: center;
}

nav {
  background-color: $secondary-color;
  padding: 0.5rem;
  text-align: center;

  a {
    color: $white-color;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;

    &:hover {
      text-decoration: underline;
    }
  }
}

main {
  padding: 2rem;
}

.tutorial {
  background-color: $white-color;
  padding: 1rem;
  margin-bottom: 1rem;
  border-radius: $border-radius;
  box-shadow: $box-shadow;
}

footer {
  background-color: $primary-color;
  color: $white-color;
  text-align: center;
  padding: 1rem 0;
  position: fixed;
  width: 100%;
  bottom: 0;
}

#codeEditor {
  width: 100%;
  height: 200px;
  margin-top: 1rem;
  font-family: monospace;
  border: 1px solid lighten($primary-color, 30%);
  border-radius: $border-radius;
  padding: 1rem;
  background: #f4f4f4;
}

#runCode {
  margin-top: 10px;
  padding: 10px 15px;
  background-color: $primary-color;
  color: $white-color;
  border: none;
  cursor: pointer;
  border-radius: $border-radius;

  &:hover {
    background-color: darken($primary-color, 10%);
  }
}

#output {
  margin-top: 1rem;
  padding: 1rem;
  background-color: #e6ffe6;
  border: 1px solid #00b300;
  border-radius: $border-radius;
}

 </style>
    <body>
        
<header>
    <h1>Interactive Coding Tutorials</h1>
  </header>
  
  <nav>
    <a href="#">Home</a>
    <a href="#">Tutorials</a>
    <a href="#">Challenges</a>
    <a href="#">Community</a>
    <a href="#">About</a>
  </nav>
  
  <main>
    <div class="tutorial">
      <h2>Learn JavaScript: Basics</h2>
      <p>Start with the fundamentals of JavaScript. Write your code in the editor below and see the output instantly.</p>
      <textarea id="codeEditor">// Write your JavaScript code here\nconsole.log('Hello, World!');</textarea>
      <button id="runCode">Run Code</button>
      <div id="output"></div>
    </div>
  </main>
  
  <footer>
    <p>&copy; 2024 Interactive Coding Tutorials. All Rights Reserved.</p>
  </footer>
  
  <script>
    const runButton = document.getElementById('runCode');
    const codeEditor = document.getElementById('codeEditor');
    const outputDiv = document.getElementById('output');
  
    runButton.addEventListener('click', () => {
      try {
        const userCode = codeEditor.value;
        const result = eval(userCode); // Caution: eval should be used carefully in real-world applications
        outputDiv.textContent = result || 'Code executed successfully!';
      } catch (error) {
        outputDiv.textContent = 'Error: ' + error.message;
      }
    });
  
    </body>
    </script>
</html>
practical no 1
<!DOCTYPE html>
<html>
    <head>
        <title>Registration form</title>
       
    </head>
    <body>
    <form>
        <h1><b>REGISTRATION FORM</h1>

            <p><b><ol><li>NAME: <input type="text" required</p1>
            
            <p2><NAME="First name"></p2>
            
            <p3><input type="last name "required></p3> <p><br><br><li>D. 0. B*<input type="date" required></p>
            
            <p5><br><br><li>*GENDER: <br> male<input type="radio" name="gender" id=male></li>p5>
            
            <p6>female<input type="radio" name="gender" id=female required></p6> <p7><li>EMAIL ADDRESS: <input type="email" required></p7>
            
            <p8<br><br><li>ADDRESS: <input type="text" required</p>
            
            <p><br><br><li>PIN CODE: <input type="4 numbers" required> </p9>
            
            -<p10><br><br><li>*BRANCH: <br><input type="checkbox" required>CSE<br>
            
            <input type="checkbox" required>ETC <br>
            
            <input type="checkbox" required>EE<br> <input type="checkbox" required>ME<br>
            
            <input type="checkbox" required>CE<br>
            
            <br><11>PHONE NO.:<input type="numbers"> <br><br>
            
            cultural activities included:
            
            <br><ol><li>folk dance<br>
            
            -<li>solo dance<br><li>hip hop dance
            
            <p11><br><br><li>Card type: <select name="Card type" id="card type"></p11
            
            <option value="">Select a card type</option>
            
            <option value="Visa">Visa</option>
            
            <option value="rupay">Rupay</option>
            
            <option value="BHIM UPI"> BHIM UPI</option>
            
            </select><br><br>
            
            <li>Card number <input type="number "name="card number"
            
            id="cardnumber"> <br><br>
            
            <li>Expiration Date: <input type="date" name="exp_date"
            
            id="exp_date"> <br><br>
            
            <li>CVV <input type="password"
            
            name="CV" id="CVV"> <br><br>
            
            for any query contact us on
            
            <a href="https://www.doubtsolve.com/">visit www.doubtsolve.com</a><br>
            
            <br><input type="submit" value="Pay Now"> <br>
            
            <br><br><input type=submit value =submit> <br><br>
            
            <input type reset value reset>
    </form>
        

  
    </body>
    
</html>
