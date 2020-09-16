<template>
    <div id="footer">

        <h3> this is my footer</h3>
        <div id="contact">

            <a href="tel:+5875684533"> call me</a>
            <a href="mailto:khalidamairi3@gmail.com"> Email me</a>
        </div>

    </div>

</template>

<script>
export default {
  name: "pageFooter"
 
};

</script>

<style scoped>

#footer{
    
    position: relative;
    /* bottom: 0; */
    width: 100%;
    background-color: green;
    color: white;
    height: 10vh;
    margin: 0;

}
#contact{
    display: grid;
    justify-items: center;
    align-items: center;
    grid-template-columns: 1fr 1fr;
}

</style>