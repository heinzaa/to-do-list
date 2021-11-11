<template>
  <div class="hello">
    <ul>
      <li><a href="default.asp">Home</a></li>
      <li><a href="news.asp">News</a></li>
      <li><a href="contact.asp">Contact</a></li>
      <li style="float:right"><a href="about.asp">User</a></li>
  </ul>
       
        
    

     
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
  margin: 0;
}
li {
  float: left;
  margin: 0 10px;
  
}

ul{
   background-color: black;
   overflow: hidden;
   list-style-type: none;
}

li a:hover{
  background-color: #111;
}

a {
  color: #42b983;
 
}
</style>
