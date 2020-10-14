<template>
  <div class="outer-container">
    <h3>NodeJs<i class="fab fa-node" style="font-size:26px"></i></h3>
    <h3>Github<i class="fab fa-github" style="font-size:26px"></i></h3>
    <h3>Javascript<i class="fab fa-js" style="font-size:26px"></i></h3>
    <h3>CSS3<i class="fab fa-css3" style="font-size:26px"></i></h3>
    <h3>HTML5<i class="fab fa-html5" style="font-size:26px"></i></h3>
    <h3>ReactJs<i class="fab fa-react" style="font-size:26px"></i></h3>
    <h3>Database<i class="fas fa-database" style="font-size:26px"></i></h3>
    <br>
    <router-link to="/">Home</router-link> 
</div>
</template>

<style scoped>
.outer-container {
    margin: auto;
    width: 50%;
    border: 2px solid #eee;
    border-radius: 8px;
    box-shadow: 8px 8px 8px 0px #A8A8A8;
    padding: 10px;
}
i {
    display: inline-block;
    margin: 15px 15px;
}
@media screen and (max-width: 700px){
    .inner-container {
    display: flex;
    flex-direction: column-reverse;
}
.data-div {
    width: 100%;
    padding: 10px;
}
.outer-container{
    width: 100%;
}
}
</style>