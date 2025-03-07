<script>
  import { base } from "$app/paths";
  import { browser } from "$app/environment";
  import Carousel from "svelte-carousel";
</script>

<svelte:head>
  <title>ISOJIN</title>
  <meta
    name="description"
    content="調布に縁がある人が集まったソフトウェア開発プロジェクトです。興味があるものを自由に開発しています。"
  />

  <!-- Open Graph -->
  <meta property="og:title" content="ISOJIN公式サイトへようこそ" />
  <meta property="og:site_name" content="ISOJIN" />
  <meta property="og:url" content="https://yukkuriproject.github.io" />
  <meta
    property="og:description"
    content="調布に縁がある人が集まったソフトウェア開発プロジェクトです。興味があるものを自由に開発しています。"
  />
  <meta property="og:type" content="website" />
</svelte:head>

<div class="main">
  <div class="explain">
    <p>ISOJINの公式サイトです。</p>
  </div>

  {#if browser}
    <div class="pictures">
      <Carousel
        autoplay
        autoplayDuration={2000}
        autoplayProgressVisible
        pauseOnFocus
      >
        <a class="pictures" href="{base}/kendomod"
          ><img
            class="pictures"
            alt="2024-11-03_20.19.09"
            src="./images/2024-11-03_20.19.09.png"
          /></a
        >
        <a class="pictures" href="{base}/maidillager"
          ><img
            class="pictures"
            alt="2024-01-21_01.08.49"
            src="./images/2024-01-21_01.08.49.png"
          /></a
        >
        <a class="pictures" href="{base}/whistlemod"
          ><img
            class="pictures"
            alt="referee_whistle_resized"
            src="./images/referee_whistle_resized.png"
          /></a
        >
      </Carousel>
    </div>
  {/if}

  <h2>ISOJINとは？</h2>
  <div class="explain">
    <p>調布に縁がある人が集まったソフトウェア開発プロジェクトです。</p>
    <p>興味があるものを自由に開発しています。</p>
  </div>

  <a
    href="https://github.com/YukkuriProject"
    class="link-button"
    id="kendo"
    target="_blank"
    rel="noopener noreferrer">GitHub</a
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

  .link-button {
    margin: auto 2em auto;
    padding: 0.1em;
    font-size: 2em;
    border: solid;
    border-radius: 0.3em;
    text-align: center;
    text-decoration: none;
    font-family: "Noto Sans JP", sans-serif;
    color: rgb(17, 17, 117);
  }

  .pictures {
    margin: auto;
    text-align: center;
    width: 700px;
    max-width: 100%;
    min-width: 40%;
  }
</style>
