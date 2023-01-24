<script>
  import { assets } from "$app/paths";
</script>

<section id="header">
  <img src="src/assets/images/logo.png" alt="logo" />

  <section id="button-nav">
    <button class="button-aanmelden">Aanmelden</button>
    <button class="button-fdnd">FDND.nl</button>
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
    width: 25em;
  }

  #button-nav {
    float: right;
  }

  button {
    color: #a675f5;
    padding: 20px;
    margin-top: 1em;
  }

  .button-aanmelden {
    border: solid #a675f5 2px;
    border-radius: 3em;
    background-color: #050542;
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
