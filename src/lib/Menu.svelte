<script lang="ts">
  import {page} from '$app/stores';
  import { base } from '$app/paths';
  let url = $page.url.pathname.slice($page.url.pathname.lastIndexOf('/'))
  const menu_url = (name: string) => {
    return url == name ? 'is-active' : '';
  }
</script>

<aside class="menu ml-auto is-size-5">
  <ul class="menu-list">
    <li><a class={menu_url('/')} href='{base}/' target="_blank">Name</a></li>
    <li><a class={menu_url('/capital')} href='{base}/capital' target="_blank">Capital</a></li>
    <li><a class={menu_url('/coin')} href='{base}/coin' target="_blank">Coin</a></li>
    <li><a class={menu_url('/religion')} href='{base}/religion' target="_blank">Religion</a></li>
    <li><a class={menu_url('/called')} href='{base}/called' target="_blank">Called</a></li>
    <li><a class={menu_url('/economy')} href='{base}/economy' target="_blank">Economy</a></li>
    <li><a class={menu_url('/touristical-places')} href='{base}/touristical-places' target="_blank">Touristical Places</a></li>
    <li><a class={menu_url('/typical-food')} href='{base}/typical-food' target="_blank">Typical Food</a></li>
    <li><a class={menu_url('/dance-folklore')} href='{base}/dance-folklore' target="_blank">Dance Folklore</a></li>
    <li><a class={menu_url('/activities')} href='{base}/activities' target="_blank">Activities</a></li>
  </ul>
</aside>

<style lang="scss">
  .menu-list > li > a:hover {
    background-color: #009739;
  }

  .is-active {
    background-color: #fedd00 !important;
    color: #012169 !important;
  }
</style>
