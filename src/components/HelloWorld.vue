<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h1>GitHub Page Here</h1>
    <h1>pert1 - 3</h1>
    <ul>
      <li>
        <h1>リポジトリ管理者</h1>
        <h1>Part1 Vue.-cli でプロジェクトを作成し、そのプロジェクトを GitHub に Push するまでの方法</h1>
        <p>ローカルにプロジェクトを作成する。</p>
        <p>GitHub Pageに公開する設定をする。</p>
        <p>GitHub リポジトリの作成</p>
        <p>プロジェクトを GitHub に Push する</p>
        <h1>Part2 現在のブランチから派生ブランチを作成してGitHubへPushする。</h1>
        <h1>開発者</h1>
        <h1>Part3 cloneを作成して派生ブランチを作成してGitHubへPushする。</h1>
        <p>GitHubリポジトリをcloneしてローカルプロジェクト作る</p>
        <p>ローカルプロジェクトをGitHubへpushする。</p>
        <h1>Part4 localでいままで作業していたbranchを削除する</h1>
        <h1>Part5 masterに他の人が追加した分を自分のところに取り込みます。</h1>
      </li>
    </ul>
    <p>
      For a guide and recipes on how to configure / customize this project,<br>
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    <h3>Installed CLI Plugins</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
    </ul>
    <h3>Essential Links</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
    <h3>Ecosystem</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
