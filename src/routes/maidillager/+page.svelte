<script>
  import { browser } from "$app/environment";
  import Carousel from "svelte-carousel";
</script>

<svelte:head>
  <title>MaidIllager | ゆっくりプロジェクト</title>
  <meta
    name="description"
    content="ゆっくりプロジェクトで開発したMinecraft Mod &quot;MaidIllager&quot;の紹介ページです。"
  />

  <!-- Open Graph -->
  <meta property="og:title" content="MaidIllager" />
  <meta property="og:site_name" content="ゆっくりプロジェクト" />
  <meta
    property="og:url"
    content="https://yukkuriproject.github.io/maidillager"
  />
  <meta
    property="og:description"
    content="ゆっくりプロジェクトで開発したMinecraft Mod &quot;MaidIllager&quot;の紹介ページです。"
  />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="./images/2023-12-07_18.54.02.png" />
  <meta name="twitter:card" content="summary_large_image" />
</svelte:head>

<div class="main">
  <h1>MaidIllager</h1>
  <h2>~邪悪な村人の見た目が若干変わるMod~</h2>
  {#if browser}
    <div id="pictures">
      <Carousel autoplay arrows={false} autoplayDuration={2000}>
        <img alt="2023-12-07_18.54.02" src="./images/2023-12-07_18.54.02.png" />
        <img alt="2023-07-13_19.33.08" src="./images/2023-07-13_19.33.08.png" />
        <img alt="2024-01-01_20.23.24" src="./images/2024-01-01_20.23.24.png" />
        <img
          alt="2023-07-13_19.35.40_2"
          src="./images/2023-07-13_19.35.40_2.png"
        />
        <img alt="2024-01-21_01.08.49" src="./images/2024-01-21_01.08.49.png" />
      </Carousel>
    </div>
  {/if}

  <h2>MaidIllagerとは</h2>
  <div class="explain">
    <p>邪悪な村人の見た目が若干変わるModです。</p>
    <p>
      <a
        href="https://github.com/SistrScarlet/LittleMaidModelLoader-Architectury"
        target="_blank"
        rel="noopener noreferrer">LittleMaidModelLoader-Architectury</a
      >のテクスチャ画像を改変の上使用しています。
    </p>
    <p>
      <a href="https://amitaro.net/" target="_blank" rel="noopener noreferrer"
        >あみたろの声素材工房様</a
      >の音声を使用しています。
    </p>
  </div>

  <h2>注意</h2>
  <div class="explain">
    <p>このModは開発中です。導入は自己責任でお願いします。</p>
    <p>営利目的での利用は禁止です。</p>
  </div>

  <h2>GitHub Wiki</h2>
  <div class="explain">
    <p>ダウンロードはこちらから。</p>
    <p>対応バージョンについてもこちらを確認してください。</p>
  </div>
  <a
    href="https://github.com/YukkuriProject/MaidIllagerForge/wiki"
    class="link-button"
    id="forge"
    target="_blank"
    rel="noopener noreferrer">Forge版</a
  >
  <a
    href="https://github.com/YukkuriProject/MaidIllagerFabric/wiki"
    class="link-button"
    id="fabric"
    target="_blank"
    rel="noopener noreferrer">Fabric版</a
  >
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

  #forge {
    color: rgb(0, 89, 177);
  }

  #fabric {
    color: rgb(217, 87, 0);
  }

  #pictures {
    margin: auto;
    text-align: center;
    width: 700px;
    max-width: 100%;
    min-width: 40%;
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

  h2 {
    margin-top: 0.3em;
    margin-bottom: 0.3em;
  }
</style>
