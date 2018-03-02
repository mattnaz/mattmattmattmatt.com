<template>
  <section class="matt-container">
    <div class="matt">
      <div class="fa-10x fade-in">
        <span class="fa-layers fa-fw">
          <i class="fas fa-bolt" style="color:rgba(0, 0, 0, 0.2); top: 10px; left: 10px;"></i>
          <i class="fa-inverse fas fa-bolt" data-fa-transform=""></i>
        </span>
      </div>
      <br>
      <br>
      <p class="fade-in-two">
        <a href="http://swingandadrive.com" target="_blank">Swing and a drive!</a>
      </p>
    </div>
  </section>
</template>


<style>
  body {
      background: #ff9966;
      /* fallback for old browsers */
      background: -webkit-linear-gradient(135deg, #ff5e62, #ff9966);
      /* Chrome 10-25, Safari 5.1-6 */
      background: linear-gradient(135deg, #ff5e62, #ff9966);
      /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
      overflow: auto;
      color: rgba(0, 0, 0, 0.7);
      font-family: 'Nunito', sans-serif;
  }

  .matt-container {
      display: flex;
      align-items: center;
      text-align: center;
      height: 100vh;
      width: 100%;
  }

  .matt {
      margin: 0 auto;
  }

  p {
      display: block;
      font-size: 1.5rem;
      line-height: 2rem;
  }

  h1 {
      letter-spacing: 0.25rem;
      font-family: 'Nunito', cursive;
      font-weight: 900;
      color: white;
      display: block;
      width: 100%;
      text-shadow: rgba(0, 0, 0, 0.2) 4px 4px 0px;
      font-size: 5rem;
  }

  a {
      border-bottom: 2px solid #f4f8b4c2;
      color: inherit;
      transition: box-shadow .15s cubic-bezier(.33, .66, .66, 1);
      font-weight: 700;
      text-decoration: none;
  }

  a:hover {
      box-shadow: inset 0 -15px 0 #f4f8b4c2;
      color: inherit;
  }

  .fa-bolt {
      text-shadow: 3px 3px black;
  }

  @keyframes fadeIn {
      from {
      opacity: 0;
      top: -50px;
      }
      to {
      opacity: 1;
      top: 0px;
      }
  }

  .fade-in {
      top: -50px;
      opacity: 0;
      animation: fadeIn ease-in-out 1;
      animation-fill-mode: forwards;
      animation-duration: 1s;
      animation-delay: .5s;
      position: relative;
  }

  .fade-in-two {
      top: -50px;
      opacity: 0;
      animation: fadeIn ease-in-out 1;
      animation-fill-mode: forwards;
      animation-duration: 1s;
      animation-delay: .7s;
      position: relative;
  }
</style>
