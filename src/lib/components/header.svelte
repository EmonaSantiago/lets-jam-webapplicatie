<script>
  import { assets } from "$app/paths";
</script>

<section id="header">
  <img src="src/assets/images/logo.png" alt="logo" />

  <section id="button-nav">
    <button class="button"
      ><span><a href="#main-sessions">Aanmelden</a></span></button
    >
    <button class="button"
      ><span><a href="https://fdnd.nl/">FDND.nl</a></span></button
    >
  </section>
</section>

<style>
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
  #header {
    border: #a675f5 solid 2px;
    margin: 2em;
    padding: 1em;
  }

  img {
    width: 25em;
  }

  #button-nav {
    float: right;
  }

  .button-aanmelden {
    border: solid #a675f5 2px;
    border-radius: 3em;
    /* background-color: #050542; */
  }

  .button-fdnd {
    border-radius: 3em;
    background-color: #66e5bf;
    color: #050542;
  }

  @media only screen and (max-width: 800px) {
    * {
      padding: 6px;
    }

    img {
      width: 10em;
    }
  }
</style>
