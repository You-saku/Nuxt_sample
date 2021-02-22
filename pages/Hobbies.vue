<template>
<div id="main">
  <Header />
  <Nav />
  <h1>趣味一覧</h1>
  <div id = "hobbies">
  <ul>
    <li v-for="hobby in hobbies" :key="hobby.src">
      <p>{{ hobby.item }}</p>
      <img :src = hobby.src />
    </li>
  </ul>
  </div>
  <Footer />
</div>
</template>

<style scoped>
  h1 {
    text-align: center;
  }

  #hobbies {
    text-align: center;
  }

  li {
    padding: 10px;
    list-style:none;
  }

</style>

<script>
export default {
    data(){
        return {
          hobbies: [
            {item: "読書", src: require('~/assets/hobbies/reading.png') },
            {item: "プログラミング", src: require('~/assets/hobbies/programming.png') },
            {item: "サイクリング", src: require('~/assets/hobbies/cycling.png') },
            {item: "サブカルチャー", src: require('~/assets/hobbies/subcul.png') },
          ]
        };
      }
    }
</script>
