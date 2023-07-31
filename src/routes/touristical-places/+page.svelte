<script>
  import palm from '$lib/assets/renders/palmera.png'
  import Menu from "$lib/Menu.svelte";
</script>

<section class="hero is-primary is-fullheight is-hero-image">
  <div class="hero-body">
    <div class="">
      <p class="title">Touristical Places</p>
      <p class="subtitle">
        Brazil is a treasure trove of breathtaking tourist destinations. From
        the iconic Christ the Redeemer statue overlooking Rio de Janeiro's
        sparkling beaches to the awe-inspiring Amazon Rainforest, the world's
        largest tropical rainforest, Brazil offers an abundance of natural
        wonders. Explore the stunning Iguazu Falls, a magnificent collection of
        waterfalls nestled between Brazil and Argentina. Wander through the
        historic streets of Salvador da Bahia, immersing yourself in
        Afro-Brazilian culture and traditions. Discover the vibrant colors and
        festivities of Carnival in Rio de Janeiro or Salvador.
      </p>
    </div>
    <Menu />
    <img src="https:/{palm}" class="render" alt="Palm" draggable="false" />
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
    background: linear-gradient(to top, #009739aa, #009739aa),
      url("https://darkerbess.github.io/_app/immutable/assets/touristical-place.9abba3c9.jpg") no-repeat center center;
    background-size: cover;
  }
  .hero-body {
    position: relative;
  }
  .render {
    position: absolute;
    bottom: 0;
    left: 40%;
    width: 30%;
  }
</style>
