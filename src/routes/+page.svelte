<script>
  import Menu from "$lib/Menu.svelte";
</script>

<section class="hero is-primary is-fullheight is-hero-image">
  <div class="hero-body">
    <div class="">
      <p
        class="m-subtitle subtitle is-3 mb-4 is-uppercase has-text-weight-bold"
      >
        Vibrant Brazil:
      </p>
      <p class="title is-size-1-mobile is-uppercase">
        Welcome<br />Paradise Awaits!
      </p>
      <p class="subtitle mt-3">
        Explore the Rich Culture, Stunning Nature, and Exotic Delights.
      </p>

      <button
        class="button is-large is-responsive is-rounded px-6 has-text-white"
        >Explore</button
      >
    </div>
    <Menu />
    <img src="https://darkerbess.github.io/_app/immutable/assets/neymar1.a5bdc749.png" class="render" alt="Neymar" draggable="false" />
  </div>
</section>

<style lang="scss">
  .title {
    font-size: 8rem;
    font-weight: 900;
    line-height: 0.9;
    opacity: 0.9;
    width: 80%;
  }

  .m-subtitle {
    opacity: 0.7;
  }

  .subtitle {
    width: 40%;
    font-weight: 500;
  }

  .button {
    background-color: rgba(255, 255, 255, 0.4);
    border: none;
  }

  .hero-body {
    position: relative;
  }

  .is-hero-image {
    position: relative;
    background: linear-gradient(to top, #009739aa, #009739aa),
      url("https://darkerbess.github.io/_app/immutable/assets/wallpaper_flag.31a3b8ab.jpg") no-repeat center center;
    background-size: cover;
  }
  .render {
    position: absolute;
    bottom: 0;
    left: 40%;
    width: 20%;
  }
</style>
