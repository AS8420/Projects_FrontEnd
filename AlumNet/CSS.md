```css


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

.hero{
  display: flex ;
  align-items: center ;
  justify-content: space-between ;
  gap: 1.9rem ;
  width: 100% ;
/*   margin: 2rem auto -6rem */
  height: 658px;
}
.intro-text h1 {
    font-size: 3.5rem;
    margin-bottom: 1rem;
    font-family: unset;
}

.intro-text h3 {
  margin-bottom: 0.5rem;
}

.hero p {
    font-family: serif;
    font-size: 20px;
}

.hear {
  color: black;
}

.connecting {
  color: black;
  size: 50px;
}
.btn {
  margin-top: 1rem;
  display: inline-block;
  padding: 0.8rem 0.6rem;
  border: none;
  font-size: 1.4rem;
  border-radius: 5px;
  color: #fff;
}

.black {
  background-color: black;
  margin-right: 1.5rem;
}

.black:hover {
  background-color: black;
  color: #fff;
}

.black {
  background-color: black;
}

.black:hover {
  background-color: black;
  color: #fff;
}
img {
  width: 100%;  
  height: 658px;
  margin-top: 0.78px
}
```
