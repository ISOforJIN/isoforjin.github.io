<svelte:head>
  <title>Whistle Mod | ゆっくりプロジェクト</title>
  <meta
    name="description"
    content="ゆっくりプロジェクトで開発したMinecraft Mod &quot;Whistle Mod&quot;の紹介ページです。"
  />

  <!-- Open Graph -->
  <meta property="og:title" content="Whistle Mod" />
  <meta property="og:site_name" content="ゆっくりプロジェクト" />
  <meta
    property="og:url"
    content="https://yukkuriproject.github.io/whistlemod"
  />
  <meta
    property="og:description"
    content="ゆっくりプロジェクトで開発したMinecraft Mod &quot;Whistle Mod&quot;の紹介ページです。"
  />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="./images/referee_whistle.png" />
  <meta name="twitter:card" content="summary_large_image" />
</svelte:head>

<div>
  <div>
    <h1>Whistle Mod</h1>
    <h2>~あなたが吹いたらみんなを連れ寄せます...~</h2>
    <img alt="referee_whistle" src="./images/referee_whistle.png" />
    <h2>なにこれ</h2>
    <script>
      document.createElement("fewa");
    </script>
    <h2>販売ページ(無料)</h2>
    <br>
    <a href="https://modrinth.com/mod/whistle" class="link-button">Modrinth</a>
    <br>
    <br>
    <h2>Repositories</h2>
    <br>
    <a href="https://github.com/UECYukkuriProject/WhistleMod" class="link-button">Forge</a>
    <a href="https://github.com/UECYukkuriProject/WhistleModFabric" class="link-button">Fabric</a>
    <a href="https://github.com/UECYukkuriProject/WhistleModNeoForge" class="link-button">NeoForge</a>
    <br>
    <br>
    <hr>
    このmodはrensatopcによって作られました。
    <br>
    This mod has created by rensatopc.
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
