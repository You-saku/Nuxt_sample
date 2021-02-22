<template>
<div>
  <div class="container">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Newsreader&display=swap" rel="stylesheet">
      <div>
        <Logo />
        <h1 class="title">
          Nuxt<br>Sample Page
        </h1>
        <div class="links">
          <NuxtLink to="Menu">
            <button id="to_menu" type="submit">Go to Munu</button>
          </NuxtLink>
        </div>
      </div>
  </div>
  <Footer />
</div>
</template>

<script>
export default {}
</script>

<style>

.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Newsreader', serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

#to_menu {
  padding: 10px;
  border-radius: 8px;
  background-color: #00fa9a;
}
</style>
