# Visual Studio
Visual Studio Projects

@page
@model IndexModel
@{
    ViewData["Title"] = "Home page";
    }
<!DOCTYPE html>
<html lang="en">

    <head>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@700&display=swap" rel="stylesheet">
        <div class="text-center">
            
                
                    <h1 class="display-4" style="font-family: 'Poppins', sans-serif; color: blue;">Hello and Welcome!</h1>
                
        <br />
        
        <title>Embedded music video</title>
    <body>
    
        <h2>Beautiful Things by Benson Boone</h2>
        <iframe width="560" height="315"
                src="https://www.youtube.com/embed/Oa_RSwwpPaA"
                frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen>
        </iframe>
        <br />
        <br />
        
            <div class="text-center">
                <h1 id="thank_you" class="display-4 green-text" onmouseover="Color1()" onmouseout="Color2()">Thank you and have a great day!</h1>
                
            </div>

    </body>   


    </head>
</html>





CSS
html {
  font-size: 14px;
}

body {
    background-color: lightgray;
}

@media (min-width: 768px) {
  html {
    font-size: 16px;
  }
}

.btn:focus, .btn:active:focus, .btn-link.nav-link:focus, .form-control:focus, .form-check-input:focus {
  box-shadow: 0 0 0 0.1rem white, 0 0 0 0.25rem #258cfb;
}

html {
  position: relative;
  min-height: 100%;
}

body {
  margin-bottom: 60px;
}




JS
// Please see documentation at https://learn.microsoft.com/aspnet/core/client-side/bundling-and-minification
// for details on configuring this project to bundle and minify static web assets.

// Write your JavaScript code.

function Color1() {
    document.getElementById("thank_you").style.color = "red";
}

function Color2() {
    document.getElementById("thank_you").style.color = "blue";
}




    

    <p>Learn about <a href="https://learn.microsoft.com/aspnet/core">building Web apps with ASP.NET Core</a>.</p>

