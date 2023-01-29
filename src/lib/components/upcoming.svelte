<section id="upcomings">
  <!-- upcoming we love web sessies -->
  <section class="upcoming">
    <div class="slider">
      <h1>Upcoming We Love Web Sessies</h1>
      <div class="slides">
        <div id="slide-1">
          <!-- svelte-ignore a11y-missing-attribute -->
          <img
            src="src/assets/images/Schermafbeelding 2023-01-26 om 22.45.56.png"
            width="300em"
          />
        </div>
        <div id="slide-2">
          <img
            src="src/assets/images/Schermafbeelding 2023-01-26 om 22.45.56.png"
            width="300em"
          />
        </div>
        <div id="slide-3">
          <img
            src="src/assets/images/Schermafbeelding 2023-01-26 om 22.45.56.png"
            width="300em"
          />
        </div>
        <div id="slide-4">
          <img
            src="src/assets/images/Schermafbeelding 2023-01-26 om 22.45.56.png"
            width="300em"
          />
        </div>
        <div id="slide-5">
          <img
            src="src/assets/images/Schermafbeelding 2023-01-26 om 22.45.56.png"
            width="300em"
          />
        </div>
      </div>
    </div>
  </section>
</section>

<style>
  /* upcoming  */

  #upcomings {
    border: #66e5bf solid 2px;
    margin: 2em;
  }

  .slider h1 {
    font-size: 3em;
    padding-bottom: 3em;
    padding-top: 2em;
  }

  .upcoming {
    background-color: #050542;
    padding-bottom: 6em;
  }

  .slider {
    border-top: #a675f5;
    border-top-style: solid;
    padding-right: 0;
    width: 100%;
    text-align: center;
    overflow: hidden;
    padding-top: 6em;
  }

  /* image slider */

  .slides img {
    border-radius: 1em;
  }
  #slide-1:hover img {
    opacity: 0.3;
  }

  #slide-2:hover img {
    opacity: 0.3;
  }

  #slide-3:hover img {
    opacity: 0.3;
  }

  #slide-4:hover img {
    opacity: 0.3;
  }

  #slide-5:hover img {
    opacity: 0.3;
  }

  .slides:hover #slide-1 {
    opacity: 1;
  }

  .slides {
    display: flex;
    overflow-x: auto;
    scroll-snap-type: x mandatory;
    scroll-behavior: smooth;
    -webkit-overflow-scrolling: touch;
  }

  .slides::-webkit-scrollbar {
    width: 10px;
    height: 10px;
  }
  .slides::-webkit-scrollbar-thumb {
    background: #66e5bf;
    border-radius: 10px;
  }
  .slides::-webkit-scrollbar-track {
    background: transparent;
  }
  .slides > div {
    scroll-snap-align: start;
    flex-shrink: 0;
    width: 300px;
    height: 300px;
    margin-right: 120px;
    border-radius: 10px;
    background: #f1adee;
    transform-origin: center center;
    transform: scale(1);
    transition: transform 0.5s;
    position: relative;

    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 100px;
  }

  .author-info {
    background: rgba(0, 0, 0, 0.75);
    color: white;
    padding: 0.75rem;
    text-align: center;
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    margin: 0;
  }
  .author-info a {
    color: white;
  }

  .slider > a {
    display: inline-flex;
    width: 100%;
    height: 1.5rem;
    background: white;
    text-decoration: none;
    align-items: center;
    justify-content: center;
    border-radius: 50%;
    margin: 0 0 0.5rem 0;
    position: relative;
    padding-right: 0;
  }
  .slider > a:active {
    top: 1px;
  }
  .slider > a:focus {
    background: #050542;
  }
</style>
