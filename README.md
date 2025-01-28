<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sumit</title>
  
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background-color: black;
      color: white;
      font-family: 'Poppins', sans-serif;
    }

    nav {
      display: flex;
      justify-content: space-around;
      align-items: center;
      height: 80px;
      background-color: rgb(27, 27, 45);
    }

    nav ul {
      display: flex;
      justify-content: center;
    }

    nav ul li {
      list-style: none;
      margin: 0 23px;
      padding: 5px 10px;
      border-radius: 5px;
      transition: 0.3s ease-in-out;
    }

    nav ul li a {
      text-decoration: none;
      color: white;
    }

    nav ul li a:hover {
      color: lavender;
    }

    nav ul li:hover {
      background-color: rgb(131, 131, 159);
      cursor: pointer;
    }

    .left {
      font-size: 1.5rem;
    }

    .firstsection {
      display: flex;
      justify-content: space-around;
      margin: 23px;
    }

    .firstsection>div {
      width: 30%;
    }

    .rightsection {
      margin-top: 20px;
      width: 70%;
      margin: 0 23px;
    }

    .leftsection {
      margin-top: 12%;
      font-size: 2.5rem;
    }

    .purple {
      color: rgb(255, 0, 191);
    }

    
    .img {
      align-items: center;
      width: 100%;
      height: auto;
    }

  </style>
</head>

<body>
  <header>
    <nav>
      <div class="left">HEAVEN</div>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="about_me.html">About Me</a></li>
        <li><a href="home.html">Services</a></li>
        <li><a href="#">Projects</a></li>
        <li><a href="conatct.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="firstsection">
      <div class="leftsection">
        Hey, I am <span class="purple">Lee Euntae</span>
        <div>but you can also <br>call me Vasco.</div>
        <span id="element"></span>
      </div>
      <div class="rightsection">
        <img src="pngwing.com.png" alt="Lee Euntae" style="width: 100%; height: auto;">
      </div>
    </section>
  </main>

  <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
  <script>
    var typed = new Typed('#element', {
      strings: ['i am fighter.', 'I am a trainer.', 'I love Arts.'],
      typeSpeed: 50,
      backSpeed: 25,
      loop: true
    });
  </script>
</body>
</html>
