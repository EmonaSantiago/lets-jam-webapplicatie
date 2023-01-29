<section id="Navigation">
  <button class="button"
    ><span><a href="#sessions">WE ❤ WEB sessions</a></span></button
  >
  <button class="button"
    ><span><a href="#upcoming">Upcoming sessions</a></span></button
  >
  <button class="button"><span><a href="#Footer">Links</a></span></button>
  <button class="button"
    ><span><a href="#main-sessions">Aanmelden</a></span></button
  >
</section>

<style>
  * {
    color: white;
  }

  /* .button {
    background-color: #050542;
    border: solid hsl(162, 71%, 65%) 1px;
    border-radius: 2rem;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
  } */
  #Navigation {
    gap: 10em;
    margin: 2em;
    margin-bottom: 5em;
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
