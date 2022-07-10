<template>
  <div class="hello">
  <nav class="navbar navbar-expand-lg navbar-light fixed-top" id="mainNav">
    <!-- <div class="container"> -->
      <a class="navbar-brand" href="https://michaelfan0310.github.io"><img src="../images/favicon.png" alt="icon" width="45px" height="30px" />Michael's Matrix</a>
      <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
        Menu
        <i class="fas fa-bars"></i>
      </button>
      <div class="collapse navbar-collapse" id="navbarResponsive">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="https://michaelfan0310.github.io/">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="https://www.michaelfan0310.ml/vue_aboutme/">About</a>
          </li>
           <li class="nav-item">
            <a class="nav-link" href="https://polar-escarpment-84617.herokuapp.com/">Post</a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="https://socialist-syrup-01160.herokuapp.com/">Contact</a>
          </li>
        </ul>
      

      <div class="col-md-3 text-end">
        <button type="button" class="btn btn-primary"><a href="https://dry-taiga-95009.herokuapp.com/">Sign-up</a></button>
        </div>
      </div>
    <!-- </div> -->
  </nav>
  </div>
</template>

<script>
export default {
  name: 'NavAbout',
  // props: {
  //   msg: String
  // } 
}
</script>


<style scoped>
.navbar-brand:hover,.nav-item:hover {
  transform: scale(1.8);
  }
.navbar {  
      top: 0;   
    }
 
/*     
#title-1, #favicon, .subheading {
      position: relative;
      z-index: 5;
    } */

a {color:#feffde;
    text-shadow: 2px 2px #6dc2b2;     
    }   
    
   
/*  
footer{
      margin-top: 0%;  
      padding-top: 2px;
      padding-right: 3%;
      color:antiquewhite;
      height:5px;
      background-color: #1d695b;
      text-align: right; 
      
    } */
</style>
