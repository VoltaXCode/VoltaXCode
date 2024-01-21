<h2 align="center">Volta</h1>
<h3 align="center">Çok Yönlü Yazılım Geliştiricisiyim</h3>

<h3 align="left">Benimle İletişime Geçebilmen İçin</h3>
<p align="left">
<a href="https://discord.gg/discord.gg/via" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="discord.gg/via" height="40" width="40" /></a>
</p>

<h3 align="left">Özetleme Kullandığım Diller</h3>
<p align="left"> <a href="https://golang.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="go" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://www.php.net" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>

</head>
<body>
  <pre>
📁 Volta's
├ 📂 Malware Developing
│ ├ 📝 Python
│ ├ 📝 Javascript
│ └ 📝 Bat
├ 🐀 R4t Development
│ ├ 🪱 Fud Methods
│ └ 🪱 +9 Fud Method
├ 📂 Developing Languages
│ ├ 📝 GoLang
│ ├ 📝 Javascript
│ ├ 📝 Python
│ └ 📝 Php
├ 📜 Social Medias
│  ├ 🔱 Discord	
│  └ 🔱 Spotify
└────────────────>
  </pre>
</body>
</html>

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
