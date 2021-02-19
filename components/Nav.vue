<template>
  <div>
    <b-navbar toggleable="lg" type="dark" style="background-color: #93aa7e;">
      <b-navbar-brand href="/">
        Home
      </b-navbar-brand>
      <b-navbar-nav><!--薄いナビゲーションバー(カーソルでホップするよ)-->
        <b-nav-item href="#">Profile</b-nav-item>
        <b-nav-item href="#">Skills</b-nav-item>
        <b-nav-item href="#">Hobby</b-nav-item>
        <b-nav-item href="https://jp.vuejs.org/v2/guide/index.html" target="_blank" rel="noopener noreferrer">Vue.js</b-nav-item>
        <b-nav-item href="https://ja.nuxtjs.org/" target="_blank" rel="noopener noreferrer">Nuxt.js</b-nav-item>
      </b-navbar-nav>


      <b-navbar-nav class="ml-auto">
        <b-navbar-brand href="https://github.com/You-saku" target="_blank" rel="noopener noreferrer">
          <img src="@/assets/GitHub-Mark-Light-32px.png">GitHub
        </b-navbar-brand>
      </b-navbar-nav>

    </b-navbar>
  </div>
</template>
<style scoped>
  img{
    padding: 3px;
  }
</style>
