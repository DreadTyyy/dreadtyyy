# dreadtyyy.github.io
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>This Is html</title>
    <link href="https://fonts.googleapis.com/css2?family=Lobster&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Amatic+SC:wght@700&family=Lobster&family=Permanent+Marker&family=Saira+Condensed&display=swap" rel="stylesheet">

    <style>
      *{
        margin: 0px;
        padding: 0px;
      }
      body{
        background-image: linear-gradient(160deg, rgba(250,128,114, 0.5),rgba(240,128,128,0.5));
        background-repeat: repeat-y;

      }
      .pertanyaan{
        margin: 100px;
        margin-top: 60px;
        background: #F0FFFF;
        padding: 10px;
        display: flex;
        border-radius: 25px;
        flex-direction: column;
        color: black;
        text-align: center;

      }
      h1{
        margin: 10px;
        text-align: center;
        font-family: 'Lobster', cursive;
        font-size: 40px;
        letter-spacing: 2px;
        text-decoration: overline;
        text-decoration-style: double;

      }

      .soal{
        margin: 25px;
        margin-left: 445px;
        background-color: #000;
        width: 250px;
        height: 70px;
        line-height:50px;
        text-align: center;
        font-size: 37px;
        color: white;

      }
      .jawaban button{
        width: 120px;
        height: 55px;
        font-family: 'Saira Condensed', sans-serif;
        font-weight: bold;
        font-size: 27px;
        outline: none;
        margin: 0px 10px;
    }
      .opsiA{
        position: absolute;
        left: 500px;
        top: 350px;
        background-color: #0b0b0b;
        color: aqua;
        border: 3px solid #fff;
      }

      .opsiB{
        position: absolute;
        left: 780px;
        top: 350px;
        background-color: #0b0b0b;
        color: aqua;
        border: 3px solid #fff;
      }

      button:active{
        transform: scale(1.1);
      }


    </style>
  </head>
  <body>


      <div class="pertanyaan">
        <h1> Refreshing otak bentar yaa </h1>
        <p class="soal">x <sup> 2 </sup> - 3x -18 = 0 </p>
        <!-- soal x kuadrat dikurangi 3x dikurangi 18 sama dengan 0-->
      </div>

      <!-- pilihan jawaban a atau b untuk a jawaban benar dan b jawaban salah-->
      <div class="jawaban">
          <button class="opsiA"> X = 6 </button>
          <button class="opsiB"> X = 3 </button>

      </div>
      



  </body>
</html>
