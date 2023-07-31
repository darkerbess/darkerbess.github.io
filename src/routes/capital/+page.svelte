<script>
  import pele_render from "$lib/assets/renders/pele.png"
  import Menu from "$lib/Menu.svelte";
</script>

<section class="hero is-primary is-fullheight is-hero-image">
  <div class="hero-body">
    <div class="">
      <p class="title">Brasilia</p>
      <p class="subtitle">
        Welcome to Brasília, the futuristic capital of Brazil! Designed like a
        soaring bird in flight, this architectural marvel showcases a perfect
        harmony between modernity and nature. As a purpose-built city, Brasília
        stands as a testament to human ingenuity, rising from the lush landscape
        of Brazil to become a symbol of progress and unity for the nation.
        Explore its unique layout and iconic landmarks, and you'll discover a
        city where innovation and tradition coexist in captivating splendor.
      </p>
    </div>
    <Menu />
    <img src="https:/{pele_render}" class="render" alt="Pelé" draggable="false" />
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
    background: linear-gradient(to top, #FEDD00aa, #FEDD00aa),
      url("https://darkerbess.github.io/_app/immutable/assets/capital.bb99ce17.jpg") no-repeat top center;
    background-size: cover;
  }
  .render {
    position: absolute;
    bottom: 0;
    left: 40%;
    width: 30%;
  }
</style>
