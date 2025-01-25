<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Our Love Wishlist 💖</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="motive">
      <h2>
        This is a small token of my love for you, <span style="color: red; font-weight: bold;">Harsha</span>. <br />
        You fill my life with happiness, love, and laughter.
        <br />
        <span>Thank you for being you 💖.</span>
      </h2>
    </div>
    <div class="instruction" style="color: rgba(181, 181, 181, 0.61);">
      <b>Swipe through the pages to explore!</b>
    </div>
    <div class="book">
      <div class="page cover-front" onclick="movePage(this, 1)">
        <h1>Our</h1>
        <h1>Love</h1>
        <h1>Wishlist 💖</h1>
        <img src="/mnt/data/WhatsApp Image 2024-12-29 at 1.53.19 PM.jpeg" alt="Love" style="width: 300px; aspect-ratio: auto 320 / 240; height: 240px; border-color: antiquewhite;">
        <h2>Forever & Always 💍</h2>
      </div>
      <div class="page text-page" onclick="movePage(this, 2)">
        <p>Dear love,</p>
        <p>
          Meeting you was the best thing that ever happened to me. 
          Your love, kindness, and strength inspire me every day. 💖
        </p>
        <img src="/mnt/data/WhatsApp Image 2024-12-29 at 1.53.19 PM.jpeg" alt="Our Moments" width="320" height="240">
        <br /><br />
        <p>Please turn the page...</p>
      </div>
      <div class="page text-page" onclick="movePage(this, 3)">
        <p>
          You are my rock, my safe place, and my biggest blessing. 
          Life with you is a journey I want to continue forever. 💕
        </p>
        <p>
          Thank you for loving me unconditionally, supporting me in every way, and being my partner in everything. 
          You complete me, and I can’t imagine life without you.
        </p>
        <img src="/mnt/data/WhatsApp Image 2024-12-29 at 1.53.19 PM.jpeg" alt="Couple" width="320" height="240">
        <br /><br />
        <p>Please turn the page...</p>
      </div>
      <div class="page text-page" onclick="movePage(this, 4)">
        <p>
          Our love is like a beautiful garden, growing with care and nurtured by the moments we share. 🌸
        </p>
        <p>
          I promise to cherish every moment with you, to support you through thick and thin, and to love you endlessly. 💍
        </p>
        <p>
          With you by my side, every day feels like a blessing, and every moment is worth celebrating. 💖
        </p>
        <img src="/mnt/data/WhatsApp Image 2024-12-29 at 1.53.19 PM.jpeg" alt="Together" width="320" height="240">
      </div>
      <div class="page text-page">
        <p>
          Here’s to our dreams, our love, and our forever. 🥂
        </p>
        <p>
          I love you more than words can ever express. Thank you for being my everything. ❤️
        </p>
        <h2>Forever Yours, 💖</h2>
        <br />
        <img src="/mnt/data/WhatsApp Image 2024-12-29 at 1.53.19 PM.jpeg" alt="Forever Together" width="320" height="240">
        <button id="botao1">I Love You Too! 💕</button>
      </div>
      <div class="page"></div>
      <div class="page"></div>
    </div>

    <script>
      function movePage(page, nextPageNumber) {
        // Simulate page turning animation or action
        alert('Turning to page ' + nextPageNumber);
      }

      document.getElementById("botao1").addEventListener("click", function () {
        alert("YAY! Love you endlessly! 😍❤️");
      });
    </script>
  </body>
</html>
