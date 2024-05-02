<svelte:head>
  <title>作ったもの | UECゆっくりプロジェクト</title>
  <meta
    name="description"
    content="UECゆっくりプロジェクトで開発したソフトウェアの紹介ページです。MinecraftのMODを主に作っています。"
  />

  <!-- Open Graph -->
  <meta property="og:title" content="作ったもの" />
  <meta property="og:site_name" content="UECゆっくりプロジェクト" />
  <meta
    property="og:url"
    content="https://uecyukkuriproject.github.io/products"
  />
  <meta
    property="og:description"
    content="UECゆっくりプロジェクトで開発したソフトウェアの紹介ページです。MinecraftのMODを主に作っています。"
  />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="./images/referee_whistle.png" />
  <meta name="twitter:card" content="summary_large_image" />
</svelte:head>

<div>
  <div>
    <h1>Whistle Mod</h1>
    <img alt="referee_whistle" src="./images/referee_whistle.png" /><br />
    <a href="https://modrinth.com/mod/whistle" class="link-button">modrinth</a>
  </div>
</div>

<style>
  div {
    color: rgb(0, 50, 100);
    margin-top: 0.5em;
    margin-bottom: 1.5em;
    text-align: center;
    font-family: "Noto Sans JP", sans-serif;
  }

  img {
    width: 700px;
    max-width: 100%;
    min-width: 40%;
  }

  .link-button {
    margin: auto 2em auto;
    padding: 0.1em;
    color: rgb(0, 50, 100);
    font-size: 2em;
    border: solid;
    border-radius: 0.3em;
    text-align: center;
    text-decoration: none;
    font-family: "Noto Sans JP", sans-serif;
  }
</style>
