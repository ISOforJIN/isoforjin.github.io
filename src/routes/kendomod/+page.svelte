<svelte:head>
  <title>剣道Mod | ISOJIN</title>
  <meta
    name="description"
    content="ISOJINで開発したMinecraft Mod &quot;MaidIllager&quot;の紹介ページです。"
  />

  <!-- Open Graph -->
  <meta property="og:title" content="剣道Mod" />
  <meta property="og:site_name" content="ISOJIN" />
  <meta
    property="og:url"
    content="https://yukkuriproject.github.io/maidillager"
  />
  <meta
    property="og:description"
    content="ISOJINで開発したMinecraft Mod &quot;剣道Mod&quot;の紹介ページです。"
  />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="./images/2024-11-03_20.19.09.png" />
  <meta name="twitter:card" content="summary_large_image" />
</svelte:head>

<div class="main">
  <h1>剣道Mod(開発中)</h1>
  <h2>~Minecraftで剣道ができるMod~</h2>
  <img alt="2024-11-03_20.19.09" src="./images/2024-11-03_20.19.09.png" />

  <h2>剣道Modとは</h2>
  <div class="explain">
    <p>Minecraftの世界に剣道を導入するModです。</p>
  </div>
  <div class="link">
    <a
      href="https://github.com/ISOforJIN/kendo-mod"
      class="link-button"
      id="kendo"
      target="_blank"
      rel="noopener noreferrer">GitHub</a
    >
  </div>
  <div class="link">
    <a
      href="https://github.com/ISOforJIN/kendo-mod-multiloader"
      class="link-button"
      id="kendo-multiloader"
      target="_blank"
      rel="noopener noreferrer">GitHub(Multiloader)</a
    >
  </div>
</div>

<style>
  div.main {
    margin-top: 0.5em;
    margin-bottom: 1.5em;
    text-align: center;
    font-family: "Noto Sans JP", sans-serif;
    color: rgb(0, 50, 100);
  }

  div.explain {
    margin-bottom: 1em;
  }

  #kendo,
  #kendo-multiloader {
    color: rgb(17, 17, 117);
  }

  img {
    width: 700px;
    max-width: 100%;
    min-width: 40%;
  }

  .link-button {
    margin: auto 2em auto;
    padding: 0.1em;
    font-size: 2em;
    border: solid;
    border-radius: 0.3em;
    text-align: center;
    text-decoration: none;
    font-family: "Noto Sans JP", sans-serif;
  }

  .link {
    margin-top: 1.25em;
  }

  h2 {
    margin-top: 0.3em;
    margin-bottom: 0.3em;
  }
</style>
