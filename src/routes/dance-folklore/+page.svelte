<script>
  import capoeria from '$lib/assets/renders/capoeira.png'
  import Menu from "$lib/Menu.svelte";
</script>

<section class="hero is-primary is-fullheight is-hero-image">
  <div class="hero-body">
    <div class="">
      <p class="title">Dance Folklore</p>
      <p class="subtitle">
        Brazil's dance scene is a mesmerizing carnival of rhythms and colors!
        From the sensual moves of Samba, swaying hips in perfect harmony with
        the beats of drums, to the electrifying energy of Forró
      </p>
    </div>
    <Menu />
    <img src="https:/{capoeria}" class="render" alt="Capoeira" draggable="false" />
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

  .subtitle {
    width: 50%;
    font-weight: 500;
  }
  .is-hero-image {
    position: relative;
    background: linear-gradient(to top, #012169aa, #012169aa),
      url("https://darkerbess.github.io/_app/immutable/assets/samba.04abd987.jpg") no-repeat center center;
    background-size: cover;
  }
  .render {
    position: absolute;
    bottom: 0;
    left: 50%;
    width: 30%;
  }
  .hero-body {
    position: relative;
  }
</style>
