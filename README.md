<h1 align="center">
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
  Hey, I'm Your Name
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
</h1>

<h3 align="center">
  I'm a <span class="typing-effect"></span>
</h3>

<div align="center">
  <img class="rotating-image" src="https://avatars.githubusercontent.com/u/ghost3jelly" width="200" height="200" alt="Profile Picture">
</div>

<p align="center">
  A brief introduction about yourself goes here.
</p>

<p align="center">
  <a href="https://twitter.com/your-twitter-handle">Twitter</a> •
  <a href="https://www.linkedin.com/in/your-linkedin-profile">LinkedIn</a> •
  <a href="https://your-website.com">Website</a>
</p>

<div align="center">
  <img src="https://media.giphy.com/media/JIX9t2j0ZTN9S/giphy.gif" width="600" height="300" frameBorder="0" class="giphy-embed" allowFullScreen></img>
</div>

<style>
  body {
    background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
    background-size: 400% 400%;
    animation: gradient 15s ease infinite;
    height: 100vh;
  }

  @keyframes gradient {
    0% {
      background-position: 0% 50%;
    }
    50% {
      background-position: 100% 50%;
    }
    100% {
      background-position: 0% 50%;
    }
  }

  .typing-effect {
    display: inline-block;
    white-space: nowrap;
    overflow: hidden;
    animation: typing 5s steps(30, end), blink-caret 0.75s step-end infinite;
    border-right: .15em solid orange;
    font-size: 1.5em;
  }

  @keyframes typing {
    from { width: 0 }
    to { width: 100% }
  }

  @keyframes blink-caret {
    from, to { border-color: transparent }
    50% { border-color: orange; }
  }

  .rotating-image {
    animation: rotation 10s infinite linear;
    border-radius: 50%;
    border: 5px solid #fff;
    box-shadow: 0 0 10px #fff, 0 0 20px #fff, 0 0 30px #e60073, 0 0 40px #e60073, 0 0 50px #e60073, 0 0 60px #e60073, 0 0 70px #e60073;
  }

  @keyframes rotation {
    from {
      transform: rotate(0deg);
    }
    to {
      transform: rotate(359deg);
    }
  }

  h1 {
    color: #fff;
    font-family: 'Arial Black', sans-serif;
    font-size: 2.5em;
    text-shadow: 0 0 5px #fff, 0 0 10px #fff, 0 0 15px #fff, 0 0 20px #e60073, 0 0 30px #e60073, 0 0 40px #e60073, 0 0 55px #e60073, 0 0 75px #e60073;
  }
</style>
