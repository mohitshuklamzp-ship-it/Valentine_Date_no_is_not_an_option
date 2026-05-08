<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Happy Birthday Aadi 💗</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: 'Poppins', sans-serif;
    }

    body{
      height:100vh;
      display:flex;
      justify-content:center;
      align-items:center;
      background: linear-gradient(135deg,#ff9ec4,#ffd6e8,#fff0f6);
      overflow:hidden;
    }

    .container{
      text-align:center;
      z-index:2;
    }

    h1{
      color:white;
      font-size:2.5rem;
      margin-bottom:20px;
      text-shadow:0 4px 10px rgba(0,0,0,0.2);
      animation: float 2s infinite ease-in-out;
    }

    .btn{
      padding:16px 35px;
      border:none;
      border-radius:50px;
      font-size:1.2rem;
      cursor:pointer;
      background:white;
      color:#ff4f8b;
      font-weight:600;
      box-shadow:0 8px 25px rgba(0,0,0,0.15);
      transition:0.3s;
    }

    .btn:hover{
      transform:scale(1.08);
    }

    .letter{
      width:90%;
      max-width:500px;
      margin-top:30px;
      background:white;
      padding:30px;
      border-radius:25px;
      box-shadow:0 10px 30px rgba(0,0,0,0.2);
      color:#444;
      line-height:1.8;
      font-size:1.1rem;
      opacity:0;
      transform:translateY(30px);
      transition:1s;
    }

    .show{
      opacity:1;
      transform:translateY(0);
    }

    .heart{
      position:absolute;
      color:#ff4f8b;
      animation: fall linear forwards;
      font-size:20px;
    }

    @keyframes fall{
      0%{
        transform:translateY(-10vh) rotate(0deg);
        opacity:1;
      }
      100%{
        transform:translateY(110vh) rotate(360deg);
        opacity:0;
      }
    }

    @keyframes float{
      0%,100%{
        transform:translateY(0px);
      }
      50%{
        transform:translateY(-8px);
      }
    }
  </style>
</head>

<body>

  <div class="container">
    <h1>🎂 Birthday Surprise 🎂</h1>

    <button class="btn" onclick="showLetter()">
      Press Here 💌
    </button>

    <div class="letter" id="letter">
      <h2>Happy Birthday Aadi 💗</h2>
      <br>

      <p>
        Maybe you achieve every single piece of happiness and achieve every future goal. ✨
      </p>

      <p>
        Maybe your future glows like the sun ☀️
      </p>

      <p>
        Be happy as you are now with Dhiraj 💖
      </p>

      <br>

      <h3>
        Lots of love didi 🫶
      </h3>
    </div>
  </div>

  <script>
    function showLetter(){
      document.getElementById("letter").classList.add("show");

      for(let i=0; i<70; i++){
        createHeart();
      }
    }

    function createHeart(){
      const heart = document.createElement("div");
      heart.classList.add("heart");
      heart.innerHTML = "💖";

      heart.style.left = Math.random() * 100 + "vw";
      heart.style.animationDuration = (Math.random() * 3 + 2) + "s";
      heart.style.fontSize = (Math.random() * 20 + 15) + "px";

      document.body.appendChild(heart);

      setTimeout(()=>{
        heart.remove();
      },5000);
    }
  </script>

</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Happy Birthday Aadi 💗</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: 'Poppins', sans-serif;
    }

    body{
      height:100vh;
      display:flex;
      justify-content:center;
      align-items:center;
      background: linear-gradient(135deg,#ff9ec4,#ffd6e8,#fff0f6);
      overflow:hidden;
    }

    .container{
      text-align:center;
      z-index:2;
    }

    h1{
      color:white;
      font-size:2.5rem;
      margin-bottom:20px;
      text-shadow:0 4px 10px rgba(0,0,0,0.2);
      animation: float 2s infinite ease-in-out;
    }

    .btn{
      padding:16px 35px;
      border:none;
      border-radius:50px;
      font-size:1.2rem;
      cursor:pointer;
      background:white;
      color:#ff4f8b;
      font-weight:600;
      box-shadow:0 8px 25px rgba(0,0,0,0.15);
      transition:0.3s;
    }

    .btn:hover{
      transform:scale(1.08);
    }

    .letter{
      width:90%;
      max-width:500px;
      margin-top:30px;
      background:white;
      padding:30px;
      border-radius:25px;
      box-shadow:0 10px 30px rgba(0,0,0,0.2);
      color:#444;
      line-height:1.8;
      font-size:1.1rem;
      opacity:0;
      transform:translateY(30px);
      transition:1s;
    }

    .show{
      opacity:1;
      transform:translateY(0);
    }

    .heart{
      position:absolute;
      color:#ff4f8b;
      animation: fall linear forwards;
      font-size:20px;
    }

    @keyframes fall{
      0%{
        transform:translateY(-10vh) rotate(0deg);
        opacity:1;
      }
      100%{
        transform:translateY(110vh) rotate(360deg);
        opacity:0;
      }
    }

    @keyframes float{
      0%,100%{
        transform:translateY(0px);
      }
      50%{
        transform:translateY(-8px);
      }
    }
  </style>
</head>

<body>

  <div class="container">
    <h1>🎂 Birthday Surprise 🎂</h1>

    <button class="btn" onclick="showLetter()">
      Press Here 💌
    </button>

    <div class="letter" id="letter">
      <h2>Happy Birthday Aadi 💗</h2>
      <br>

      <p>
        Maybe you achieve every single piece of happiness and achieve every future goal. ✨
      </p>

      <p>
        Maybe your future glows like the sun ☀️
      </p>

      <p>
        Be happy as you are now with Dhiraj 💖
      </p>

      <br>

      <h3>
        Lots of love didi 🫶
      </h3>
    </div>
  </div>

  <script>
    function showLetter(){
      document.getElementById("letter").classList.add("show");

      for(let i=0; i<70; i++){
        createHeart();
      }
    }

    function createHeart(){
      const heart = document.createElement("div");
      heart.classList.add("heart");
      heart.innerHTML = "💖";

      heart.style.left = Math.random() * 100 + "vw";
      heart.style.animationDuration = (Math.random() * 3 + 2) + "s";
      heart.style.fontSize = (Math.random() * 20 + 15) + "px";

      document.body.appendChild(heart);

      setTimeout(()=>{
        heart.remove();
      },5000);
    }
  </script>

</body>
</html>
