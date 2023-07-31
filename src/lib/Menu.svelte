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
    <li><a class={menu_url('/')} href='{base}/'>Name</a></li>
    <li><a class={menu_url('/capital')} href='{base}/capital'>Capital</a></li>
    <li><a class={menu_url('/coin')} href='{base}/coin'>Coin</a></li>
    <li><a class={menu_url('/religion')} href='{base}/religion'>Religion</a></li>
    <li><a class={menu_url('/called')} href='{base}/called'>Called</a></li>
    <li><a class={menu_url('/economy')} href='{base}/economy'>Economy</a></li>
    <li><a class={menu_url('/touristical-places')} href='{base}/touristical-places'>Touristical Places</a></li>
    <li><a class={menu_url('/typical-food')} href='{base}/typical-food'>Typical Food</a></li>
    <li><a class={menu_url('/dance-folklore')} href='{base}/dance-folklore'>Dance Folklore</a></li>
    <li><a class={menu_url('/activities')} href='{base}/activities'>Activities</a></li>
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
