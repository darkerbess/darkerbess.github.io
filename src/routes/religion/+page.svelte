<script>
  import cristo from '$lib/assets/renders/cristo.png'
  import Menu from "$lib/Menu.svelte";
</script>

<section class="hero is-primary is-fullheight is-hero-image">
  <div class="hero-body">
    <div class="">
      <p class="title">Faith in Brazil</p>
      <p class="subtitle">
        Welcome to the spiritual mosaic of Brazil, where faith dances in a
        kaleidoscope of beliefs! From the rhythmic beats of Candomblé's ancient
        rituals to the solemn beauty of Catholic processions, Brazil's religious
        tapestry weaves together a vibrant symphony of traditions. Embracing
        Afro-Brazilian religions, indigenous practices, and a strong Catholic
        heritage, this colorful fusion of faith creates a harmonious melody that
        resonates deep within the soul of this diverse and captivating nation.
        In Brazil, the sacred and the celebratory blend in a breathtaking dance
        of devotion, reflecting the unity in diversity that defines this land of
        wonder and enchantment.
      </p>
    </div>
    <Menu />
    <img src="https:/{cristo}" class="render" alt="Pelé" draggable="false" />
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
  .hero-body {
    position: relative;
  }
  
  .is-hero-image {
    position: relative;
    background: linear-gradient(to top, #009739aa, #009739aa),
      url("https://darkerbess.github.io/_app/immutable/assets/religion.fe04516b.jpg") no-repeat top center;
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
