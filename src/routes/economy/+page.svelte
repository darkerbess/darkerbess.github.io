<script>
  import coffe from '$lib/assets/renders/coffe.png'
  import Menu from "$lib/Menu.svelte";
</script>

<section class="hero is-primary is-fullheight is-hero-image">
  <div class="hero-body">
    <div class="">
      <p class="title">Economy</p>
      <p class="subtitle">
        As one of the world's largest economies, it's a major player in Latin
        America. Key industries include agriculture (coffee, soybeans,
        sugarcane), mining (iron ore, bauxite), and manufacturing (automobiles,
        electronics). Brazil is also a top exporter of beef and poultry. Despite
        its potential, the economy faces challenges like income inequality, high
        public debt, and occasional fluctuations due to global commodity prices.
        Nevertheless, Brazil remains a significant economic force with immense
        growth opportunities.
      </p>
    </div>
    <Menu />
    <img src="https:/{coffe}" class="render" alt="coffe" draggable="false" />
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
  
  .render {
    position: absolute;
    bottom: 0;
    left: 60%;
    width: 30%;
  }
  .hero-body {
    position: relative;
  }
  
  .is-hero-image {
    position: relative;
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
