<template>
  <div id="main">
    <Header />
    <Nav />

    <h1>Nuxt.js入門</h1>
    <p>Vue.jsを触る傍らでNuxt.jsに興味を持ったのでこの際、何か作ってみようと思い、おなじみのプロフィールページを書いてみる</p>
    ナビゲーションバーにコンテンツを並べたのでご覧ください
    <div id="icon">
      <img src="@/assets/vue-js.png">
    </div>

    <Footer />
  </div>
</template>

<style scoped>
  #main{
    text-align: center;
  }

  h1{
    text-align: center;
    padding: 5px
  }

  h2, p{
    text-align: center;
  }

  #icon{
    text-align: center;
  }
</style>
