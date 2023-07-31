<script>
  import samba from "$lib/assets/renders/samba.png";
  import Menu from "$lib/Menu.svelte";
</script>

<section class="hero is-primary is-fullheight is-hero-image">
  <div class="hero-body">
    <div class="">
      <p class="title">Land of Samba and Soccer</p>
      <p class="subtitle">
        the rhythmic heartbeat of Brazil! This tropical paradise, affectionately
        known as the "Carnival Nation," exudes a contagious energy that sweeps
        you off your feet. With its sun-kissed beaches, lush Amazon rainforest,
        and passionate people, "The Marvelous Country" invites you to immerse
        yourself in its colorful fiestas, explore the wild mysteries of nature,
        and experience the warmth of Brazilian hospitality. So come and join the
        party, for Brazil is a vibrant carnival that never ends!
      </p>
    </div>
    <Menu />
    <img src="https:/{samba}" class="render" alt="Samba" draggable="false" />
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
      url("https://github.com/darkerbess/darkerbess.github.io/blob/master/src/lib/assets/called.jpg?raw=true")
        no-repeat center center;
    background-size: cover;
  }
  .hero-body {
    position: relative;
  }
  
  .render {
    position: absolute;
    bottom: 0;
    left: 60%;
    width: 30%;
  }
</style>
