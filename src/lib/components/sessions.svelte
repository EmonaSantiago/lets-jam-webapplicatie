<section id="sessions">
  <div id="BrushCursor">
    <div class="p p1">WE LOVE WEB SESSIES</div>
    <div class="p p2">WE LOVE WEB SESSIES</div>
    <div class="p p3">
      WE LOVE WEB SESSIES
      <div class="cursor" />
    </div>
  </div>
  <div class="grid-container">
    <div class="container">
      <h2>We web Navigeren op het web & de kracht van Css</h2>
      <h3>Cyd Stumpel</h3>
      <p>
        2022-06-21T14:51:22.000Z <br />
        Een talk over de kracht van CSS gegeven door oud student cmd Cyd Stumpel!<br
        />
        www.fdnd.nl<br />
      </p>
    </div>

    <div class="container">
      <h2>We web Navigeren op het web & de kracht van Css</h2>
      <h3>Cyd Stumpel</h3>
      <p>
        2022-06-21T14:51:22.000Z <br />
        Een talk over de kracht van CSS gegeven door oud student cmd Cyd Stumpel!<br
        />
        www.fdnd.nl<br />
      </p>
    </div>

    <div class="container">
      <h2>We web Navigeren op het web & de kracht van Css</h2>
      <h3>Cyd Stumpel</h3>
      <p>
        2022-06-21T14:51:22.000Z <br />
        Een talk over de kracht van CSS gegeven door oud student cmd Cyd Stumpel!<br
        />
        www.fdnd.nl<br />
      </p>
    </div>

    <div class="container">
      <h2>We web Navigeren op het web & de kracht van Css</h2>
      <h3>Cyd Stumpel</h3>
      <p>
        2022-06-21T14:51:22.000Z <br />
        Een talk over de kracht van CSS gegeven door oud student cmd Cyd Stumpel!<br
        />
        www.fdnd.nl<br />
      </p>
    </div>
    <div class="container">
      <h2>We web Navigeren op het web & de kracht van Css</h2>
      <h3>Cyd Stumpel</h3>
      <p>
        2022-06-21T14:51:22.000Z <br />
        Een talk over de kracht van CSS gegeven door oud student cmd Cyd Stumpel!<br
        />
        www.fdnd.nl<br />
      </p>
    </div>
  </div>
</section>

<style>
  .p {
    position: absolute;
    font-size: 25px;
    font-family: sans-serif;
    font-weight: bold;
    white-space: nowrap;
    text-align: center;
  }

  @media only screen and (min-width: 500px) {
    .p {
      font-size: 25px;
    }
  }

  @media only screen and (min-width: 700px) {
    .p {
      font-size: 25px;
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
  .title {
    text-align: center;
    position: sticky;
    top: 0;
  }
  .grid-container {
    display: grid;
    column-gap: 30px;
    grid-template-columns: auto auto;
    padding: 5em;
  }

  #sessions {
    border: 2px solid #66e5bf;
    border-radius: 2em;
    height: 40em;
    overflow-x: hidden;
    padding: 2em;
    margin: 2em;
  }
  .container {
    width: fit-content;
    height: fit-content;
    border: solid 6px #a675f5;
    border-radius: 2em;
    margin: 2em;
    padding: 1em;
  }
</style>
