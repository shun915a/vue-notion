<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <a class="navbar-brand" href="/main">Notion Like App</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarText">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link" href="/main"><i class="fas fa-file-alt"></i>ノートリスト</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" data-toggle="dropdown">
            <i class="fas fa-user-graduate"></i>学習用ページ
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="/study/binding">学習1</a></li>
            <li><a class="dropdown-item" href="/study/directive">学習2</a></li>
            <li><a class="dropdown-item" href="/study/event">学習3</a></li>
          </ul>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
}
</script>

<style scoped lang="scss">
</style>

