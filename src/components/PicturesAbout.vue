<template>
  <div class="container">
        <a href="https://socialist-syrup-01160.herokuapp.com/">Contact me, Please </a>
        <!-- <img class="row-cols-md-4" src="../images/marketman.png" height="150">
        <img class="row-cols-md-4" src="../images/webMan.png" height="150">
        <img class="row-cols-md-4" src="../images/adMan.png" height="150"> -->
           
      <card-item 
      data-image="https://images.unsplash.com/photo-1427751840561-9852520f8ce8?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8bWFya2V0aW5nJTIwcGVyc29ufGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=500&q=60">
        <h1 slot="header">Marketing</h1>
        <p slot="content">A Marketing Person</p>
      </card-item>
      <card-item data-image="https://images.unsplash.com/photo-1497493292307-31c376b6e479?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8OXx8Y29kaW5nJTIwcGVyc29ufGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=500&q=60">
        <h1 slot="header">Coding</h1>
        <p slot="content">A Web Developer</p>
      </card-item>
      <card-item data-image="https://images.unsplash.com/photo-1495985429137-999cdd47722a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTl8fGFkdmVydGlzaW5nJTIwcGVyc29ufGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=500&q=60">
        <h1 slot="header">Advertising</h1>
        <p slot="content">An Advertising Man</p>
      </card-item>
      <h3>Hover Me</h3>
          
   
  </div>
</template>

<script>
import CardItem from './CardItem.vue'
export default {
name:"PicturesAbout",
components: {CardItem}
}
</script>

<style scoped>     
        
 a, h3{
  color: rgb(167, 167, 226);
 }       
.container {
  padding: 40px 80px;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
}
a{
   text-decoration: none;
}
</style>