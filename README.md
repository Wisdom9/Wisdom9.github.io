<!DOCTYPE html>
<html>
    <head>
        <title><Wisdom</title>
        <style>
           h1 {
            font-size: 75px;
           } 
           header {
            background: linear-gradient(110deg, rgb(121, 121, 255) 40%, rgb(58, 58, 194) 40%);
           }
           section {
               background : lightgray;
           }
           footer {
               background : black;
               color : white;
           }
           div {
               text-align:center;
               padding: 40px;
           }
           h3 {
              border: 2px solid white;
              font-size: 45px;
              padding: 15px;  
              margin: auto;    
              
           }
           p {
               font-size : 30px
           }
           input {
               border : 2px solid black  ;
               font-size: larger;
           }
           img {
               border-radius: 50%;
               border : 8px  black;
               border-style: outset;
               width: 20%;
           }
           body {
               background-image: url(bg.png);
           }
           .circle {
                color: white;
                font-size: 2.5em;
                display: inline-block; height: 40px;
                width: 40px;
                margin: 15px;
                border-radius: 50%; 
                background: blue; 
                padding: 5px 10px 15px 10px; 
                font-family: helvetica;
            }  
            button {
                background: lightgray;
                border: 2px solid black;
                font-size: 2em;
                border-style: dashed;
            }    
            .a {
                font-size: 4em;
                color : white;
            }
        </style>
    </head>
    <body>
        <header>
            <nav>
                <div>
                <a href="hi.html" class="a" > Home |</a>
                <a href="cv.html" class="a" >CV |</a>        
                <a href="projects.html" class="a" >Projects</a>           
                </div>  
            </nav>
            <div>
                <h1>Wisdom Myxzptlk</h1> 
                <img src= "wisdom.jpg">
                <p>Hi! I'm Wisdom Myxzptlk, a software developer. Say hello!</p>
                <input type="text" placeholder="Your email"> <input type="Submit">
            </div>
        </header>
        <div>
            <section>
                <h3><i>Motivation: I want to learn to code because i hope to solve problems affecting the world</i> </h3>
            </section>
            <section>
                <h4>
                <u>My story 
                :</u> My name is Wisdom Mathonisa, I am a 16 year old software developer. I currently study at Curtis Nkondo School of Specialisation(Grade 12).I started being interested in programming when i won a Macbook Air laptop in a math competition(Siyavula) and that was my head start. I am passionate about how software works and particularly how it was made thus making me be eager to learn to program. I have learnt several programming languages like Python, C# and Delphi but I specialise mainly in Desktop apps with Delphi and I also make simple websites for small businesses using Html, Css and Javascript.
                </h4>
            </section>
            <button onclick="getPage();"><a href="cv.html">Click here for MY CV</a></button>
            <button onclick="getPage();"><a href="cv.html">Click here for MY PROJECTS</a></button>
            
        </div>
        <div>
            <footer>
            <div class="circle">M</div> 
            <div class="circle">Y</div> 
            <div class="circle">X</div>
            <div class="circle">Z</div> &copy Copyright 2021 Wisdom Myxzptlk
            </footer>
        </div>
    </body>
</html>
