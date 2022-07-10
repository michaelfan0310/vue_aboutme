<template>
   <div class="masthead backImg">
    <div class="overlay"></div>
    <div class="container">
      <!-- <div class="row"> -->
       
          <div class="page-heading">
            <h1>About Me</h1>
            <span class="subheading">This is what I do</span>
          </div>
        </div>
      <!-- </div> -->
   
  </div>
</template>

<script>
export default {
      name: 'TitleAbout'
}
</script>

<style scoped>
/* header .masthead .backImg{
  height: 30%;
} */
.container{     
      top:-10%;
      padding-bottom: 13%;
    } 
  
  .backImg {
    /* width: 100%; */    
    background-image: url('../images/about-bg2.jpg');
     top: 0;
     left: 0;
    z-index: 0;
     
    background-size: cover; 
    background-color: #868e96;
    width: 100%;
    height: 30%;
     }

    h1{
      padding-top: 10%;
      color: rgba(170, 160, 160, 0.781);
    text-shadow: 2px 2px #054e40ca;}
    h2 {
    display: block;
    padding-top: 0;
    padding-bottom: 30px;
    border-top: none;
    color: rgba(248, 248, 235, 0.644);
    font-family: Cambria,cursive;;
    font-size: 1.5em;
    font-style: italic;
    text-shadow: 2px 2px #01161215;
    }

    header .masthead .overlay{
    position: absolute;    
    background-color: #212529;
       opacity: .5;}
                              
    
</style>