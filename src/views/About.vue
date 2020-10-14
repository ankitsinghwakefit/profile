<template>
  <div class="outer-container">
    <h1>About Me :</h1>
    <h4>A 2017 Batch Mechanical Engineer.</h4>
    <p>I deliver Full-Stack Projects in MERN stack.</p>
    <p>For Front-End design I use ReactJs & VueJs.</p>
    <p>For Back-End development I use NodeJs & ExpressJs.</p>
    <router-link to="/">Home</router-link>
  </div>
</template>

<style scoped>
.outer-container {
  margin: auto;
  width: 50%;
  border: 2px solid #eee;
  border-radius: 8px;
  box-shadow: 8px 8px 8px 0px #a8a8a8;
  padding: 10px;
}

@media screen and (max-width: 700px) {
  .inner-container {
    display: flex;
    flex-direction: column-reverse;
  }
  .data-div {
    width: 100%;
    padding: 10px;
  }
  .outer-container {
    width: 100%;
  }
}
@media screen and (max-width: 900px) {
  .inner-container {
    display: flex;
    flex-direction: column-reverse;
  }
  .data-div {
    width: 100%;
    padding: 10px;
  }
  .outer-container {
    width: 100%;
  }
}
</style>
