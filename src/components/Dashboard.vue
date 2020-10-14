<template>
  <div class="outer-container">
    <div class="inner-container">
      <div class="data-div">
        <h2>Ankit Singh</h2>
        <h3>Full Stack Developer</h3>
        <h3>Dharamshala, Himachal Pradesh</h3>
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link> |
        <router-link to="/skill">Skills</router-link> |
        <router-link to="/project">Projects</router-link><br />
        <a class="link" href="https://github.com/ankitsinghwakefit" target="_blank"
          ><i class="fab fa-github" style="font-size:26px"></i
        ></a>
        <i class="fab fa-linkedin" style="font-size:26px"></i>
        <a class="link" href="https://twitter.com/singh_07Ankit" target="_blank"
          ><i class="fab fa-twitter" style="font-size:26px"></i
        ></a>
      </div>
      <div class="image-div">
        <img alt="Vue logo" src="../assets/ankit.jpg" />
      </div>
    </div>
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
.inner-container {
  display: flex;
}
.data-div {
  width: 70%;
  padding: 10px;
}
.link {
  color: #2c3e50;
}
i {
  display: inline-block;
  margin: 15px 15px;
}
img {
  width: 250px;
  height: 250px;
  border-radius: 10px;
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
  .image-div {
    width: 100%;
  }
  img {
    width: 450px;
    height: 250px;
    border-radius: 10px;
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
  .image-div {
    width: 100%;
  }
  img {
    width: 450px;
    height: 250px;
    border-radius: 10px;
  }
}
</style>
