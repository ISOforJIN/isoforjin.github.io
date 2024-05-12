<svelte:head>
  <title>ゆっくりプロジェクト</title>
  <meta
    name="description"
    content="調布に縁がある人が集まったソフトウェア開発プロジェクトです。興味があるものを自由に開発しています。"
  />

  <!-- Open Graph -->
  <meta property="og:title" content="メンバー" />
  <meta property="og:site_name" content="ゆっくりプロジェクト" />
  <meta property="og:url" content="https://yukkuriproject.github.io" />
  <meta
    property="og:description"
    content="調布に縁がある人が集まったソフトウェア開発プロジェクトです。興味があるものを自由に開発しています。"
  />
  <meta property="og:type" content="website" />
</svelte:head>

<div class="main">
  <div class="explain">
    <p>ゆっくりプロジェクトの公式サイトです。</p>
  </div>

  <h2>ゆっくりプロジェクトとは？</h2>
  <div class="explain">
    <p>調布に縁がある人が集まったソフトウェア開発プロジェクトです。</p>
    <p>興味があるものを自由に開発しています。</p>
  </div>

  <h2>GitHub</h2>
  <div class="explain">
    <a href="https://github.com/YukkuriProject"
      >https://github.com/YukkuriProject</a
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
</style>
