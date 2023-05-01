<script >
  import Card from "./components/Card.vue"
  import "bootstrap/dist/css/bootstrap.css"
  export default{
    data(){
      return {
        doctitle: "Random Dog Images"
      }
    },
    components:
    {
      card:Card
    }
  }
</script>

<template>
  <h5>{{ doctitle }}</h5>

  <card></card>
  <card></card>
  <card></card>
  

  
  
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
