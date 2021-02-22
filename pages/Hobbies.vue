<template>
<div id="main">
  <Header />
  <Nav />
  <h1>趣味一覧</h1>
  <ul>
    <li v-for="hobby in hobbies" :key="hobby">
      {{ hobby.item }}
    </li>
  </ul>
  <Footer />
</div>
</template>

<style scoped>                          
  h1 {
    text-align: center;
  }

</style>

<script>
export default {
    data(){
        return {
          hobbies: [
            { item: "読書" },
            { item: "プログラミング" },
            { item: "サイクリング" },
            { item: "サブカルチャー" },
          ]
        };
      }
    }
</script>