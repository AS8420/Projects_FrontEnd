```html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Side bar menu</title>
  <style media="screen">
    @import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,500;1,400&display=swap');
    
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
    
    html {
        font-size: 62.5%;
        font-family: sans-serif;
    }
    
    li {
        list-style: none;
    }
    
    a {
        text-decoration: none;
    }
    
    .header{
        border-bottom: 1px solid #E2E8F0;
    }
    
    .navbar {
        display: flex;
        justify-content: space-between;
        align-items: center;
        background-color: #151617;
        padding: 1rem 1.5rem;
    }
    
    .hamburger {
        display: none;
    }
    
    .bar {
        display: block;
        width: 25px;
        height: 3px;
        margin: 5px auto;
        -webkit-transition: all 0.3s ease-in-out;
        transition: all 0.3s ease-in-out;
        background-color: white;
    }
    
    .nav-menu {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    
    .nav-item {
        margin-left: 3rem;
    }
    
    .nav-link{
        font-size: 19px;
    
        color: white;
    }
    
    .nav-link:hover{
        color: #1ae5f7;
    }
    
    .nav-logo {
        font-size: 30px;
        font-weight: 500;
        color: white;
    }
    
    @media only screen and (max-width: 668px) {
        .nav-menu {
            position: fixed;
            left: -100%;
            top: 5rem;
            flex-direction: column;
            background-color: #3d3d3d;
            width: 100%;
            padding-top: 20px;
            padding-bottom: 20px;
            text-align: center;
            transition: 0.3s;
    
        }
    
        .nav-menu.active {
            left: 0;
        }
    
        .nav-item {
            margin: 2.5rem 0;
    
        }
    
        .hamburger {
            display: block;
            cursor: pointer;
        }
    
        .hamburger.active .bar:nth-child(2) {
            opacity: 0;
        }
    
        .hamburger.active .bar:nth-child(1) {
            -webkit-transform: translateY(8px) rotate(45deg);
            transform: translateY(8px) rotate(45deg);
        }
    
        .hamburger.active .bar:nth-child(3) {
            -webkit-transform: translateY(-8px) rotate(-45deg);
            transform: translateY(-8px) rotate(-45deg);
        }
    }

  </style>

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
                    <a href="#" class="nav-link">Registration</a>
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
            </ul>
            <div class="hamburger">
                <span class="bar"></span>
                <span class="bar"></span>
                <span class="bar"></span>
            </div>
        </nav>
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
