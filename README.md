<style>
  body {
    background-color: black;
  }
  .social-link {
    display: inline-block;
    margin: 0 8px;
    transition: transform 0.3s;
  }

  .social-link:hover {
    transform: scale(1.1);
  }

  .social-link img {
    height: 48px;
    width: 48px;
    background-color: transparent;
  }

  .footer {
    position: fixed;
    bottom: 0;
    left: 0;
    right: 0;
    text-align: center;
    color: white;
    font-size: 12px;
    padding: 8px;
  }

  .fade-in {
    animation: fade-in 0.5s linear;
  }

  @keyframes fade-in {
    from {
      opacity: 0;
    }
    to {
      opacity: 1;
    }
  }

  .dropdown {
    position: relative;
    display: inline-block;
  }

  .dropdown-content {
    display: none;
    position: absolute;
    z-index: 1;
  }

  .dropdown:hover .dropdown-content {
    display: block;
  }
</style>
<div class="fade-in">
  <div class="dropdown">
    <a href="#">Games</a>
    <div class="dropdown-content">
      <a href="#">Game 1</a>
      <a href="#">Game 2</a>
      <a href="#">Game 3</a>
    </div>
  </div>
</div>
<div class="footer fade-in">
  <div class="fade-in">
    <a class="social-link" href="https://steamcommunity.com/id/SuperCringeMan" target="_blank">
      <img src="https://img.icons8.com/color/48/000000/steam.png" alt="Steam">
    </a>
    <a class="social-link" href="https://twitter.com/BRITAINISFAKE" target="_blank">
      <img src="https://img.icons8.com/color/48/000000/twitter.png" alt="Twitter">
    </a>
    <a class="social-link" href="https://open.spotify.com/user/coolmusicboi" target="_blank">
      <img src="https://img.icons8.com/color/48/000000/spotify.png" alt="Spotify">
    </a>
  </div>
  Made With Love By ChatGPT
</div>
