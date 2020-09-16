<template>
    <div id="header">

        <img src="../assets/logo.png" alt="vue logo">
        <h3> Welcome to my first vue app </h3>

    </div>

</template>

<script>
export default {
  name: "pageHeader"
 
};

</script>

<style scoped>

#header{
    
    position: relative;
    top: 0;
    width: 100%;
    background-color: black;
    color: white;
    height: 10vh;

}
img{
    width: 5vw;
    object-fit: cover;
    height: 5vh;
}

</style>