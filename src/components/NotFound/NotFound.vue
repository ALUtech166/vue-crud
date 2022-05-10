<template>
  <div class="title"><h1>Page Not Found</h1></div>
  <BaseCard>
  <p>Page Not Found Please you maybe go to the Home Page 
       <router-link to="/">Home</router-link>
      
  </p>
  </BaseCard>
</template>

<script>
import BaseCard from "../UI/BaseCard.vue"
export default {
     components: {
          BaseCard,
          
     }
}
</script>

<style scoped>
.title {
     margin: 1rem auto;
     text-align: left;
     padding: 2rem;
     text-align: center;
     border-radius: 12px;
     font-family: Georgia, 'Times New Roman', Times, serif;
}

p {
  font-family: Georgia, 'Times New Roman', Times, serif;
  font-size: 19px;
  line-height: 30px;
  
}

h1 {
  font-family: Georgia, 'Times New Roman', Times, serif;
  color: #0F044C;
  font-size: 50px;
  text-align: center;


}
a {
  text-decoration: none;
  color: white;
  justify-content: space-between;
  padding: 0.2rem;
  background-color: #548CA8;
  border-radius: 10%;
}

a:hover,
a:active {
  color: #B2F9FC;
}


</style>