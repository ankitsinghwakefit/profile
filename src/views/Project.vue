<template>
<div>
     <div class="outer-container">
         <div class="inner-container">
            <div class="data-div">
                <h2>Title: NGO Website</h2>
                <h3>Technologies Used: 
                <i class="fab fa-github" style="font-size:26px"></i>
                <i class="fab fa-js" style="font-size:26px"></i>
                <i class="fab fa-css3" style="font-size:26px"></i>
                <i class="fab fa-html5" style="font-size:26px"></i>
                <i class="fab fa-react" style="font-size:26px"></i>
                <i class="fas fa-database" style="font-size:26px"></i>
                </h3>
                <h3><a href="https://jolly-neumann-418736.netlify.app/" target="_blank">Live</a></h3>
            </div>
            <div class="image-div">
                 <img alt="Vue logo" src="../assets/NGO.png">
            </div>
         </div>
         <router-link to="/">Home</router-link> |
     </div>

     <div class="outer-container">
         <div class="inner-container">
            <div class="data-div">
                <h2>Title: ProductHunt Clone</h2>
                <h3>Technologies Used: 
                <i class="fab fa-github" style="font-size:26px"></i>
                <i class="fab fa-js" style="font-size:26px"></i>
                <i class="fab fa-css3" style="font-size:26px"></i>
                <i class="fab fa-html5" style="font-size:26px"></i>
                <i class="fab fa-react" style="font-size:26px"></i>
                <i class="fas fa-database" style="font-size:26px"></i>
                <i class="fab fa-node" style="font-size:26px"></i>
                </h3>
                <h3><a href="https://nervous-newton-a2ed19.netlify.app/" target="_blank">Live</a></h3>
            </div>
            <div class="image-div">
                 <img alt="Vue logo" src="../assets/producthunt.png">
            </div>
         </div>
         <router-link to="/">Home</router-link> |
     </div>

     <div class="outer-container">
         <div class="inner-container">
            <div class="data-div">
                <h2>Title: Note Pad</h2>
                <h3>Technologies Used: 
                <i class="fab fa-github" style="font-size:26px"></i>
                <i class="fab fa-js" style="font-size:26px"></i>
                <i class="fab fa-css3" style="font-size:26px"></i>
                <i class="fab fa-html5" style="font-size:26px"></i>
                <i class="fab fa-react" style="font-size:26px"></i>
                <i class="fas fa-database" style="font-size:26px"></i>
                 <i class="fab fa-vuejs" style="font-size:26px"></i>
                </h3>
                <h3><a href="https://hopeful-ardinghelli-fe5100.netlify.app/" target="_blank">Live</a></h3>
            </div>
            <div class="image-div">
                 <img alt="Vue logo" src="../assets/notes.png">
            </div>
         </div>
         <router-link to="/">Home</router-link> |
     </div>

     <div class="outer-container">
         <div class="inner-container">
            <div class="data-div">
                <h2>Title: Signup/Login Component</h2>
                <h3>Technologies Used: 
                <i class="fab fa-github" style="font-size:26px"></i>
                <i class="fab fa-js" style="font-size:26px"></i>
                <i class="fab fa-css3" style="font-size:26px"></i>
                <i class="fab fa-html5" style="font-size:26px"></i>
                <i class="fab fa-react" style="font-size:26px"></i>
                <i class="fas fa-database" style="font-size:26px"></i>
                <i class="fab fa-bootstrap" style="font-size:26px"></i>
                <i class="fab fa-node" style="font-size:26px"></i>
                </h3>
                <h3><a href="https://modest-thompson-3cbc2c.netlify.app/" target="_blank">Live</a></h3>
            </div>
            <div class="image-div">
                 <img alt="Vue logo" src="../assets/signin.png">
            </div>
         </div>
         <router-link to="/">Home</router-link> |
     </div>

       <div class="outer-container">
         <div class="inner-container">
            <div class="data-div">
                <h2>Title: Standalone component</h2>
                <h3>Technologies Used: 
                <i class="fab fa-github" style="font-size:26px"></i>
                <i class="fab fa-js" style="font-size:26px"></i>
                <i class="fab fa-css3" style="font-size:26px"></i>
                <i class="fab fa-html5" style="font-size:26px"></i>
                <i class="fab fa-react" style="font-size:26px"></i>
                <i class="fas fa-database" style="font-size:26px"></i>
                <i class="fab fa-node" style="font-size:26px"></i>
                </h3>
                <h3><a href="https://peaceful-lamarr-7f3e3d.netlify.app/" target="_blank">Live</a></h3>
            </div>
            <div class="image-div">
                 <img alt="Vue logo" src="../assets/stand.png">
            </div>
         </div>
         <router-link to="/">Home</router-link> |
     </div>
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
    margin-bottom: 50px;
}
.inner-container {
    display: flex;
}
.data-div {
    width: 60%;
    padding: 10px;
}
i {
    display: inline-block;
    margin: 15px 15px;
}
img {
    width: 350px;
    height: 250px;
    border-radius: 10px;
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
.image-div {
    width: 100%;
}
img {
     width: 100%;
    height: 250px;
    border-radius: 10px;
}
}
@media screen and (max-width: 900px){
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
.image-div {
    width: 100%;
}
img {
    width: 100%;
    height: 250px;
    border-radius: 10px;
}
}
</style>