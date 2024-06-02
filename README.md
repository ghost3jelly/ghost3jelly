<h1 align="center">
  Hello, I'm Your Name
</h1>

<h3 align="center">
  I'm a <span class="typing"></span>
</h3>

<div align="center">
  <img class="rotate" src="https://avatars.githubusercontent.com/u/ghost3jelly" width="200" height="200" alt="Profile Picture">
</div>

<p align="center">
  A brief introduction about yourself goes here.
</p>

<p align="center">
  <a href="https://twitter.com/your-twitter-handle">Twitter</a> •
  <a href="https://www.linkedin.com/in/your-linkedin-profile">LinkedIn</a> •
  <a href="https://your-website.com">Website</a>
</p>

<style>
  .typing {
    animation: typing 2s steps(20, end), blink-caret .75s step-end infinite;
    white-space: nowrap;
    overflow: hidden;
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

  .rotate {
    animation: rotation 2s infinite linear;
  }

  @keyframes rotation {
    from {
      transform: rotate(0deg);
    }
    to {
      transform: rotate(359deg);
    }
  }
</style>
