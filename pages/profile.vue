<template>
    <div id= "main">
        <Header />
        <Nav />
        <h1>マイプロフィール</h1>
        <div id="intro">
          <h2>基本情報</h2>
          顔だしは恥ずかしいのでNGでおねがいします
        </div>
        <div id="topics">
          <ul>
            <li>
              名前
              <span class="value">You-saku</span>
            </li>
            <li>
              出身
              <span class="value">Gunmma</span>
            </li>
            <li>
              性別
              <span class="value">Man</span>
            </li>
            <li>
              国籍
              <span class="value">Japan</span>
            </li>
          </ul>
          <div id="img">
              <img src="@/assets/kapi.png">
           </div>
        </div>
        <Footer />
    </div>
</template>

<style scoped>


h1 {
  text-align: center;
}

#intro {
  text-align: center;
  padding: 2%;
}

#topics {
  display: flex;
}

ul {
  position: relative;
  left: 30%;
}

#img{
  position: relative;
  left: 35%;
}

.value {
  font-style: italic;
  font-size: 17px;
  margin: 50px;
}

</style>
