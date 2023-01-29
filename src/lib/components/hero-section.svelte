<section id="Hero-section">
  <img src="src/assets/images/headimage.png" alt="we love web pic" />
  <!-- <h1>WE ❤ WEB</h1> -->
  <div id="BrushCursor">
    <div class="container">
      <div class="p p1">WE LOVE WEB</div>
      <div class="p p2">WE LOVE WEB</div>
      <div class="p p3">
        WE LOVE WEB
        <div class="cursor" />
      </div>
    </div>
  </div>
  <button class="button"
    ><span><a href="#Navigation">Kom een sessie volgen!</a> </span></button
  >
</section>

<style>
  img {
    width: 100%;
    height: auto;
  }

  #Hero-section {
    height: fit-content;
    text-align: center;
    border-radius: 2em;
    position: relative;
    color: white;
    margin: 2em;
  }

  #BrushCursor {
    position: absolute;
    top: 20%;
    left: 23%;
    transform: translate(-50%, -50%);
  }

  .container {
    height: 100%;
    width: 100%;
  }

  .p {
    position: absolute;
    font-size: 2rem;
    font-family: sans-serif;
    font-weight: bold;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    white-space: nowrap;
  }

  @media only screen and (min-width: 500px) {
    .p {
      font-size: 3rem;
    }
  }

  @media only screen and (min-width: 700px) {
    .p {
      font-size: 5rem;
    }
  }

  .p1 {
    text-shadow: 1px 1px 1px black, -1px -1px 1px black;
    color: #a675f5;
  }

  .p2 {
    color: #66e5bf;
    clip-path: polygon(0 0, 100% 0, 100% 100%, 0% 100%);
    animation: text-animation 3s ease-in-out forwards alternate infinite;
    text-shadow: 1px 1px 1px black, 10px 2px 2px black;
  }

  .p3 {
    height: 20%;
    color: transparent;
  }

  @keyframes text-animation {
    from {
      clip-path: polygon(0 0, 100% 0, 100% 100%, 0% 100%);
    }
    to {
      clip-path: polygon(0 0, 0% 1%, 0% 100%, 0% 100%);
    }
  }

  .cursor {
    position: absolute;
    top: 50%;
    height: 100%;
    width: 100%;
    transform: translate(0, -50%);
    animation: cursor-animation 3s ease-in-out forwards alternate infinite;
  }

  @keyframes cursor-animation {
    from {
      width: 100%;
    }
    to {
      width: 0;
    }
  }

  .button {
    position: absolute;
    top: 35%;
    left: 13%;
    transform: translate(-50%, -50%);
  }

  a {
    color: white;
  }

  .button {
    border-radius: 2em;
    background-color: #050542;
    border: solid 2px #a675f5;
    color: white;
    text-align: center;
    font-size: 18px;
    padding: 20px;
    width: fit-content;
    transition: all 0.5s;
    cursor: pointer;
    margin: 5px;
  }

  .button span {
    cursor: pointer;
    display: inline-block;
    position: relative;
    transition: 0.5s;
  }

  .button span:after {
    content: "\00bb";
    position: absolute;
    opacity: 0;
    top: 0;
    right: -20px;
    transition: 0.5s;
  }

  .button:hover span {
    padding-right: 25px;
  }

  .button:hover span:after {
    opacity: 1;
    right: 0;
  }
</style>
