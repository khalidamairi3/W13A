<template>
    <div id="body">

      <pageSidebar />
      <page-content />

    </div>

</template>

<script>

import pageSidebar from './sidebar.vue';
import pageContent from './content.vue';
export default {
  name: "pageBody",
  components : {
      pageSidebar,
      pageContent
  }
 
};

</script>

<style scoped>

#body{
    
    display: grid;
    grid-template-columns: 3fr 5fr;
    height: 80vh;
    margin: 0;
    

}


</style>