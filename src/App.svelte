<script>
  import croppedImg from './assets/crop.jpg'
  import bigImg from '/big.jpg'
  import uddImg from './assets/udd.jpg'
</script>

<main>
    <div class="body">

      <!-- <a href="" target="_blank" rel="noreferrer">
        <img src={bigImg} class="logo" alt="Vite Logo" />
      </a>
      <a href="" target="_blank" rel="noreferrer">
        <img src={uddImg} class="logo svelte" alt="Svelte Logo" />
      </a> -->
      <h1>ELSA BINDER</h1>
      <h2>KOMMER SNART</h2>
      <p>binder.elsa@gmail.com</p>
    </div>
</main>

<style>
  .logo {
    height: 20em;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }
  .body{
    background-color: aliceblue;
    padding: 20rem;
    background: url('./assets/crop.jpg'); /* Update this path */
    background-size: cover; /* Optional: Adjusts the size of the background image */
    background-position: center; /* Optional: Centers the background image */
  }
</style>
