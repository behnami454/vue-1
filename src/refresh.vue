<template>
<div class="btnn">
    <button @click="reloadPage">Reload this page</button>
</div>
  
</template>


<script>
export default {
  data() {
      return {
          name: 'refresh',
              }
            },
             methods:{
            reloadPage() {
            window.location.reload();
                         }
                 }
     
            }
  

</script>
<style>
button{
    padding: 15px;
    background-color: black;
    color:white;
    margin: 10px;
}

</style>

  