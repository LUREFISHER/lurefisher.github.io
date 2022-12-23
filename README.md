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

  .dropdown a {
    color: white;
    font-size: 20px;
  }

  .games-animation {
    animation: games-animation 0.5s linear;
  }

  @keyframes games-animation {
    from {
      transform: translate(0, 0);
    }
    to {
      transform: translate(50px, 0);
    }
  }
</style>
<div class="fade-in">
  <div class="dropdown">
