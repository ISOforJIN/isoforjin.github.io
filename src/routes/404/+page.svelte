<script>
  import { base } from "$app/paths";
</script>

<svelte:head>
  <title>ISOJIN</title>
  <meta
    name="description"
    content="調布に縁がある人が集まったソフトウェア開発プロジェクトです。興味があるものを自由に開発しています。"
  />

  <!-- Open Graph -->
  <meta property="og:title" content="ページが見つかりません" />
  <meta property="og:site_name" content="ISOJIN" />
  <meta property="og:url" content="https://yukkuriproject.github.io" />
  <meta
    property="og:description"
    content="調布に縁がある人が集まったソフトウェア開発プロジェクトです。興味があるものを自由に開発しています。"
  />
  <meta property="og:type" content="website" />
</svelte:head>

<div>
  <h1 id="notfound">404</h1>
  <p>ページが見つかりません。</p>
  <p>ページが削除されたか、URLが間違っています。</p>
  <a href="{base}/"> トップ </a>
</div>

<style>
  div {
    color: rgb(0, 50, 100);
    margin: 1em;
    text-align: center;
    font-family: "Noto Sans JP", sans-serif;
  }
  #notfound {
    font-size: 10em;
  }
</style>
