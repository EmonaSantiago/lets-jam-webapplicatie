<script>
  import { assets } from "$app/paths";
</script>

<section id="header">
  <img src="src/assets/images/logo.png" alt="logo" />

  <section id="button-nav">
    <button class="button-aanmelden">Aanmelden</button>
    <button class= >FDND.nl</button>
  </section>
</section>

<style>
  * {
    padding: 1em;
  }

  #header {
    border: #a675f5 solid 2px;
  }

  img {
    width: 30em;
  }

  #button-nav {
    float: right;
  }

  button {
    color: #a675f5;
    background-color: aqua;
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
