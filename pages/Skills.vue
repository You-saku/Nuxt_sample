<template>
<div id="main">
  <Header />
  <Nav />
  <h1>スキルセット</h1>
  <div id="skills">
  <h2>プログラミング(初級レベル)</h2>
  <ol>
    <li v-for="code in codingskills" :key="code">
      {{code.item}}<br>
      <img :src = code.src />
    </li>
  </ol>
  <h2>語学</h2>
  <ol>
    <li v-for = "l in languages" :key="l">
      {{l.item}}
    </li>
  </ol>
  <h2>その他</h2>
  <ol>
    <li v-for = "other in others" :key="other">
      {{other.item}}
    </li>
  </ol>
  </div>
  <Footer />
</div>
</template>

<style scoped>


  #main{
    text-align: center;
    min-width: 100vh;
  }

  li {
    list-style: none;
    padding-right: 40px;
    padding-bottom: 15px;
  }

</style>

<script>
export default {
  data(){
    return{
      codingskills: [
        {id: 1, item: "C++", src: require('~/assets/skills/cpp.png')},
        {id: 2, item: "Python",src: require('~/assets/skills/python.png')},
        {id: 3, item: "JavaScript",src: require('~/assets/skills/js.png')},
        {id: 4, item: "PHP", src: require('~/assets/skills/php.png')}
      ],

      languages: [
        {id: 1, item: "日本語"},
        {id: 2, item: "English(L&R&S)"}
      ],

      others: [
        {id: 1, item: "ライティングスキル"},
        {id: 2, item: "ロジカルシンキング"},
        {id: 3, item: "コンピュータサイエンス基礎"},
        {id: 4, item: "剣道弐段"},
        {id: 5, item: "地道な努力"}
      ]
    };
  }
}
</script>
