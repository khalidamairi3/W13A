<template>
    <div id="content">

      <contentWelcome />
      <contentMeeting />


    </div>

</template>

<script>

import contentMeeting from './meeting.vue';
import contentWelcome from './welcome.vue';
export default {
  name: "pageContent",
  components : {
      contentWelcome,
      contentMeeting

  }
 
};

</script>

<style scoped>

#content{
    
    display: grid;
   justify-items: center;
   align-items: center;
    

}


</style>