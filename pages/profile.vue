<template>
    <div id= "main">
        <Header />
        <Nav />
        <h1>マイプロフィール</h1>
        <div id="topics">
          <ol>
            <li id="basic">
            <h3>名前</h3>
              <span class="value">You-saku</span>
            <h3>出身</h3>
              <span class="value">Gunmma</span>
            <h3>性別</h3>
              <span class="value">Man</span>
            <h3>国籍</h3>
              <span class="value">Japan</span>
            </li>
            <li id="basic">
              <img src="@/assets/kapi.png">
            </li>
          </ol>
        </div>
        <Footer />
    </div>
</template>

<style scoped>
h1 {
  text-align: center;
}

#topics {
  text-align: center;
}

#basic {
  display: inline-block;
  padding: 30px;
}

.value {
  font-style: italic;
  font-size: 17px;
  margin: 50px;
}

</style>
