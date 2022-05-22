<script lang="ts">
  import logo from './assets/svelte.png'
  import Counter from './lib/Counter.svelte'
</script>

<main>
  <div class="container">
    <div class="row max-w-sm mx-auto">
      <div class="col-xs-12 col-sm-10 col-md-8 col-lg-6">
        <h1 class="text-rose-900 text-3xl font-roobert ">Checking if the font is working.</h1>
        <h4>Headers</h4>
        <p>A site can define styles for headers</p>
        <h1>First Header</h1>
        <h2>Second Header</h2>
        <h3>Third Header</h3>
        <h4>Fourth Header</h4>
        <h5>Fifth Header</h5>

        <strong>Checking if the font is working.</strong>

      </div>
      <div class="col-xs-12 col-md-4 col-lg-6">
        <h2>Checking if the font is working.</h2>
        <em>Checking if the font is working.</em>
      </div>
    </div>
  </div>
</main>

<style>
  /* Base Styles and variables */
  :root {
    --mint: #E3F7F1;
    --teal: #005866;
    --text: #1f1111;
    --gray: #D9D8D6;
    --light: #E5E5E5;
    --off: #FAFAFA;
    --vibrant: #6ED7B7;
    --yellow: #FFDD00;
  }

  html {
    scroll-behavior: smooth;

  }

  body {
    line-height: 1.6;
    color: var(--text);
    font-family: 'Roobert TRIAL', sans-serif;
  }


  /* Feel free to add or remove as needed */
  /* @media screen and (max-width:1199px) {}

  @media screen and (max-width:991px) {}

  @media screen and (max-width:767px) {}

  @media screen and (max-width:575px) {}

  @media screen and (max-width:420px) {} */
</style>
