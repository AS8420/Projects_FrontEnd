```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <link rel="stylesheet" href="style.css" />
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>AlumNet</title>
  </head>
<body>
      <header class="header">
        <nav class="navbar">
            <a href="#" class="nav-logo">AlumNET</a>
            <ul class="nav-menu">
                <li class="nav-item">
                    <a href="#" class="nav-link">Home</a>
                </li>
                <li class="nav-item">
                    <a href="https://form.wewillwin1.repl.co/" class="nav-link">Registration</a>
                </li>

                <li class="nav-item">
                    <a href="#" class="nav-link">Connect</a>
                </li>
                <li class="nav-item">
                    <a href="#" class="nav-link">About us</a>
                </li>
                <li class="nav-item">
                    <a href="#" class="nav-link">Profile</a>
                </li>
                <li></li>
            </ul>
            <div class="hamburger">
                <span class="bar"></span>
                <span class="bar"></span>
                <span class="bar"></span>
            </div>
        </nav>
         <section class="hero">
      <div style="float: left; width: 50%; margin-left: 25px;" class="intro-text">
        <h1>
          <span class="hear"> This is the platform that is a bridge between Directorate and Trainess </span> <br />
          <span class="connecting"> <strong>A</strong>lum<strong>NET</strong></span>
        </h1>
        <p>
          A student entered in college with so many dreams and questions. They need a guidance from a person who already gone through those situations and experienced all those things. What are the course expertises? How to manage the different skills with curriculum? Where the opportunities lies? Which course will help them in their career? And so many queries and doubts whose can be resolved by an experienced persona. 
<br />
        Who can be better than a passed out student from same college for all those valuable guidance? An Alumni is the person who can provide the best guidance and a society for like minded students. But there always a barrier of lack of communication arises. There is missing puzzle which can be solved by our project "AlumNET”.
        </p>
        <a class="btn black" href="https://form.wewillwin1.repl.co/">Sign In</a>
        <a class="btn black" href="https://login.ok1098.repl.co/">Log In</a>
      </div>
      <div class="i-frame">
        <img src="alumnimg.png">
      </div>
    </section>
    </header>
    <script>
const hamburger = document.querySelector(".hamburger");
const navMenu = document.querySelector(".nav-menu");
const navLink = document.querySelectorAll(".nav-link");

hamburger.addEventListener("click", mobileMenu);
navLink.forEach(n => n.addEventListener("click", closeMenu));

function mobileMenu() {
    hamburger.classList.toggle("active");
    navMenu.classList.toggle("active");
}

function closeMenu() {
    hamburger.classList.remove("active");
    navMenu.classList.remove("active");
}
    </script>
</body>
</html>
```
