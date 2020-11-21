<template>
<div><head>
  <link rel="stylesheet" href="main.css"></head>
 <header style="margin-bottom:2em"> <yo /></header>
 
 </div> 
</template>

<script>
import Form from '~/components/Form.vue'
import yo from '~/components/yo.vue'
export default {
  components: {
    Form,
    yo
  }
}
</script>



<style>
.body {}

.layout {
  margin: 0 auto;
  padding-left: 0vw;
  padding-right: 0vw;
  background-color:none;
}

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 1.67em;
}

.nav__link {
  text-decoration: none;
  font-family:"Arial Rounded MT Bold";
}
</style>
