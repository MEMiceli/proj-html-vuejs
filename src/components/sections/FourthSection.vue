<template>
    <div class="container-fluid">
        <div class="container text-center">
           <h4>Our Testimonials</h4>
           <p>If you are planning on developing a product landing app or website,
               <br>
               take a look at this beautiful-crafted
           </p>
           
            
        </div>
        
    </div>
  
</template>

<script>
export default {
    name:'FourthSection'

}
</script>

<style scoped lang="scss">
.container-fluid{
    padding: 5rem;
    background-color: var(--secondary-color);
    background-image: url("../../assets/img/15.png"); /*fallback*/
    background-image: url("../../assets/img/15.png"), linear-gradient(180deg, var(--secondary-color) 85%, var(--primary-color) 85%);
    // background: linear-gradient(180deg, var(--secondary-color) 11%, var(--primary-color) 48%);
    background-position: center top;

}
p{
    color:var(--quinary-colortext);
    font-size: smaller;
}
</style>