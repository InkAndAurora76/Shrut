
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

    <!-- Disqus comment embed (you can replace shortname later) -->
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
