<script>
  import kaka from '$lib/assets/renders/kaka.png'
  import Menu from "$lib/Menu.svelte";
</script>

<section class="hero is-primary is-fullheight is-hero-image">
  <div class="hero-body">
    <div class="">
      <p class="title">Activities</p>
      <p class="subtitle">
        In Brazil, life is a vibrant fiesta of activities! From kicking a soccer
        ball on the sandy beaches to reveling in the pulsating rhythms of
        Carnaval, there's something for everyone. Embrace the thrill of surfing
        massive waves, exploring the enchanting Amazon rainforest, or savoring
        the rich flavors of feijoada in a bustling street market. Join in the
        infectious dance of samba at local clubs or witness the passion of
        capoeira fighters in action. Whether it's cheering at a thrilling
        football match
      </p>
    </div>
    <Menu />
    <img src={kaka} class="render" alt="coffe" draggable="false" />
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
  .is-hero-image {
    position: relative;
    background: linear-gradient(to top, #009739aa, #009739aa),
      url("$lib/assets/activities.jpg") no-repeat center center;
    background-size: cover;
  }
  .render {
    position: absolute;
    bottom: 0;
    left: 50%;
    width: 20%;
  }
</style>
