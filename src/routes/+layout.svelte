<script>
  import { base } from "$app/paths";
  import { page } from "$app/stores";
</script>

<h1>UEC Yukkuri Project</h1>

<nav>
  <a
    href="{base}/"
    aria-current={$page.url.pathname === base + "/"}
    class="nav-element"
  >
    トップ
  </a>
  <a
    href="{base}/products"
    aria-current={$page.url.pathname === base + "/products"}
    class="nav-element"
  >
    作ったもの
  </a>
  <a
    href="{base}/members"
    aria-current={$page.url.pathname === base + "/members"}
    class="nav-element"
  >
    メンバー
  </a>
</nav>

<slot />

<footer>
  <!-- AddToAny BEGIN -->
  <div class="a2a_kit a2a_kit_size_32 a2a_default_style share_buttons">
    <a class="a2a_dd" href="https://www.addtoany.com/share"></a>
    <a class="a2a_button_mastodon"></a>
    <a class="a2a_button_threads"></a>
    <a class="a2a_button_line"></a>
    <a class="a2a_button_facebook"></a>
    <a class="a2a_button_x"></a>
    <a class="a2a_button_copy_link"></a>
  </div>
  <script async src="https://static.addtoany.com/menu/page.js"></script>
  <!-- AddToAny END -->
</footer>

<style>
  @import url(http://fonts.googleapis.com/earlyaccess/notosansjp.css);

  h1 {
    padding-top: 10px;
    background-color: cadetblue;
    color: black;
    -webkit-text-stroke: white 1px;
    text-align: center;
    font-weight: bold;
    font-family: "Noto Sans JP", sans-serif;
  }

  nav {
    padding: 10px;
    background-color: #b9b9b9;
    text-align: center;
    font-family: "Noto Sans JP", sans-serif;
  }

  footer {
    position: absolute;
    bottom: 0;
    width: 100%;
    height: 4em;
    background-color: cadetblue;
  }

  .share_buttons {
    position: absolute;
    margin-top: 0.5em;
    left: 50%;
    transform: translateX(-50%);
  }

  a.nav-element {
    margin: auto 1em auto;
    color: black;
    text-decoration: none;
  }

  a.nav-element[aria-current="true"] {
    border-bottom: 2px solid;
  }
</style>
