<script>
  import coxinha from "$lib/assets/renders/coxinha.png";
  import Menu from "$lib/Menu.svelte";
</script>

<section class="hero is-primary is-fullheight is-hero-image">
  <div class="hero-body">
    <div class="">
      <p class="title">Typical Food</p>
      <p class="subtitle">
        Feijoada<br />
        Coxinha<br />
        Moqueca<br />
        Pao de Queijo<br />
        Brigadeiro<br />
      </p>
    </div>
    <Menu />
    <img
      src="https:/{coxinha}"
      class="render"
      alt="Coxinha"
      draggable="false"
    />
  </div>
</section>

<style lang="scss">
  .title {
    font-size: 7rem;
    font-weight: 900;
    line-height: 0.9;
    opacity: 0.9;
    width: 80%;
  }

  .subtitle {
    width: 50%;
    font-weight: 500;
  }
  .hero-body {
    position: relative;
  }

  .is-hero-image {
    position: relative;
    background: linear-gradient(to top, #fedd00aa, #fedd00aa),
      url("https://github.com/darkerbess/darkerbess.github.io/blob/master/src/lib/assets/feijoada.jpg?raw=true")
        no-repeat center center;
    background-size: cover;
  }
  .hero-body {
    position: relative;
  }
  .render {
    position: absolute;
    bottom: 0;
    left: 30%;
    width: 50%;
  }
</style>
