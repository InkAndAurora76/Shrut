
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>QuoteGalaxy</title>



  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #ffecd2 0%, #fcb69f 100%);
      color: #333;
    }
    header {
      background: #ff6f61;
      color: white;
      padding: 1rem;
      text-align: center;
      font-size: 2rem;
      font-weight: bold;
    }
    .container {
      max-width: 800px;
      margin: 2rem auto;
      padding: 0 1rem;
    }
    .quote {
      background: white;
      padding: 1.5rem;
      margin: 1rem 0;
      border-left: 5px solid #ff6f61;
      border-radius: 8px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }
    .tag {
      background: #ffd166;
      display: inline-block;
      padding: 0.3rem 0.7rem;
      border-radius: 4px;
      font-size: 0.8rem;
      margin-top: 0.5rem;
      color: #333;
    }
    footer {
      text-align: center;
      padding: 2rem 1rem;
      background: #fcb69f;
      color: #fff;
      margin-top: 3rem;
    }
  </style>
</head>
<body>
  <header>QuoteGalaxy</header>
  <div class="container">
    <div class="quote">
      <p>"The best way to predict the future is to invent it."</p>
      <span class="tag">#motivation</span>
    </div>
    <div class="quote">
      <p>"Be yourself; everyone else is already taken."</p>
      <span class="tag">#life</span>
    </div>
    <div class="quote">
      <p>"Happiness is not something ready made. It comes from your own actions."</p>
      <span class="tag">#happiness</span>
    </div>
    <div class="quote">
      <p>"In the middle of every difficulty lies opportunity."</p>
      <span class="tag">#inspiration</span>
    </div>
    <div class="quote">
      <p>"Every moment is a fresh beginning."</p>
      <span class="tag">#inspiration</span>
    </div>
    <div class="quote">
      <p>"Creativity is intelligence having fun."</p>
      <span class="tag">#creativity</span>
    </div>
    <div class="quote">
      <p>"Success is not the key to happiness. Happiness is the key to success."</p>
      <span class="tag">#success</span>
    </div>
    <div class="quote">
      <p>"Doubt kills more dreams than failure ever will."</p>
      <span class="tag">#dreams</span>
    </div>
    <div class="quote">
      <p>"You are never too old to set another goal or to dream a new dream."</p>
      <span class="tag">#goals</span>
    </div>
    <div class="quote">
      <p>"Do what you can, with what you have, where you are."</p>
      <span class="tag">#action</span>
    </div>
    <div class="quote">
      <p>"Believe you can and you're halfway there."</p>
      <span class="tag">#believe</span>
    </div>
    <div class="quote">
      <p>"Your time is limited, so don’t waste it living someone else’s life."</p>
      <span class="tag">#truth</span>
    </div>
    <div class="quote">
      <p>"It always seems impossible until it’s done."</p>
      <span class="tag">#determination</span>
    </div>
    <div class="quote">
      <p>"Try to be a rainbow in someone’s cloud."</p>
      <span class="tag">#kindness</span>
    </div>
    <div class="quote">
      <p>"Turn your wounds into wisdom."</p>
      <span class="tag">#wisdom</span>
    </div>
    <div class="quote">
      <p>"We are what we repeatedly do. Excellence, then, is not an act, but a habit."</p>
      <span class="tag">#excellence</span>
    </div>
    <div class="quote">
      <p>"Act as if what you do makes a difference. It does."</p>
      <span class="tag">#purpose</span>
    </div>
    <div class="quote">
      <p>"To handle yourself, use your head; to handle others, use your heart."</p>
      <span class="tag">#leadership</span>
    </div>
    <div class="quote">
      <p>"What you get by achieving your goals is not as important as what you become by achieving your goals."</p>
      <span class="tag">#growth</span>
    </div>
    <div class="quote">
      <p>"A person who never made a mistake never tried anything new."</p>
      <span class="tag">#learning</span>
    </div>
    <div class="quote">
      <p>"Don’t let yesterday take up too much of today."</p>
      <span class="tag">#focus</span>
    </div>
    <div class="quote">
      <p>"Strive not to be a success, but rather to be of value."</p>
      <span class="tag">#value</span>
    </div>
    <div class="quote">
      <p>"Life is 10% what happens to us and 90% how we react to it."</p>
      <span class="tag">#attitude</span>
    </div>

    <!-- Disqus Comment Section -->
    <div id="disqus_thread" style="margin-top: 4rem;"></div>
    <script>
      var disqus_config = function () {
        this.page.url = window.location.href;
        this.page.identifier = 'quotegalaxy-home';
      };
      (function() {
        var d = document, s = d.createElement('script');
        s.src = 'https://quotegalaxy.disqus.com/embed.js';
        s.setAttribute('data-timestamp', +new Date());
        (d.head || d.body).appendChild(s);
      })();
    </script>
    <noscript>Please enable JavaScript to view the comments powered by Disqus.</noscript>
  </div>
  <footer>
    &copy; 2025 QuoteGalaxy | Made with ❤️ for quote lovers
  </footer>
</body>
</html>
