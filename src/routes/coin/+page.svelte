<script>
  import real from "$lib/assets/renders/real.png";
  import Menu from "$lib/Menu.svelte";
</script>

<section class="hero is-primary is-fullheight is-hero-image">
  <div class="hero-body">
    <div class="">
      <p class="title">Real</p>
      <p class="subtitle">
        Step into the vibrant world of Brazil's currency, the Real! Like a
        colorful carnival dance, the Real flaunts a kaleidoscope of hues on its
        banknotes, reflecting the nation's rich diversity and natural beauty.
        From the striking animals depicted on the bills to the captivating
        landmarks gracing the coins, each piece of the Real tells a mesmerizing
        story of Brazil's captivating culture and lively spirit. Embrace the
        rhythm of the Real and let it whisk you away on a thrilling journey
        through the heart of this enchanting South American nation.
      </p>
    </div>
    <Menu />
    <img src="https:/{real}" class="render" alt="Pelé" draggable="false" />
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
    position: relative !important;
  }
  
  .is-hero-image {
    position: relative;
    background: linear-gradient(to top, #012169aa, #012169aa),
      url("https://darkerbess.github.io/_app/immutable/assets/coin.fdf8dc6f.jpg") no-repeat top center;
    background-size: cover;
  }
  
  .render {
    position: absolute !important;
    bottom: 0 !important;
    left: 50% !important;
    width: 30% !important;
  }
  
</style>
